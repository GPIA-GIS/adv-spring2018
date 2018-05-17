---
layout: project-page
title: "Humanitarian Crisis Mapping in South Sudan"
linkname: humanitarian-crisis-mapping-in-south-sudan
author: "Claudio De Los Reyes, Greg Pachacz, Adi Gill "
tagline: "A map created for Watchlist illustrating the impact the conflict in South Sudan has on humanitarian access and healthcare staff and facilities."
location:
    - place: South Sudan
project-link:
    - href: https://humcrisis-southsudan.glitch.me/
tags:
    - tag: Conflict, healthcare, humanitarian, vulnerability, refugees 
thumbnail-path: img/humanitarian-crisis-mapping-in-south-sudan/vD8wtsCr.png
img-folder: ../../img/humanitarian-crisis-mapping-in-south-sudan/
timestamp: 5/14/2018 20:28:05
---
Years of conflict have torn at the seams of South Sudan. Fighting between the Dink government forces, Sudan People’s Liberation Movement, and Nuer rebel faction, known as the Sudan People’s Liberation Movement in Opposition (SPLM-IO) has left tens of thousands dead, and over two million people displaced (CNN, UNHCR). During the fight from independence from Sudan, tribal divisions were overlooked, creating a fragile stability. When independence was attained, the external threat that supported the need for tribal unity collapsed, and the conflict reconstituted itself as a fight between Dinka (35.8%) and Nuer (15.6%), the biggest tribes in South Sudan. (CIA, 2016). Since the start of the violence in 2013, attacks from both government and rebel forces spare no area - schools and medical facilities are frequently attacked. This creates a short and long term problem for the people of South Sudan; victims of attacks have nowhere to turn to for medical assistance, and children and families are left unprotected with vaccines from preventable diseases such as Polio. 

This project is a collaboration between Watchlist on Children and Armed Conflict and The New School’s Studley Graduate Program for International Affairs (SGPIA) to create data, visualization, and interactive humanitarian mapping to assist Watchlist in their efforts to advocate for the protection of children in civilians around the world. 

In the first phase of the project, Watchlist provided the SGPIA team with over 40 reports documenting attacks on medical facilities, healthcare providers, or blocks to humanitarian access. These reports record attacks ranging from February 2016 - July 2017, and are produced by organizations such as OCHA, UNHCR, MSF, UNICEF, and Security Insights. 

![]({{ page.img-folder }}uEqX1dir.png)

The attacks were listed on a google sheet and columns were created to separate information such as the type and location of the attack, injuries, casualties. The SGPIA team used online tools such as google maps, openstreetmap, and general online searches to georeference the location of the attack to a specific latitude and longitude. Precision levels of points range from rooftop, intersection, town/city, or state level, depending on the information available on the specific attack. 

![]({{ page.img-folder }}BzvBLP0r.png)

After removing duplicates and finishing the first phase of georeferencing the attacks, the SGPIA team developed 28 final attack points. 

Since South Sudan is the youngest country in the world, founded in 2011, there is little data available on the country. Therefore, SGPIA team members developed additional layers to provide more context on the attacks and to make the map more dynamic. 

Greg Pachacz developed two land type layers by reclassifying a 30m raster of Africa’s land cover created by the National Geomatics Center of China (NGCC). After singling out useful land types by reclassifying all others as NoData, the separated rasters were then converted into polygons. The polygons were then further developed and designed in Mapbox where they were ultimately embedded within the map’s finalized base layer. 

Adi Gill developed a IDP and Refugee Camps layer using satellite imagery from United Nations Operational Satellite Applications Program (UNOSAT). Originally, she found 13 separate IDP & refugee camp shapefiles which reflected all the tent structures in camps. She then had to create a separate shapefile of camp points, by creating a polygon around the tent structure, and finding the centroid of the polygon. More information on this project can be found here. 

Lastly, the SGPIA team added a health sites facilities layer taken from openstreetmap, which displays health site facilities and clinics produced through participatory mapping. 

The SGPIA team created Zoom-to buttons, a drop down menu to display the precision levels, and a checkbox to filter the type of attack using Javascript. These features and layers are housed on an HTML page to display the current situation in South Sudan, and to give the user an interactive, dynamic experience. 
