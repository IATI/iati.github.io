---
layout: post
categories: [validator]
---

[IATI Public Validator](http://tools.aidinfolabs.org/validator/) is a simple tool to allow people to check whether or not their IATI XML validates against the schema. As we now have a few different versions of the schema, we need to make sure users can select the appropriate version against which they wish to check their data.

Ben has done the work to make sure the tool now offers verison 1.03 as default.

We've also moved the code into our new [IATI GitHub organisation account](https://github.com/IATI/). This is part of a plan to move all of the 'IATI Code' into one place, and out of individual accounts where much of it has resided for the past couple of years.

In the near future we hope to move the service itself onto the iatistandard domain as we are also hoping to try to ensure our code lives in places that are easy for people to find, and that make sense!

We also investigated the [URL validation bug](https://github.com/IATI/IATI-Public_Validator/issues/12) and we think we have found a bug in the `libxml2` library used to parse XML files. It seems that when XML is parsed using the streaming API, then it errors on `xsd:anyURI`. We have [reported it upstream](https://bugzilla.gnome.org/show_bug.cgi?id=709171), and are taking a look at our code to see if we can work around it.
