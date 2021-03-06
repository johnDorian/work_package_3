---
title       : Work Package 3
subtitle    : Stable water isotopes
author      : Jason Lessels
job         : University of Aberdeen
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}

widgets     : mathjax           # {mathjax, quiz, bootstrap}
mode        : standalone # {selfcontained, standalone, draft}
knit        : slidify::knit2slides
github:
  user: johnDorian
  repo: work_package_3
hitheme: solarized_light
--- 

<!-- Limit image width and height -->
<style type='text/css'>
img {
    max-height: 560px;
    max-width: 964px;
}
</style>

<!-- Center image on slide -->
<script src="http://ajax.aspnetcdn.com/ajax/jQuery/jquery-1.7.min.js"></script>
<script type='text/javascript'>
$(function() {
    $("p:has(img)").addClass('centered');
});
</script>

## Using isotopic and geochemical tracers to identify sources of runoff

<b>Aims and objectives</b>

1. Identify the main sources of water at the catchment scale.
2. Use this information to improve the understanding of the sources and fate of C through the catchment.

<b>How we will use the data</b>

- <span class='red'>Precipitation samples</span>: Identify the isotopic signature of precipitation inputs
- <span class='red'>Soil water</span>: Identify isotopic signature to monitor mixing of soil water and precipitation and the travel time from soil to the stream.
- <span class='red'>Stream sampling (catchment outlet)</span>: Detect seasonal trends and allow for the calibration of estimated transit times.

---
## Data summary ##

Data           | Frequency | Objective
---------------|-----------|----------
Synoptic sampling | multiple times throughout 13 and 14 | Examine small scales controls
Extra synoptic sites | 2 visits (2014) |  Incorporated into a network geospatial model
Stream discharge  | (15 min - 2014) | Estimating loads and hydrological modeling
Soil water | multiple times at 2 depths (4 locations) during 2014 | Used in estimating transit times and identifying production and sources of DOC
Rainfall collection | throughout 2013 and 2014 | Used as input to transit time modeling
CDOM | (2 weeks during 2014) | Continuous estimates of DOC 


---
## Hydrological time series##
![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 


---
## Isotope overview ##
![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 

> A strong seasonal variation can be seen in the isotopes. 

> The sources of water (rain, snow and soil water) have distinct signals

---
## Temporal isotope data ##
![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 



---
## Soil water Isotopes##
![plot of chunk unnamed-chunk-4](assets/fig/unnamed-chunk-4-1.png) 
> There is a large variation between the two slopes

> This may be useful for identify and tracing carbon in the system



---
## CDOM data ##
![plot of chunk unnamed-chunk-5](assets/fig/unnamed-chunk-5-1.png) 

> CDOM is a good surrogate for DOC.
> There is large daily diurnal variation.

> The rainfall event had a dilution effect on DOC. 

---

## Soil pH data ##

![plot of chunk unnamed-chunk-6](assets/fig/unnamed-chunk-6-1.png) 

> Soil pH data collected at 14C profile sites. 

> Willow sites differ greatly from the other sites.

> Additional samples were collected along transect 2.


---
## WP3 Summary ##

<b> Interesting findings so far</b>
> The isotope data looks promising to inform how C is transported through the catchment.

> Strongly controlled by active layer dynamics. 

> Isotopes will be used to inform the hydrological model of the catchment.

<b> Paper Ideas </b>

> Linking soil dissolved carbon with stable isotopes to identify sources in Siksik

<b> Outreach </b>

Presentation at EGU 2013




--- .title-slide



<br></br>
<br></br>
<br></br>
<br></br>
<br></br>
<hgroup>
    <h1>Work package 4</h1>
</hgroup>


--- 

## Aims and objectives ##

<br></br>
1. Develop a parsimonious hydrological model for an Arctic catchment using hydrological tracers to improve model structure. 

2. Use isotope data to estimate transit times in the catchment. 

3. Improved hydrology and freeze/thaw routines for ECOSSE and improved DOC estimates for parsimonious hydrological model. 

<b>Tasks completed</b>
- Developed a coupled hydrology-biogeochemistry model to simulate stream discharge and DOC for Granger catchment.




---



## Coupled model##

<b>Hydrological component</b>
- Based on the conceptual HBV model.
- Includes an additional modules:
    - for the affect of slope facing aspects, and
    - freeze-thaw processes do to soil frost and permafrost conditions

<b> DOC component</b>
- Based on the DOC components of the ECOSSE model
- Simplified DOC production and loss functions using 
  - a Q10 relationship for temperature, and 
  - a soil moisture modifying term.

---


##  Model outline ##

![alt text](http://github.com/johnDorian/work_package_3/raw/gh-pages/fig2.jpg)

--- 

## Observed data from Granger catchment ##

![plot of chunk unnamed-chunk-7](assets/fig/unnamed-chunk-7-1.png) 

> Subarctic alpine catchment with permafrost on north facing slopes.

> Characterised with large spring melt stream discharge events early spring.

---

##  Stream discharge simulations ##

![plot of chunk unnamed-chunk-8](assets/fig/unnamed-chunk-8-1.png) 

> Discharge simulations captured the spring melt timing and magnitude for most years.

> Simulated discharge is strongly correlated <span class = 'red'>($r^2=0.67$)</span> with observed discharge.


---

##  DOC simulations ##

![plot of chunk unnamed-chunk-9](assets/fig/unnamed-chunk-9-1.png) 

> DOC simulations captured the spring melt timing and magnitude for most years with a strong correlation to the observed DOC <span class = 'red'>($r^2=0.81$)</span>.

> The simulations also indicate that DOC concentrations increase later in the season.


---

## Coupled Simulations ##

![plot of chunk unnamed-chunk-10](assets/fig/unnamed-chunk-10-1.png) 

> Simulations closely resemble observed trends of both DOC and stream discharge.



---

## Simulated soil water DOC ##

![plot of chunk unnamed-chunk-11](assets/fig/unnamed-chunk-11-1.png) 

> Soil water DOC works well for the south facing slope, but is exported a little quickly on the north facing slope.

---

##  Observed DOC v simulated DOC ##

![plot of chunk unnamed-chunk-12](assets/fig/unnamed-chunk-12-1.png) 


---

## Transit time modeling ##

![plot of chunk unnamed-chunk-13](assets/fig/unnamed-chunk-13-1.png) 

> Transit times are based on the _smoothing_ of the isotope signal by the catchment

---

## WP4 summary

<b> Interesting findings so far</b>

> modeling results so far indicate that conceptual models will work in permafrost environments

> Isotopes should be able to be used to estimate transit times, which will improve hydrological models

<b> Paper Ideas </b>

> Evaluation of parsimonious hydrological model of an arctic catchment

> Improving the model using hydrological stable isotopes (transit times)

<b> Outreach </b>

> Presenting conceptual model at EGU 2014

> Submitted manuscript to Hydrological Processes.




