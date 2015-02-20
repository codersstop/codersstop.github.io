---
layout: post
category : nodejs
title: Hello, World! with Node js
tags : [nodejs, beginner, helloworld, tutorial]
---

Today we are going to learn how to build a hello world application with Node.js.
but before we build our first application on Node JS, you need to have following softwares installed.

Prerequisite
-------------

- Download [Node.js](http://nodejs.org/download/){:target="_blank"} and install it. You can follow instruction given on [setting up Node JS on windows](http://strongloop.com/strongblog/install-node-js-windows/){:target="_blank"}/[linux](https://github.com/joyent/node/wiki/installation#installing-on-linux){:target="_blank"}/[Mac](https://github.com/joyent/node/wiki/installation#installing-on-mac){:target="_blank"}.
Don't worry about the StrongLoop part when you are installing it for windows. You can ignore it.
- Simple text editor ( We like [Sublime](http://www.sublimetext.com/download){:target="_blank"} )
- Browser

Once you're done with Node.js installation, run the below command to make sure that it has been installed successfully.

{% highlight tcsh%}
$ node -v
{%endhighlight%}

And you should see something like following:

{% highlight tcsh%}
v0.10.33in: Thu Feb 19 16:15:58 on console
{%endhighlight%}

If you are running node on windows or Linux , just run the same command as above and output of that command will be similar.

Now download this Node.js [Hello world]({{ site.url }}/assets/Hello-world.zip "Hello, World!") project and unzip it wherever you want. I use Mac so I generally keep it in [/Users/degarg/Documents].

You should see two files in the unzipped folder as below.

<p><img src="/assets/hello-world-files.png" style="width:100%;height:50%;display: -webkit-inline-box;" /></p>


Don't worry about the details in the files, we will tell you what these files are and what each file contains. For now we will just focus on running the application.

Now go to the folder where you have unzipped the Hello world application and run below command.

{% highlight tcsh%}
$ node server.js
{%endhighlight%}

And you should see the following output:

<p><img src="/assets/node-run.png" style="width:80%;height:50%;display: -webkit-inline-box;" /></p>


If everything is fine then you would see following output  when you go to [http://127.0.0.1:1337/] in the browser.

<p><img src="/assets/node-output.png" style="width:80%;height:50%;display: -webkit-inline-box;" /></p>

Congratulations! you have a working Node.js Hello World app.

Details about the app will be explained in the next blog, so stay tuned.

