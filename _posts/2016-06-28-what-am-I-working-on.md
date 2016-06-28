---
layout: post
title: What am I working on?
---

I am currently working on a Capstone project at General Assembly. Under the guidance of Carey Anne Nadeau from [Open Data Nation](http://www.opendatanation.com/), I am working to replicate [Chicago's Food Inspection Forecasting](https://chicago.github.io/food-inspections-evaluation/) open source project for Washington, DC. I am also doing this in Python instead of R.

Open Data Nation was the [first entity to replicate Chicago's model](http://www.theatlantic.com/technology/archive/2016/01/predictive-policing-food-poisoning/423126/) and is actively working to replicate the project for additional cities through [FIVAR](http://www.fivar.org/).

So far it has definitely been interesting! I am still cleaning and wrangling my data. My goal is to model the data in the first days of July. In addition to data available on the [District of Columbia Open Data Portal](http://opendata.dc.gov/), I have pulled data from multiple APIs including [Google Places](https://developers.google.com/places/), [Yelp](https://www.yelp.com/developers/documentation/v2/overview), [SeeClickFix](http://dev.seeclickfix.com/), and [Forecast.io](https://developer.forecast.io/). [DC's Health Inspection Reports](http://dc.healthinspections.us/webadmin/dhd_431/web/) are available online, but do not have an API available. I downloaded my target reports locally and parsed them with [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/). I also took this opportunity to try [mongoDB](https://www.mongodb.com/). I used it to house some of my API records.

Check back in August for more information!