---
published: true
layout: post
title: >-
  Hello World For My Location API
date: 2018-08-05T11:00:00.000Z
tags:
  - Location
  - Cities
  - Regions
  - Countries
image: >-
  https://s3.amazonaws.com/kinlane-productions/api-evangelist/api-evangelist-hello-world-location-api.png
---
<p><img src="{{ page.image }}" width="45%" align="right" style="padding: 15px;" /></p>
I was needing cities, states, countries, and other located related data repeatedly within applications, and across my systems. To help make my work more efficient, I found a complete and usable data set that I could use to drive an API. I was able to find a complete SQL script for a database thanks to [David Graham](https://github.com/prograhammer/countries-regions-cities). Making it dead simple for me to fire up an Amazon RDS (Aurora) instance to act as the backend to my location API.

As of launch, this new API has exposed basic endpoints for each of the three resources, cities, regions, and countries. I'll be adding other features to the road map, based upon the first couple of integrations I need to make. If you have anything you'd like to see added to the API Evangelist Locations API [you can just add to the Github issues for the project](https://github.com/api-evangelist-apis/locations/issues).

[The API Evangelist Locations API](http://locations.apievangelist.com/) is just one of the APIs I offer publicly, while also using the APIs for some of my own internal, and partner related projects. Everything that is needed to work with this API should be available here, within [its self-contained Github repository](https://github.com/api-evangelist-apis/locations). Keeping everything related to this locations API available in one spot, and something I can easily evolve, as well as fork and deploy for anyone else along the way.
