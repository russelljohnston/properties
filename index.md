---
title       : Should I Live In London?
subtitle    : 
author      : Russell Johnston
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Introduction

- Have you been offered a job in London or thinking of moving there?  

- Wondering if you can afford it or if the commute will be too long?

- Well this app combines API data from the property site [zoopla.co.uk](http://www.zoopla.co.uk) and Google Maps to help you quickly find and explore the ideal suburb that balances rental prices with commuting transit times.

---

## Finding Rental Properties 
<img style="float:right; margin:0px 20px 0px 20px;" src="rentpanel.png" height="500px"/>

- We only consider rental accomodation and the options available to you are: area interested in, search radius, price range, property type, and the number of bedrooms. 

-  The default location is 'Watford, England', but this can of course be changed to any area/town/village/postcode within the UK. 

- Once you're ready, just click on `Fetch Properties` buttons to display your results.

---

## Property Results

<img style="float:right; margin:0px 20px 0px 20px;" src="rentresults.png" width="450px"/>


<!-- Map generated in R 3.2.1 by googleVis 0.5.10 package -->
<!-- Tue Dec 22 21:37:03 2015 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataMapID217e7f8cc693 () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 51.656452,
-0.37701306,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/39041398?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1350 pcm</a>" 
],
[
 51.656452,
-0.37701306,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/39027751?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1350 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/39020132?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £975 pcm</a>" 
],
[
 51.65488,
-0.410286,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/39013331?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £995 pcm</a>" 
],
[
 51.654427,
-0.40251,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/39012567?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1095 pcm</a>" 
],
[
 51.651398,
-0.391731,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/39011972?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1195 pcm</a>" 
],
[
 51.64873,
-0.3812375,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38973260?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £925 pcm</a>" 
],
[
 51.658985,
-0.39723593,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38966082?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £975 pcm</a>" 
],
[
 51.665417,
-0.40084,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38953865?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1395 pcm</a>" 
],
[
 51.664497,
-0.39971924,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38951648?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £785 pcm</a>" 
],
[
 51.65712,
-0.39783424,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38951660?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1250 pcm</a>" 
],
[
 51.65243,
-0.371796,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38951399?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £1800 pcm</a>" 
],
[
 51.659367,
-0.392707,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38948101?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £895 pcm</a>" 
],
[
 51.66679,
-0.385715,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38948085?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £950 pcm</a>" 
],
[
 51.65529,
-0.41266656,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38948105?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £795 pcm</a>" 
],
[
 51.66178,
-0.39206234,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38948019?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1395 pcm</a>" 
],
[
 51.66299,
-0.390684,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38943897?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1195 pcm</a>" 
],
[
 51.663387,
-0.3908466,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924788?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1100 pcm</a>" 
],
[
 51.65568,
-0.38263074,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924767?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1350 pcm</a>" 
],
[
 51.643517,
-0.391944,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924790?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1150 pcm</a>" 
],
[
 51.6527,
-0.4078171,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924761?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £975 pcm</a>" 
],
[
 51.6527,
-0.4078171,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924816?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1200 pcm</a>" 
],
[
 51.6527,
-0.4078171,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924774?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £950 pcm</a>" 
],
[
 51.6527,
-0.4078171,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924812?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1150 pcm</a>" 
],
[
 51.654427,
-0.40251,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38924840?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1175 pcm</a>" 
],
[
 51.651398,
-0.391731,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38918008?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1225 pcm</a>" 
],
[
 51.643517,
-0.391944,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38900061?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1100 pcm</a>" 
],
[
 51.66132,
-0.396643,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38898777?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1750 pcm</a>" 
],
[
 51.655083,
-0.400087,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38895957?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1100 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38884855?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £975 pcm</a>" 
],
[
 51.664497,
-0.39971924,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38876821?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £1050 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38876110?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £975 pcm</a>" 
],
[
 51.652615,
-0.394695,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38868021?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1050 pcm</a>" 
],
[
 51.656105,
-0.3907625,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38811421?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £725 pcm</a>" 
],
[
 51.66122,
-0.39794767,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38790224?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1200 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38750872?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £1100 pcm</a>" 
],
[
 51.663387,
-0.3908466,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38751753?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1100 pcm</a>" 
],
[
 51.664497,
-0.39971924,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38747526?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1250 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38742530?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £1050 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38734667?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £975 pcm</a>" 
],
[
 51.653225,
-0.393907,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38693197?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1200 pcm</a>" 
],
[
 51.656452,
-0.37701306,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38691004?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1350 pcm</a>" 
],
[
 51.66679,
-0.385715,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38691091?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £850 pcm</a>" 
],
[
 51.656452,
-0.37701306,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38674492?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1350 pcm</a>" 
],
[
 51.652855,
-0.368991,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38677514?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1950 pcm</a>" 
],
[
 51.656105,
-0.3907625,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38665667?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £875 pcm</a>" 
],
[
 51.65329,
-0.4117225,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38579563?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £795 pcm</a>" 
],
[
 51.66178,
-0.39206234,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38560555?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1400 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38462877?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £1100 pcm</a>" 
],
[
 51.6537,
-0.39506167,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38394936?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £1101 pcm</a>" 
],
[
 51.652855,
-0.368991,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38344484?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £2396 pcm</a>" 
],
[
 51.652855,
-0.368991,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38334119?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1950 pcm</a>" 
],
[
 51.65535,
-0.40021235,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38254673?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £725 pcm</a>" 
],
[
 51.659367,
-0.392707,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38247866?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1150 pcm</a>" 
],
[
 51.666485,
-0.4060276,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38246781?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1295 pcm</a>" 
],
[
 51.663902,
-0.39163926,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38068784?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £995 pcm</a>" 
],
[
 51.650738,
-0.398339,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/38064225?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £975 pcm</a>" 
],
[
 51.663383,
-0.406157,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/37902146?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1150 pcm</a>" 
],
[
 51.652348,
-0.368901,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/37114314?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £2400 pcm</a>" 
],
[
 51.659367,
-0.392707,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/36011328?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £750 pcm</a>" 
],
[
 51.656452,
-0.37701306,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/35442445?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1350 pcm</a>" 
],
[
 51.65712,
-0.39783424,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/34571700?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1101 pcm</a>" 
],
[
 51.64873,
-0.3812375,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/34081810?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1350 pcm</a>" 
],
[
 51.665417,
-0.40084,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/33192937?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1295 pcm</a>" 
],
[
 51.663902,
-0.39163926,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/32433425?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1000 pcm</a>" 
],
[
 51.659367,
-0.392707,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/31745327?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1100 pcm</a>" 
],
[
 51.65284,
-0.40640834,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/26737065?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>1 bedroom £775 pcm</a>" 
],
[
 51.665333,
-0.3902615,
"<a target='_blank' href='http://www.zoopla.co.uk/to-rent/details/17950099?utm_source=v1:8K6FHiHeGxWLqgGtZeAh5SP5PQAm1K-L&utm_medium=api'>2 bedroom £1150 pcm</a>" 
] 
];
data.addColumn('number','Latitude');
data.addColumn('number','Longitude');
data.addColumn('string','propertylink');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMapID217e7f8cc693() {
var data = gvisDataMapID217e7f8cc693();
var options = {};
options["showTip"] = true;
options["showLine"] = true;
options["enableScrollWheel"] = true;
options["mapType"] = "normal";
options["width"] =    450;
options["height"] =    270;

    var chart = new google.visualization.Map(
    document.getElementById('MapID217e7f8cc693')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "map";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartMapID217e7f8cc693);
})();
function displayChartMapID217e7f8cc693() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartMapID217e7f8cc693"></script>
 
<!-- divChart -->
  
<div id="MapID217e7f8cc693" 
  style="width: 450; height: 270;">
</div>


- Returns up to 100 properties from [zoopla](http://www.zoopla.co.uk). 

- We compute the average and median prices  and show the distributions.

- And use the `googleVis` library to show the locations of each property. Click on one of the properties in the above Google Map. [note: the map may not be displaying properly in Chrome browser -it seems to be a bit glitchy. On  a Mac try safari. If still not displaying try refreshing the slide. - sorry]

---

## Transit times

<img style="float:left; margin:0px 20px 0px 20px;" src="transit.png" height="400px"/>

- Once you are happy with your property results, the app will take your entered location and use it to compute train transit times via Google Maps API. 

- Simply enter your desired destination  e.g. this might be the place of work. 

- Then, enter a search radius 

- And finally a departure time. Default is set to roughly a rush hour time and the date set to todays.

- The app will then return a list of stations within yoru search radius followed by transit times.

- Future versions of this app will include a lot more information such as: monthly commuting costs, and other outgoings set against your salary.

---
