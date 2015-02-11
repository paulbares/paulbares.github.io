---
layout: post
title:  "Java Memory Model"
tags: java
---

Here's some intersting links about the Java Memory Model.

- [http://docs.oracle.com/javase/specs/jls/se8/html/jls-17.html#jls-17.4](http://docs.oracle.com/javase/specs/jls/se8/html/jls-17.html#jls-17.4)
- [http://stackoverflow.com/questions/4919392/reorder-normal-field-around-volatile-field](http://stackoverflow.com/questions/4919392/reorder-normal-field-around-volatile-field)
- [http://jeremymanson.blogspot.fr/2007/05/roach-motels-and-java-memory-model.html](http://jeremymanson.blogspot.fr/2007/05/roach-motels-and-java-memory-model.html)
- [http://www.ibm.com/developerworks/library/j-jtp03304/](http://www.ibm.com/developerworks/library/j-jtp03304/)
- [Concrete example: DoubleCheckedLocking](http://www.cs.umd.edu/~pugh/java/memoryModel/DoubleCheckedLocking.html)

{% highlight java linenos %}
// Works with acquire/release semantics for volatile
// Broken under current semantics for volatile
class Foo {
    private volatile Helper helper = null;
    public Helper getHelper() {
        if (helper == null) {
            synchronized(this) {
                if (helper == null)
                    helper = new Helper();
            }
        }
        return helper;
    }
}
{% endhighlight %}

- Google's lecture:

<iframe width="600" height="400" src="https://www.youtube.com/embed/WTVooKLLVT8" frameborder="0" allowfullscreen></iframe>
