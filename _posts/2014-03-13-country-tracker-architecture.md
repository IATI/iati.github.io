---
layout: post
---

...or 'Why we chose to use ECMAScript'.

*By Kriss and Shi Blank*

We've been working on a project to build a re-usable piece of code that can be easily hosted by anyone, anywhere and that will tell an interesting story using IATI data, under the working title; IATI Country Tracker https://github.com/IATI/IATI-Country-Tracker

We were asked to build a HTML5 serverless design that would be easy to deploy and configure, so it was inevitable that ECMAScript (i.e. Javascript)  would have to be used browser side.

Languages are always a contentious issue among programmers and picking a language to use for a project is not only a matter of compromise but something that has to be decided on rather quickly or it becomes very hard to make any progress.

We soon discovered that we would also need to have a server side component, something that processes raw data and makes it available to the client in a more digestible format. This could be written in any language but we chose to use a node server. Primarily this allows the same code to be shared between server and client and reduces code dependencies.

On top of this we use a zero configuration database (SQLite) so there is no need to install, configure and maintain a complicated database server.

Even if you do not consider yourself an ECMAScript programmer the ubiquity of the language online means that you have almost certainly worked with it, maybe you even consider it your second language. It is quite simply the language of the web and although Node is still rather new, what it represents is an inevitable, unstoppable spread of the language onto the server.


* [ECMAScript](http://en.wikipedia.org/wiki/ECMAScript) is the technical name of JSscript or JavaScript. 
* [KISS](http://en.wikipedia.org/wiki/KISS_principle) is the design principle behind all of these decisions. 
* [Node](http://nodejs.org/) is a webserver based on googles [V8 ECMAScript engine](https://code.google.com/p/v8/)


