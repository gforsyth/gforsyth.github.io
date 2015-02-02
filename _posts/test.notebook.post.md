---
layout: post
title: "test.notebook.post"
date: 15-02-02 12:07:28 
tags:
    - python
    - notebook
---
# Testing ipython notebook post

yep.


**In [1]:**

{% highlight python %}
import numpy
from matplotlib import pyplot
%matplotlib inline
{% endhighlight %}

**In [2]:**

{% highlight python %}
x = numpy.arange(20)
{% endhighlight %}

**In [3]:**

{% highlight python %}
pyplot.plot(x, x**2)
pyplot.plot(x, x**3);
{% endhighlight %}


![png]({{ site.baseurl}}notebooks/test.notebook.post_files/test.notebook.post_4_0.png)

