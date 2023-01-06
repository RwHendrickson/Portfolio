---
layout: page
title: Projects
---

# Current Projects

## **Mapping Green Zones**

### One Sentence Description

Create an interactive web site that promotes environmental justice and highlights the characteristics of the protected municipal [Green Zones](https://www2.minneapolismn.gov/government/departments/health/environmental-programs/sustainability/green-zones/) in Minneapolis.

### [Map](https://rwhendrickson.github.io/MappingGZ/MVP_2)

### [Repository](https://github.com/RwHendrickson/MappingGZ) 

## **Measuring the Distribution of Environmental Hazards in Minneapolis**

### [Repository](https://github.com/RwHendrickson/GIS5571/blob/main/Final_Project)

### Abstract

It is understood that some parts of Minneapolis experience a greater burden of environmental hazard than others. Anecdotally and visually, this can be correlated to [restrictive housing practices](https://legacy.umn.edu/stories/a-city-divided-0) of the early to mid 20th century. This project aims to quantify the cumulative environmental harms across Minneapolis at a fine spatial resolution with the intention of spatially correlating this with historic restrictive housing practices and modern demographics.

<center>
<img src="/figs/AirQualityHazardsAndAsthma.png" alt="AirQualityHazardsAndAsthma.png" class="responsive" width = 600/>
</center>

### Data Sources

#### [MPCA's Permitted Industrial Emissions](https://www.pca.state.mn.us/air/permitted-facility-air-emissions-data)

#### [MnDoT's Annual Average Daily Traffic (AADT)](https://gisdata.mn.gov/dataset/trans-aadt-traffic-segments)

#### [PLACES Asthma Rates](https://www.cdc.gov/places/index.html)

#### [PurpleAir Observed Particulate Matter 2.5 (PM2.5)](https://map.purpleair.com/1/mAQI/a60/p604800/cC0#11/44.9402/-93.2188)

<center>
<br>
<h3> An example of an air quality hazard index </h3>
<img src="/figs/ExampleHazardIndex.png" alt="ExampleHazardIndex.png" class="responsive" width = 600/>
</center>

<center>
<h3> Interpolation of 6-Month Average PM2.5 Observations</h3>
<img src="/figs/Purple Air Interpolation.png" alt="Purple Air Interpolation.png" class="responsive" width = 600/>
</center>

## **Twin Cities Mobility & Emissions**

In this project, I am exploring the relationship between human mobility and emissions. This involves:

* Aggregating large datasets of device trajectories in the Twin Cities Metropolitan Area
* Measuring human mobility indices at various time scales
* Exploring relationships between mobility indices, observed PM2.5, and municipal carbon emissions.

<center>
<img src="/figs/mpls_mobility.svg" alt="mpls_mobility.svg" class="responsive" width = 600/>
</center>

# Selection of Past Projects

## **Mitigating Runoff on the St. Paul Campus**

The goal of this project was to find the most cost-effective storm-water runoff mitigation strategy for the St. Paul Campus of the University of Minnesota. This involved modeling Rainfall at Surface (RAS) and Surface Absorption (SA) to estimate runoff across the study area as well as approximating flow accumulation using pre-processed Digital Elevation Model (DEM) data. Upon diagnosing the current condition of the campus’ storm preparedness, mitigation measures were proposed to bring net runoff of each watershed to zero.

<center>
    <iframe src="/figs/25mm_Mitigation_map.pdf#toolbar=0" width="100%" height="1000px">
    </iframe>
</center>

## **Modeling Cercarial Dermatitis**

<center>
<img src="/figs/REU Poster.png" alt="REU Poster.png" class="responsive" width = 500/>
</center>

In the summer of 2016, I participated in an undergraduate research experience at the University of Wisconsin – La Crosse. Following their crash course in mathematical ecology, my mentors, [Dr. Greg Sandland](https://www.uwlax.edu/profile/gsandland/) and [Dr. James Peirce](https://www.uwlax.edu/profile/jpeirce/), paired me with another undergraduate student, [Kelly Buch](http://feffermanlab.org/kelly.html). 

Tasked with finding our own research topic, my partner and I scoured countless articles and research papers. We eventually resolved to study cercarial dermatitis, also known as swimmers’ itch, because the control practices at that time were particularly harmful to lake ecosystems. By the end of the summer, we had built our own mathematical model of the parasite-host dynamics and coded a specialized RK4 differential equation solver into Matlab. This allowed us to experiment with more ecologically sound treatment methods and devise recommendations for lake management across the Midwest.

We later presented our project at the 2017 Joint Mathematics Meeting in Atlanta, and our preliminary work led to a [publication](https://www.researchgate.net/publication/342077609_A_mathematical_model_for_the_control_of_swimmer%27s_itch) in 2020 by Dr. Peirce and Dr. Sandland, in which we are acknowledged.
