---
layout: page
title: Projects
permalink: /projects/
---

### hyougaibot

#### October 2015 - Present

Twitter bot that tweets readings, definitions and dictionary references for nonstandard kanji characters (hyougaiji). Information on the hyougaiji was filtered from a larger kanji dictionary, EDGRD's KANJIDIC file. This bot will tweet about 11,000 characters, which should take around 5 months. Significant parts of the twitter interface design for this bot were adapted from/inspired by github user tpinecone's hello-world-bot.

This project uses the [KANJIDIC](http://www.edrdg.org/jmdict/edict.html) dictionary file. This file is the property of the Electronic Dictionary Research Group, and is used in accordance with the group's license.

[Github link](https://github.com/asdfhamiltonian/hyougaibot/)

[Twitter](https://twitter.com/hyougai_bot/)

### KanjiAnalyze

#### October 2015 - Present

Script that extracts an ordered dictionary of kanji (Chinese characters) from a larger file, then uses it to analyze Japanese texts. It returns basic statistics (mean, variance, standard deviation, total) for the grade, Japanese Language Proficiency Test (JLPT) level, and frequency ranking of the kanji in the text.

This project also uses the [KANJIDIC](http://www.edrdg.org/jmdict/edict.html) dictionary file. This file is the property of the Electronic Dictionary Research Group, and is used in accordance with the group's license.

[Github link](https://github.com/asdfhamiltonian/kanjiAnalyze/)

### Planets API

#### September 2015 - Present

Simple RESTful API implementation of my planets app using flask. More information in the readme on GitHub.

[Sample API call](http://planetsapi.herokuapp.com/PositionNow/45.523080/-122.681124)

[Github link](https://github.com/asdfhamiltonian/planets_api/)

### Planets

#### May 2015 - Present

Python object that gives the current right ascension, declination, azimuth, and elevation of the planets for any location on earth. Can also approximately calculate these parameters for Pluto. Uses algorithms/equations from ["How to Compute Planetary Positions"](http://www.stjarnhimlen.se/comp/ppcomp.html#20) by Paul Schlyter.

[Github link](https://github.com/asdfhamiltonian/planets/blob/master/planets.py)

### Luna

#### April 2015 - Present

This python object can give the current azimuth and elevation of the moon for any location on earth between the years 1900-2100. I recently added a method for calculating moon rise and set times, but the algorithm still needs some work since the moon does not rise/set in a 24 hour period.

Adapted from [original code](http://www.stargazing.net/kepler/moon2.html) in QBASIC by Keith Burnett.

Further adatped with algorithms/equations from ["How to Compute Planetary Positions"](http://www.stjarnhimlen.se/comp/ppcomp.html#20) by Paul Schlyter.

[Github link](https://github.com/asdfhamiltonian/planets/blob/master/luna.py)

### Wadokei

#### March 2015 - May 2015

This program uses python and tkinter to make a continuously updating wadokei for any location (not including the arctic and antarctic circles). Wadokei are an older form of Japanese clock, and are essentially mechanical sun dials. This means that the lengths of hours differ between night and day and change throughout the year. More information can be found on wikipedia: http://en.wikipedia.org/wiki/Japanese_clock 

Concept for calculating sunrise and sunset from ["Calulating sunrise and sunset in Python"](http://michelanders.blogspot.com/2010/12/calulating-sunrise-and-sunset-in-python.html)​ by Michele Anders.

Reprogrammed from algorithm by NOAA, ["NOAA_Solar_Calculations_year.xls"](http://www.esrl.noaa.gov/gmd/grad/solcalc/calcdetails.html)

<img src="{{ site.url }}/img/projects/wadokei1.png" alt="wadokei" style="width: 400px; float: right"/>

<img src="{{ site.url }}/img/projects/wadokei2.png" alt="wadokei" style="width: 400px; "/>

[Github link](https://github.com/asdfhamiltonian/planets)