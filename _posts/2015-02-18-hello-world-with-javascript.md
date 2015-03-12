---
layout: post
title: Hello, World! with javascript 
---

Prerequisite
-------------

- Simple text editor ( We like [Sublime](http://www.sublimetext.com/download) )
- Browser

Create a file helloworld.html (you can call it anything)

{% highlight tcsh%}
$ touch helloworld.html
{%endhighlight%}

Copy following content into your helloworld.html

{% highlight html%}
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
</head>
<body>
</body>
</html>
{% endhighlight %}

If you open this file in the browser, you would not see anything! Don't worry, we'll make it say 'Hello, World!' in
couple of minutes.

Now open your html file with a text editor and add following code inside <body> tag

{% highlight html %}
<script>
    alert('Hello, World!');
</script>
{% endhighlight %}

Your file should look as below:

{% highlight html%}
<!DOCTYPE html>
<html>
<head>
    <title>Hello, World!</title>
</head>
<body>
    <script>
        alert('Hello, World!');
    </script>
</body>
</html>
{% endhighlight %}

Now just refresh the page in the browser and Voila you should see 'Hello, World!' as below:

<p><img src="/assets/hello-world-alert.png" style="width:75%;height:50%;display: -webkit-inline-box;" /></p>