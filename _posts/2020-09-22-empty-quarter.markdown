---
layout: post
title:  "The Empty Quarter"
date:   2020-09-22 9:53:39 +0400
categories: jekyll update
---
![Lower third is rolling sand dunes. Upper two thirds is a gradient blue sky.](https://github.com/havemaps/havemaps.github.io/blob/master/_site/assets/img/2020-09-22-thoughts.JPG?raw=true "The Empty Quarter")

Lately, I have felt nostalgic for my teenage writing days.
Something about isolation---of miles and minds---has always tugged me back to old habits. Seven years on, my brain skips like a scratched CD, looking for somewhere safe to land.

Lately, I have wanted to return to a comfortable place, not with miles but with my mind. Feeling both comfort and betrayal in writing, it's becoming impossible to ignore the intrusive thoughts and prods, compartmentalizing has gone on long enough. Broken machinery and cheap reproductions are still part of me if I can only remember how to how to get them moving again.

<html>
  <head>
    <title>The Empty Quarter<title>
    <meta name="viewport" content="initial-scale=1.0">
    <meta charset="utf-8">
<link rel="stylesheet" href="https://unpkg.com/leaflet@1.4.0/dist/leaflet.css"
integrity="sha512-puBpdR0798OZvTTbP4A8Ix/l+A4dHDD0DGqYW6RQ+9jxkRFclaxxQb/SJAWZfWAkuyeQUytO7+7N4QKrDh+drA=="
crossorigin=""/>

<script src="https://unpkg.com/leaflet@1.4.0/dist/leaflet.js"
integrity="sha512-QVftwZFqvtRNi0ZyCtsznlKSWOStnDORoefr1enyq5mVL4tmKB3S/EnC3rRJcxCPavG10IcrVGSmPh6Qw5lwrg=="
crossorigin=""></script>

	<style>
      /* Always set the map height explicitly to define the size of the div
       /* element that contains the map. */
      #map {
        height: 300px;
        width: 100%
        /* For custom height use width:500px;height:500px; inside the #map selector
        curly brackets. 100% does a full screen map*/
      }
      /* Optional: Makes the sample page fill the window. */
      html, body {
        height: 100%;
        margin: 0;
        padding: 0;
      }

    </style>
  </head>
  <body>

	<div id="map"></div>
    <script>

	  var khali = [23.014978, 53.765416];
	  var mymap = L.map('map').setView(khali, 13);

		L.tileLayer('https://{s}.tile.openstreetmap.org/{z}/{x}/{y}.png', {
		  minZoom: 1,
		  maxZoom: 18,
		  attribution: 'Map data &copy; <a href="https://openstreetmap.org/copyright">OpenStreetMap</a> contributors'
		}).addTo(mymap);

		var marker = L.marker(khali).addTo(mymap);
    /*  marker.bindPopup("<b>Hello world!</b><br>I am a popup.");

  /* Add more locations
  1) Create new location variable var NAME = [lat, long];
  2) Create new marker variable var NameMarker = L.marker(NAME).addTo(mymap);
 3) Create marker popup NameMarker.bindPop("INSERT TEXT AND HTML");
    var AUBlocation = [33.901048, 35.480588];
    var AUBmarker = L.marker(AUBlocation).addTo(mymap);
    AUBmarker.bindPopup("Am I a pop up too");

    var Caramel = [33.895813, 35.482524];
    var CaramelMarker = L.marker(Caramel).addTo(mymap);
    CaramelMarker.bindPopup("My hotel!"); */

    </script>

  </body>
</html>
