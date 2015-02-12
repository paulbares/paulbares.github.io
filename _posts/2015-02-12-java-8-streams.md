---
layout: post
title:  "Java 8 - Stream usage"
tags: [java, stream]
---

Basic example class using `Stream` feature.

{% highlight java linenos %}
// Basic example
public class StreamExamples{
    public static int [] intArray = new int [] {12,15,67,18,29,40,23,4,59,5};
    public static void main(String[] args) {
        System.out.println("Sum of arrays: " +
            IntStream.range(0, intArray.length).map(i -> intArray[i]).reduce(0, (a, b) -> a + b));
        
        System.out.print("The array includes: ");
        System.out.println(Arrays.toString(
            IntStream.range(0, intArray.length).map(i -> intArray[i]).toArray()));
        
        System.out.print("The array output backwards:  ");
        System.out.println(Arrays.toString(
            IntStream.range(0, intArray.length).map(i -> intArray[intArray.length - 1 - i]).toArray()));
        
        System.out.print("The content of the arrays multiplied by 3: ");
        System.out.println(Arrays.toString(
            IntStream.range(0, intArray.length).map(i -> 3 * intArray[i]).toArray()));
    }
}
{% endhighlight %}

Output:

{% highlight java %}
Sum of arrays: 272
The array includes: [12, 15, 67, 18, 29, 40, 23, 4, 59, 5]
The array output backwards:  [5, 59, 4, 23, 40, 29, 18, 67, 15, 12]
The content of the arrays multiplied by 3: [36, 45, 201, 54, 87, 120, 69, 12, 177, 15]
{% endhighlight %}

Link: 
[stackoverflow post](http://stackoverflow.com/questions/28462556/print-out-formatting/28464576#28464576)


