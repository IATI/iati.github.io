---
layout: post
categories: [csv2iati]
title: CSV2IATI Converter Updates
---

*Note: This post covers some of the technical changes, for user migration information, see ["Announcement: CSV2IATI tool"](https://groups.google.com/d/msg/iati-technical/i6zkhUf2d1w/7v9PznPRwUUJ) on the iati-technical mailing list.*

Over the past month we've done various work to improve the CSV conversion tool, now called CSV2IATI. We've moved the public instance to http://csv2iati.iatistandard.org/ and moved the code into the IATI github organisation - https://github.com/IATI/CSV2IATI and https://github.com/IATI/CSV2IATI-backend

We've updated the documentation. Instead of being an external .docx file, the documentation is now part of the github repository. It's now written in [reStructuredText](http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html) (a lightweight human readable markup language) and transformed into html using [Sphinx](http://sphinx-doc.org/). The resulting [user guide is now displayed within CSV2IATI](http://csv2iati.iatistandard.org/docs/user_guide.html).

Various changes have been made to the tools itself, which are listed in our new [CSV2IATI Changelog](https://github.com/IATI/CSV2IATI/blob/master/CHANGELOG.md#version-22). These include various UI changes, recording history of conversions and model saves (although the latter has no UI yet), and generating default elements directly from the schema.
