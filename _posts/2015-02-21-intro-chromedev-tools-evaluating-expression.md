---
layout: post
title: Introduction to Chrome DevTools console -  Evaluating expressions .
categories: JavaScript
tags : [javascript, chromedevtools, console]
---


Chrome DevTools is a playground area for front end web developers. It gives extra arms to know your code properly.
Since, this article focuses just on introduction we would start with basic functionality of *Console* tab.

To open the console tab, do one of the following:

 - Use the keyboard shortcut **Command - Option - J** (Mac) or **Control - Shift - J** (Windows/Linux)
 - Select **View > Developer > JavaScript Console**

<p><img src="/assets/console-tab.png" style="width:80%;display: -webkit-inline-box;" /></p>

Our motive to here is to get you familiar with Console tab and how to evaluate expressions with it.

###Evaluating expressions in Console Tab

Console tab is editable and you can type out your code there. Let's declare to integer variables and get their sum:

<p><img src="/assets/console-tab-adding-two-variables.png" style="width:80%;display: -webkit-inline-box;" /></p>

Well, that wasn't a rocket science so let's do something more exciting. We'll declare a [JavaScript Object](/javascript/2015-02-20-javascript-objects) and access its
attributes and method to get some information.

Type out following code (Use **Shift + Enter** for the next line, pressing just **Enter** would evaluate the expression:)

{%highlight javascript %}
var laptop = {
    brand : "Dell",
    color : "Black",
    price : 400,
    discount : 50,
    getBrand : function(){
        return this.brand;
    },
    getColor : function(){
        return this.color;
    },
    getDiscountedPrice : function(){
        return  "$" + (this.price - this.discount);
    }
}
{%endhighlight%}

{%highlight javascript %}
laptop.brand // "Dell"
laptop.color // "Black"
laptop.getDiscountedPrice() // "$350"
{%endhighlight%}

You must observe expressions being evaluated as below:

<p><img src="/assets/evaluate-js-objects-console-tab.png" style="width:80%;display: -webkit-inline-box;" /></p>

So we're done with the basic introduction of Chrome DevTools Console Tab.
Read here about how to select HTML elements and manipulate them in this article.

Read more : [Using the console](https://developer.chrome.com/devtools/docs/console)

