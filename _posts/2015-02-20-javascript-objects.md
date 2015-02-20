---
layout: post
title: JavaScript Objects Concept explained with example.
categories: JavaScript
tags : [javascript, beginner, javascript-objects, tutorial]
---


JavaScript (JS) is an Object-Oriented language and objects are at the heart of JS.
There are following data types available in JS (type tells you what kind of information a particular variable stores) :

 - Number
 - String
 - Boolean
 - Function
 - Symbol (New type introduced in latest JS edition)
 - ###**Object**

###Object###
Programming is nothing but a mean to represent real world in the virtual world so that we can automate stuff. When we talk about JS objects,
just think of a real world object, for an example the **_Laptop_** in front of you:

{% img /assets/js-object-laptop.png 70x %}

This laptop has properties like color and brand, and methods like start and shutdown. Properties of an object tells us what kind of object we're dealing with, basically the state of the object. Methods of an object are used to manipulate the properties of an object i.e. dealing with the state of the object.

To represent a real world laptop we can create JS object as follows:

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

The best place to play with JavaScript code is Chrome Developer Tool console, you can learn about it here:

Simply copy the above code and paste it in console window of Developer's tool, after that you can access properties and methods as follows:

{%highlight javascript %}
laptop.brand // "Dell"
laptop.color // "Black"
laptop.getDiscountedPrice() // "$350"
{%endhighlight%}

There you go, you learned about core concept of JavaScript, **"Objects"**!