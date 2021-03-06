---
author: "Benjamin"
comments: true
date: "2011-02-18T16:36:57.000Z"
layout: "post"
title: "HTMLGenerator - display Silex sites in HTML 5"
categories: ["Plugins"]
tags: ["html"]

---
This plugin allows you to generate an HTML version of your websites. This is perfect for mobiles or internet tablets. And this is lighter too.

If your visitor do not have Flash, he should be automatically redirected to the HTML version of your website. If he does not have Flash nor Javascript, a link is displayed to visit the HTML version of the website.

![HTML 5 plugin for Silex](https://www.silexlabs.org/wp-content/uploads/2011/02/plugin2.png)


### Abotu this plugin


After having installed and activated it, you can access the HTML version of your websites by accessing your website's URL followed by &format=html For example, if you access your website at the URL : http://myserver/?/myPublication then you can access the HTML version of it at http://myserver/?/myPublication&format=html

Also note that deeplinks should be put directly after the publication's name without any hash. For example, in if in Flash version you have the following URL:
> http://myserver/?/testsimple#/start/test

You can access the HTML version by going at
> http://myserver/?/testsimple/start/test&format=html


### Installation


To install this plugin on a silex server, use the [manager's plugin installer - see the tutorial](https://www.silexlabs.org/?p=1447), or copy the plugin folder in the silex_server/plugins folder.


### Activation


In the manager, go to "Manage", click on the publication on which the plugin should be activated, then click on "Plugins > Activate a plugin", and finally click on the plugin icon and then on "confirm".

Then you can click on the plugin name which appeared in the list of activated plugins, and edit its parameters.


### Parameters


The parameters :




  * Default format: values can be 'html' or 'flash'. It is the format which will be displayed by default, i.e. if there is not a format given in the URL (the '&format=html' or '&format=flash' in the address).


  * CSS declaration: Enter here CSS declaration, e.g. "body{font-family: Verdana;}". Only taken into account in HTML version of the site. Your CSS must be URL-encoded, you can [use this tool to do it](http://www.albionresearch.com/misc/urlencode.php). It should look like this: body%7Bfont-family%3A%20Verdana%3B%7D


Source code of the plugin

Here is the source code of this plugin, which is written in haXe (php target): [html5generator](https://www.silexlabs.org/wp-content/uploads/2011/02/html5generator.zip)


