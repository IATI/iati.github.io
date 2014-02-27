---
layout: post
title: What's in a Registry URL?
---

The United Nations Development Programme have long published lots of data as IATI XML, and shared it via the IATI Registry.  They currently have 154 activity files that (today) detail some 7396 activities ([source](http://iati.github.io/IATI-Dashboard/publisher/undp.html)).

In terms of these 154 files, we noticed a pattern of including date-specifics in the package name and URL.  So, in the latest update Afghanistan was expressed as:

    http://iatiregistry.org/dataset/undp-afg2014

with the title:

    UNDP Activity File Afghanistan 2014*

The source XML linked to [CO_2014/Afghanistan_projects.xml](http://www.undp.org/content/dam/undp/documents/iati_xml/CO_2014/Afghanistan_projects.xml) - this file did contain historical data however.

We wanted to encourage a framework of non date-specific package names and URL, reverting back to the original position of:

http://iatiregistry.org/dataset/undp-afg (no date in URL)

with the title:

    UNDP Activity File Afghanistan*

Again - this would maintain the link to [CO_2014/Afghanistan_projects.xml](http://www.undp.org/content/dam/undp/documents/iati_xml/CO_2014/Afghanistan_projects.xml) 

UNDP agreed - but pointed out that a quirk of the Registry meant it was not possible to "reclaim" the old package name.  Hence, in iterating, they were pushed to add date details in order to generate their new packages.  We therefore worked with the CKAN team at OKF to discover and "purge" older deleted files, thus freeing up the old packages for reuse!  

Phew!

UNDP now have all their current data published at neutral names and URLs, which provides a stable environment.  Note - the end URL to the XML may change, but the wider context will remain consistent.
