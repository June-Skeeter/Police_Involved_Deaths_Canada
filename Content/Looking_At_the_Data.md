---
layout: default
title: Trends
nav_order: 3
---

# 1) How are people dying at the hands of police?

There were *at least* 600 police involved deaths in Canada since January 2000.  Of those, 71.9% were a result of police shootings.
* Is this an artifact?  Shootings are the most "noticable" since officers have to report when the discharge a firearm.  Many other forms of violence may go undreported.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="CA_CauseofDeath.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="CA_CauseofDeath.png" target="_blank">View Image in New Tab</a>


# 2) Police shootings by Year

2020 was a record-breaking year, there were *at least* 50 police involved deaths, 35 of which were shootings.
* There was a statistically significant (p<0.001) increasing trend of 1.15 shootings/year over this period.  Police involved deaths mirrors this increasing trend (1.11 deaths/year).
* Is this trend real? Or an artifact of increased awareness and acess to information?
 --\
<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="CA_Trendline.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="CA_Trendline.png" target="_blank">View Image in New Tab</a>

## The Police Involved Death Rate (PIDR):
The PIDR is the number of police killings per unit of population (ie. million) per unit of time (ie. year).  
<a href="https://www.codecogs.com/eqnedit.php?latex=PIDR&space;=&space;(\frac{600&space;Deaths&space;}{35,151,728&space;ppl})&space;x&space;(\frac{1,000,000&space;ppl}{21.25&space;yr})&space;=&space;0.8&space;/&space;million&space;ppl&space;/&space;yr" target="_blank"><img src="https://latex.codecogs.com/gif.latex?PIDR&space;=&space;(\frac{600&space;Deaths&space;}{35,151,728&space;ppl})&space;x&space;(\frac{1,000,000&space;ppl}{21.25&space;yr})&space;=&space;0.8&space;/&space;million&space;ppl&space;/&space;yr" title="PIDR = (\frac{600 Deaths }{35,151,728 ppl}) x (\frac{1,000,000 ppl}{21.25 yr}) = 0.8 / million ppl / yr" /></a>


# 3) Racial Breakdown.

Demographic groups are not evenly represented in the population.  Canada's population is 73.4% White, but White people only account for 42.3% of police killings.  Meanwhile, Canada's population is only 4.8% Indigenous and 3.4% Black, but these groups account for 17.1% and 8.4% of police killings respectively.  The victim's race is Unknown 150 (25.8%) of the incidents, this means the numbers for across racial groups are likely higher than reported.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="CA_Race_Proportional.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="CA_Race_Proportional.png" target="_blank">View Image in New Tab</a>

This does not describe the whole picture, because there are large disparities in the police killing rate between demographic groups.  The PKR for Indigenous and Black people are **2.82** and **1.95** per million people per year.  The PKR for White people is 0.44 per million people per year.


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="CA_Race_Normalized.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="CA_Race_Normalized.png" target="_blank">View Image in New Tab</a>

### Statistical Testing

What would we expect from a uniform proportional distribution?  A [Chi Square](https://www.youtube.com/watch?v=2QeDRsxSF9M) test can be used to check if the observed number of police killings by racial group is significantly different than what would be expect if the PKR were equal between racial groups.  Here is an example for the country as a whole.

There were 579 police killings in Canada between January 2000 and December 2020, meaning the police killing rate was: 0.78 per million residents per year.
  * If Systemic Racism did not exist in Canada, as the RCMP commissioner Brenda Lucki claimed ... This rate would apply to each demographic group. We can get the expected distribution by multiplying the population of each demographic group by the average PKR and the record length (21 years).
  * The Chi Square test, will compare the expected and observed distribution to see if the deviations in the observed killings are beyond what would be randomly expected.
    * The test is significant to p < 0.0001, meaning there is **VERY STRONG** evidence showing that there are systemic racial biases in police killings.


|                         |   Total Population (Millions) |   Expected Distribtuion |   Observed Distribution |
|:------------------------|------------------------------:|------------------------:|------------------------:|
| Total                   |                          35.1 |                     600 |                     600 |
| White                   |                          25.8 |                     440 |                     252 |
| Asian                   |                           3.2 |                      54 |                      17 |
| South Asian             |                           1.9 |                      32 |                      12 |
| Indigenous              |                           1.6 |                      28 |                     105 |
| Black                   |                           1.1 |                      20 |                      50 |
| Arab                    |                           0.5 |                       8 |                       5 |
| Latin American          |                           0.4 |                       7 |                       3 |
| Visible minority, n.i.e |                           0.3 |                       6 |                       5 |
| Unknown                 |                           0   |                       0 |                     151 |


# 4) Which police services are responsible for the most killings?
There are 90 police services listed in the dataset, of which 13 are responsible for 69.7% of all police killings.
* The RCMP are responsible for 27% (162)) of all police killings in Canada.
	* They are the federal police and serve as the provincial police in eight provinces and the territories.
	* The BC RCMP are far and away the deadliest police sericve in Canada.  
* Large municipal police departments and provincial police are responsible for the majority of the rest police killings.

### Deadliest Police Departments in Canada

|Rank|               Department                |Province|Killings|
|---:|-----------------------------------------|--------|-------:|
|   1|RCMP                                     |BC      |      82|
|   2|Toronto Police Service                   |ON      |      58|
|   3|RCMP                                     |AB      |      38|
|   4|Service de police de la Ville de Montréal|QC      |      35|
|   5|Sûreté du Québec                         |QC      |      34|
|   6|Ontario Provincial Police                |ON      |      33|
|   7|Edmonton Police Service                  |AB      |      29|
|   8|Calgary Police Service                   |AB      |      27|
|   9|Vancouver Police Department              |BC      |      25|
|  10|Winnipeg Police Service                  |MB      |      21|
|  11|Peel Regional Police                     |ON      |      16|
|  12|Ottawa Police Service                    |ON      |      10|
|  13|York Regional Police                     |ON      |      10|



<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="PoliceViolenceIncidents.html" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="PoliceViolenceIncidents.html" target="_blank">View map new tab</a>

# Comparing to the United States  

The PIDR in the United States 4.25 times higer than in Canada.  On the whole, US police are more violent than Canadian Police. 

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="NormalizedComparison.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="NormalizedComparison.png" target="_blank">View Image in New Tab</a>

# Racial Disparities

The data for each country use different demographic groupings so we can't directly compare between all groups.  Three demographic groups: White, Black, and Indigenous are recorded by each.
* Whites are the majority in both countries, while black and indigenous people disproportionately impacted by police killings on both sides of the border.  

The PIDR for Indigenous and Black people are much higher than for white people in both Canada and the United States.  The overall rates for each racial group are higher in the US than Canada.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Racial_Comparison.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Racial_Comparison.png" target="_blank">View Image in New Tab</a>


### However, the disparity between races is actually greater in Canada than the United States.

To show this, we can divide the Black and Indigenous rates for each country by the national rate.  This will tell us how many times more likely a Black or Indigenous individual is to be the victim of a police involved death than is "typical" for the country.

We can see that Indigenous and Black Canadians are 3.8 and 2.4 times more likely to be victims than the national average.


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Racial_Disparities.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Racial_Disparities.png" target="_blank">View Image in New Tab</a>


# A brief history of the policing in Canada.
Racism has been ingrained in the misson of the RCMP since its foundation.

* The RCMP were created by Prime Minister John A. Macdonald.  He got the idea for the Mounties from the Royal Irish Constabulary, a paramilitary police force the British created to keep the Irish under control.  Initially called the "North West Mounted Rifles", their primary purpose to clear Indigenous people off their land.  The name was changed to "North-West Mounted Police" because officials in the United States raised concerns that an armed force along the border was a prelude to a military buildup.  This organization was renamed the Royal Canadian Mounted Police in 1904.
* If you want to learn more about the history of the RCMP, I suggest you listen to these by [The Secret Life of Canada](https://www.cbc.ca/listen/cbc-podcasts/203-the-secret-life-of-canada/episode/15798131-s3-the-mounties-always-get-their-land-part-1) and [Commons](https://www.canadaland.com/podcast/the-police-2-the-secret-history-of-the-rcmp/) 


# Ordinal Data
Ratio data (eg. PKR) can be translated to or described as original data.  Sequential color schemes are a good choice for ordinal data as well.  The following is an example of ordinal data, but with a poor choice of category labels.  What does low, medium or high mean in this context?  


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Ordinal_Map_Bad_Labels.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Ordinal_Map_Bad_Labels.png" target="_blank">View Image in New Tab</a>

Here is an example with better choices.  The categories give a good description of what the data is showing.  However, we can't infer anything about the differences between categories.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Ordinal_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Ordinal_Map.png" target="_blank">View Image in New Tab</a>


# Nominal Data
A nominal (categorical) variable can take on one of a limited number of possible values, assigning each record to a nominal category on the basis of a qualitative property.  When working with categorical data, avoid sequential and diverging colormaps, as they give the impression of an order or ranking in the data.  Choose a colormap designed for [categorical data](https://colorbrewer2.org/#type=qualitative&scheme=Accent&n=5).  You don't have to stick with the colors shown on color brewer, but they are a good starting point.

Race is an example of categorical data, and we can choose to attribute a categorical value to the provinces/states in a number of ways.  For instance, we could map the race making up the largest number of police killings in each province/state.


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="MostNumerousRace_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="MostNumerousRace_Map.png" target="_blank">View Image in New Tab</a>

However, this is a bit misleading, for reasons we discussed earlier.  Its not accounting for differential population.  It is more meaningful to map the race most likely to be killed by police in each state/province.  

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="HighestRateRace_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="HighestRateRace_Map.png" target="_blank">View Image in New Tab</a>


### Nunavut has the highest Police Killing Rate of any administrative sub-division in Canada or the United States.   The numbers presented here are contradicted by the [CBC's own reporting](https://www.cbc.ca/news/canada/north/nunavut-police-related-death-rate-high-data-1.5645619).  This article suggests the death rates may be much higher across the north than presented here.


# Manual Breaks
We can define our own break values to classify data.  This allows us to choose more meaningful break values if necessary (round numbers, clean fractions, etc.  The choice of manual breaks can influence the way the data is perceived.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="ManualBreaks_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="ManualBreaks_Map.png" target="_blank">View Image in New Tab</a>


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="ManualBreaks_Hist.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="ManualBreaks_Hist.png" target="_blank">View Image in New Tab</a>



