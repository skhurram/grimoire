{% highlight clojure linenos %}
(defn unchecked-byte
  "Coerce to byte. Subject to rounding or truncation."
  {:inline (fn  [x] `(. clojure.lang.RT (uncheckedByteCast ~x)))
   :added "1.3"}
  [^Number x] (clojure.lang.RT/uncheckedByteCast x))
{% endhighlight %}
