# Greeting-Chrome-Extension
Chrome extension using Vanilla JavaScript

![title](https://github.com/bawantharathnayakasliit/Greeting-Chrome-Extension/blob/master/screenshot/ss.png)

# How To build this Chrome Extenstion
Source:-https://medium.com/javascript-in-plain-english/https-medium-com-javascript-in-plain-english-how-to-build-a-simple-chrome-extension-in-vanilla-javascript-e52b2994aeeb

Today, I’m going to show you how to make Chrome extension in vanilla JavaScript — that is, plain JavaScript without any additional frameworks like React, Angular, or Vue.

Building a Chrome extension doesn’t have to be difficult — in my first year of programming, I released two extensions, and I made both using just HTML, CSS, and plain JavaScript. In this article, I’ll walk you through how to the same in just a few minutes.

I’ll be showing you how to make a simple Chrome extension dashboard from scratch. If you have your own idea for an extension, however, and just want to know what to add to your existing project files to get it working in Chrome, you can skip down to the section on customizing your own manifest.json file and icon.

# About Chrome Extensions
A Chrome extension is essentially just a group of files that customizes your experience in the Google Chrome browser. There are a few different kinds of Chrome extensions; some activate when a certain condition is met, like when you’re on a store checkout page; some only pop up when you click on an icon; and some appear each time you open a new tab. Both of the extensions that I published this year are ‘new tab’ extensions; the first is Compliment Dash, a dashboard that keeps a to-do list and compliments the user, and the second is a tool for pastors called Liturgical.li. If you know how to code a basic website, then you can code this kind of extension without too much difficulty.

# Prerequisites
We’re going to keep things simple, so in this tutorial, we’ll just be using HTML, CSS, and some basic JavaScript, as well as customizing a manifest.json file that I’ll include below. Chrome extensions vary in complexity, so building a Chrome extension can be as simple or complicated as you want it to be. After you learn the basics here, you’ll be able to create something much more complicated using your own skillset.

# Setting Up Your Files
For this tutorial, we’re going to create a simple dashboard that greets the user by name. Let’s call our extension Simple Greeting Dashboard.

To get started, you’ll want to create three files: index.html, main.css, and main.js. Put these in their own folder. Next, fill the HTML file with basic HTML document setup, and connect it to the CSS and JS files:
'''
<!-- =================================Simple Greeting Dashboard================================= //--><!DOCTYPE html><html><head>  <meta charset="utf-8" />  <title>Simple Greeting Dashboard</title>  <link rel="stylesheet" type="text/css" media="screen" href="main.css" /></head><body>   <!-- My code will go here -->   <script src="main.js"></script></body></html>

'''
