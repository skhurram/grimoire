### Example 0
[permalink](#example-0)

{% highlight clojure linenos %}
{% raw %}
user=> (import java.util.Date)
java.util.Date

user=> (def *now* (Date.))
#'user/*now*

user=> (bean *now*)
{:seconds 57, :date 13, :class java.util.Date, :minutes 55, :hours 17, :year 110, :timezoneOffset -330, :month 6, :day 2, :time 1279023957492}
{% endraw %}
{% endhighlight %}


### Example 1
[permalink](#example-1)

{% highlight clojure linenos %}
{% raw %}
;; although not reference-able in Clojuredocs, org.clojure/java.data provides a useful, alternative 'from-java' function that works similarly to bean, but more customizable.  See https://github.com/clojure/java.data for more info.{% endraw %}
{% endhighlight %}


