---
layout: project-page
title: "Investigating \"Opportunity Zones\" in New York City"
linkname: investigating-opportunity-zones-in-new-york-city
author: "Sarah Kontos"
tagline: "Opportunity Zones will allow developers to get a tax break to invest in \"bad\" areas. This tool shows you where new development is going "
location:
    - place: New York CIty
project-link:
    - href: https://kontos.glitch.me
tags:
    - tag: New York City
    - tag:  Opportunity Zones
    - tag:  Real Estate
    - tag:  Economic Justice
thumbnail-path: img/investigating-opportunity-zones-in-new-york-city/jUmzLOw.png
img-folder: ../../img/investigating-opportunity-zones-in-new-york-city/
timestamp: 5/15/2018 20:25:12
---
A small provision of the new Congressional Tax Bill signed into law in late 2017 gives tax breaks to investors who are willing to put money into urban areas that have seen historical disinvestment. These “Opportunity Zones” will be created at the census tract level, and are selected by the State government. While proponents will say that this could turn around neighborhoods that badly need money, in places like New York this trend has played out over and over again in the form of gentrification as predatory venture capitalists invest at little cost to them and drive up prices, waiting the neighborhood to become profitable again. The goal of my map is to research the suitability of these locations with an eye for outliers that may have snuck in do to policy (see Hudson Yards on the map), as well as identifying areas that are being primed for gentrification at an institutional level.

In order to measure the thoughtfulness of the placement of these Opportunity Zones, I turned to the metrics created by the Urban Institute to measure inclusion in urban areas. I focused on displaying census tracts in New York across these different subject areas, choosing the six that I believed are most relevant to gentrification: race and class. The “Indicators” buttons toggle demographic details of residents, while the “Racial Gap” buttons are a number that is calculated to show the difference between POC residents and White residents in each of the subjects.

I have also included the locations of all of the Venture Capital Firms in New York City to spatialize the spectre of outside money that will be shaping these Opportunity Zones. Although none of these firms are involved yet, they are always looming in the economic landscape. Click on each firm for a detailed description of what their investment specialty is.

In producing these maps I used a multi-stage process between a few different GIS applications. First I downloaded, sorted, and cleaned the NYC tract and Census data to perform analyses to create each metric in Excel. I then used QGIS to join that information to the tract, and uploaded that data to Carto as layers so they could eventually end up on my website. 

Toggle each button on and off to see how these indicators display spatially. The Opportunity Zones themselves are clickable, displaying the name and neighborhood of each. 
