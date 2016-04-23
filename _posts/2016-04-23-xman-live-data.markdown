---
layout: post
title:  "Live data in Demo"
date:   2016-04-23 15:55:09 +0200
author: Benjamin Beret
comments: true
---
The demo website now has access to a live feed of XMAN data.
<!--more-->
You're now able to track real XMAN data in the [demo](demo-page).

The demo doesn't have access to live radar data for security reasons. We're emulating the operational behaviour using [FR24](http://www.flightradar24.com/) data with a polling frequency of 60 seconds.

You're now able to see a live XMAN flight list, with flights appearing and disappering as they enter/exit your sector.

Operational version will have access to real radar data, polled every 5 seconds for maximum accuracy.

[demo-page]: {{site.baseurl}}/demo/
