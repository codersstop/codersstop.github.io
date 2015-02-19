---
layout: post
title: Hello, World! with Node js
---

Today we are going to learn how to build a hello world application with Node js.
but before we build our first application on Node JS, you need to have below software installed.

Prerequisite
-------------

- Download [Node JS](http://nodejs.org/download/) and install it. you can follow instruction given on [setting up Node JS on windows](http://strongloop.com/strongblog/install-node-js-windows/)/[linux](https://github.com/joyent/node/wiki/installation#installing-on-linux)/[Mac](https://github.com/joyent/node/wiki/installation#installing-on-mac).
Don't worry about the StrongLoop part when you are installing it for windows. You can ignore it.
- Simple text editor ( We like [Sublime](http://www.sublimetext.com/download) )
- Browser

Once you complete the node js installation , just run the below command to make sure that it has installed successfully.

{% highlight tcsh%}
$ node -v
{%endhighlight%}

And you should see something like below

{% highlight tcsh%}
v0.10.33in: Thu Feb 19 16:15:58 on console
{%endhighlight%}

if you are running node on windows or Linux , just run the same command as above and output of that command will be similar.

Now download this node [Hello world]({{ site.url }}/assets/Hello-world.zip "Hello, World!") project and unzip it wherever you want. I use Mac so i generally keep in [/Users/degarg/Documents], but you can copy and unzip it anywhere.

you should see two files in the unzipped folder as below.

![Hello, World! Alert box]({{ site.url }}/assets/hello-world-files.png "Hello, World!")

Don't worry about the details, we will tell you what these files are and what each file contains. for now we will just focus on running the application.

Now go to the folder where you have unzipped the Hello world application and run below command.

{% highlight tcsh%}
$ node server.js
{%endhighlight%}

And you should see the below output

![Node run! Alert box]({{ site.url }}/assets/node-run.png "Node run result!")

if everything is fine then you see see the below when you type [http://127.0.0.1:1337/] in the browser.

![Node output! Alert box]({{ site.url }}/assets/node-output.png "Node output browser!")

