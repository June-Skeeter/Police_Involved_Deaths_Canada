---
layout: default
title: The Data
nav_order: 2
---
# Deadly Force (2020)

This dataset covers January 2000 to July 2020 and was collected by the [CBC](https://newsinteractives.cbc.ca/fatalpoliceencounters/).  

* "There is no government database listing deaths at the hands of the police available to the public in Canada, so CBC News created its own. The CBC’s research librarians have collected detailed information on each case, such as ethnicity, the role of mental illness or substance abuse, the type of weapon used and the police service involved, to create a picture of who is dying in police encounters."*
* This database is a collection of secondhand information (eg. press releases), and is an undercount of the true number of incidents.

## Just a Fad
[The dataset was intially published in 2018](https://newsinteractives.cbc.ca/longform-custom/deadly-force), covering incidents from 2000 to 2017.  It was only updated in summer 2020 in response to the killing of George Floyd.  
* A key issue with relying on a news corporation to collect this information, is that it is not updated at regular intervals.
* Once the subject falls out of the news cycle, they have little incentive to continue.
* In the United States, there is a non-profit organization, [Mapping Police Violence](https://mappingpoliceviolence.org/) that maintains a database and updates it on a monthly basis.


## Filling the Gaps
Many records are missing or incomplete.  For example, this dataset does not include the killings of Rodney Naistus and Lawrence Wegner in January and February 2000.


* Rodeny and Lawrence were victims of ["starlight tours"](https://en.wikipedia.org/wiki/Saskatoon_freezing_deaths), a heinous practice where police, abduct indigenous people during winter and drop them off in rural areas far from their homes, leaving them to freeze to death if they couldn't make it home.  

  * I have reached out to to the CBC for comment on why these incidents were omitted from the data set, but they were unable to clarify wheter this was an intentional or accidental omission.
  * I have added incidents that were omitted in the Deady Force Article and updated it through December 2020 to the best of my abilities.  However, it is difficult to find information regarding police killings (esepecially historically) so my updates are also incomplete.

Despite the incomplete nature of this dataset, it is best record available.  It is important to understand the pervasiveness of police violence ans sytemic racism in policing in Canada, This is a problem across North America, not just in the United States.

# 1) Police killings by year in Canada

## 2020 was a record-breaking year, with *at least* 49 police involved killings.
There were *at least* 581 killings between January 2000 - December 2020.  There was a statistically significant (p<0.001) increasing trend of 1.07 killings/year over this period.  Is this trend real? Or an artifact of increased awareness and acess to information?

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


# 2) Age distribution of victims
Histograms show the shape and spread of a dataset.  Here we see the age distribution of victims in 5-year increments.  The histogram shows us that the age is slightly skewed towards older ages.  The mean age of victims is 35.6 and the standard deviation is 11.9.  The youngest victim was 1 and the oldest was 77

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="CA_AgeHist.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="CA_AgeHist.png" target="_blank">View Image in New Tab</a>

# 3) What type of weapon (if any) did the victim have?
Nearly 30% of victims were unarmed.  **Note** Being Armed is does *not* justify any individual police killing.  However, in aggregate a higher number of killings of unarmed people can indicate a predisposition towards excessive use of force.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="CA_Weapon.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="CA_Weapon.png" target="_blank">View Image in New Tab</a>


# 4) Which police services are responsible for the most killings?
There are 86 police services listed in the dataset, of which 11 are responsible for 68% of all police killings.  The RCMP are responsible for 27% (156)) of all police killings in Canada.  They are the federal police and serve as the provincial police in eight provinces and the territories.  The BC RCMP are far and away the deadliest police sericve in Canada.  Large municipal police departments and provincial police are responsible for the majority of the rest police killings.

### Deadliest Police Services in Canada

|Rank|               Department                |Province|Killings|
|---:|-----------------------------------------|--------|-------:|
|   1|RCMP                                     |BC      |      80|
|   2|Toronto Police Service                   |ON      |      57|
|   3|RCMP                                     |AB      |      36|
|   4|Service de police de la Ville de Montréal|QC      |      36|
|   5|Sûreté du Québec                         |QC      |      36|
|   6|Ontario Provincial Police                |ON      |      33|
|   7|Edmonton Police Service                  |AB      |      28|
|   8|Calgary Police Service                   |AB      |      26|
|   9|Vancouver Police Department              |BC      |      24|
|  10|Winnipeg Police Service                  |MB      |      21|
|  11|Peel Regional Police                     |ON      |      16|



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


# 5) The racial breakdown of police killings.
You might hear someone say: "The majority of people killed by police in Canada are White".  This statement isn't false ... but it is also very misleading.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="CA_Race.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="CA_Race.png" target="_blank">View Image in New Tab</a>


# Poll Questions:

### 3) What should we do to get a more accurate picture of the racial breakdown of police killings?
    A) Display the data alongside the proportion of Canada's total population each racial group comprises 
    B) Divide by the total number of police killings to get a percentage
    C) Subtract the Unknown category and then divide by the total number of police killings to get a percentage
    D) Divide the total killings of each racial group by the total population of each racial group
    

# Data Normalization

Demographic groups are not evenly represented in the population.  Canada's population is 73.4% White, but White people only account for 41.5% of police killings.  Meanwhile, Canada's population is only 4.8% Indigenous and 3.4% Black, but these groups account for 17.0% and 8.4% of police killings respectively.  The victim's race is unreported 150 (25.8%) of the incidents, this means the numbers for across racial groups are likely higher than reported.

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

In order to adequately account for this, we need to Normalize our data.  Normalization, is the process of scaling one variable by another.  For example, to find get the proportion of Canada's population made up by each racial group, we can divide the population of each racial group by the total population.  This tells the percentage of Canada's population each racial group makes up.  Normalizing by the sum of a dataset is the simplest example of data normalization.  Doing the same operation to the police killings data allows us to plot them side by side because they are on the same sale (Percentage).

Comparing the proportion of police killings for each demographic group to their respective proportion of the population is informative.  However, its more meaningful to combine the police killings and the population into one statistic.

### The Police Killing Rate (PKR):
The PKR is the number of police killings per unit of population (ie. million) per unit of time (ie. year).  For example, Canada's Total Police Killing Rate is 0.79 killings per million residents per year.

<a href="https://www.codecogs.com/eqnedit.php?latex=PKR&space;=&space;(\frac{581&space;Police&space;Killings}{35,151,728&space;ppl})&space;x&space;(\frac{1,000,000&space;ppl}{21&space;yr})&space;=&space;0.79&space;/&space;million&space;ppl&space;/&space;yr" target="_blank"><img src="https://latex.codecogs.com/gif.latex?PKR&space;=&space;(\frac{581&space;Police&space;Killings}{35,151,728&space;ppl})&space;x&space;(\frac{1,000,000&space;ppl}{21&space;yr})&space;=&space;0.79&space;/&space;million&space;ppl&space;/&space;yr" title="PKR = (\frac{581 Police Killings}{35,151,728 ppl}) x (\frac{1,000,000 ppl}{21 yr}) = 0.79 / million ppl / yr" /></a>


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




# Statistical Testing

What would we expect from a uniform proportional distribution?  A [Chi Square](https://www.youtube.com/watch?v=2QeDRsxSF9M) test can be used to check if the observed number of police killings by racial group is significantly different than what would be expect if the PKR were equal between racial groups.  Here is an example for the country as a whole.

There were 579 police killings in Canada between January 2000 and December 2020, meaning the police killing rate was: 0.78 per million residents per year.
  * If Systemic Racism did not exist in Canada, as the RCMP commissioner Brenda Lucki claimed ... This rate would apply to each demographic group. We can get the expected distribution by multiplying the population of each demographic group by the average PKR and the record length (21 years).
  * The Chi Square test, will compare the expected and observed distribution to see if the deviations in the observed killings are beyond what would be randomly expected.
    * The test is significant to p < 0.0001, meaning there is **VERY STRONG** evidence showing that there are systemic racial biases in police killings.


|                         | Total Population (Millions)   | Expected Distribtuion   |   Observed Killings |
|:------------------------|:------------------------------|:------------------------|--------------------:|
| Total                   | 35.1                          | 581.0                   |                 581 |
| White                   | 25.8                          | 426.0                   |                 241 |
| Asian                   | 3.2                           | 53.0                    |                  17 |
| South Asian             | 1.9                           | 31.0                    |                  12 |
| Indigenous              | 1.6                           | 27.0                    |                  99 |
| Black                   | 1.1                           | 19.0                    |                  49 |
| Arab                    | 0.5                           | 8.0                     |                   5 |
| Latin American          | 0.4                           | 7.0                     |                   3 |
| Visible minority, n.i.e | 0.3                           | 6.0                     |                   5 |
| Unknown                 | --                            | --                      |                 150 |

# Poll Questions:

### 4) Do you think this pattern contiunes at the municipal department level?
    A) Yes
    B) No
    C) Unsure
    

### 5) What impact do you think the missing data (Unknown race) has on this Chi Squared Analysis?
    A) Invalidates  the results
    B) The racial disparities are likely greater than indicated
    C) The racial disparities are likely less than indicated
    D) Minimal impact, the race of Unknown victims is probably distributed similarly to those of known race



<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="US_Data.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="US_Data.png" target="_blank">View Image in New Tab</a>



# Comparing to the United States  

There are more police killings in the United States than in Canada.   


<a href="RawComparison.png" target="_blank">View Image in New Tab</a>

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="RawComparison.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>

# Poll Questions:

### 6) What factors do we need to look at to calculate rates of police killings in Canada and the United States? (select all that apply)
    A) The population of both countries
    B) The record lengths of both datasets
    C) The different socio-economic circumstances of each country
    D) The different rates of gun ownership in each country
    


# Police Killing Rates
By normalizing, we can more directly compare the patterns between geographic regions with different characteristics (Population) and datasets of different lengths.  Police in the United states are, on the whole, more likely to kill someone than Canadian Police.  However, this doesn't tell the full story.  Systemic Racism is pervasive on both sides of the border, and there are sever racial disparities in both countries.

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

The police violence dataset and census for each country use different demographic groupings so we can't directly compare between all groups.  However, three demographic groups: White, Black, and Indigenous are recorded by each census, so we'll compare between these.  Whites are the majority in both countries, while black and indigenous people disproportionately impacted by police killings on both sides of the border.  One Caveat, the race of the victim is unknown for 25% of Canadian and 9% of United States.  This adds uncertainty to the comparison.  It also means that the Police Killing Rates by race are underestimated, especially for Canada.

Scaled, to their respective populations, we can see that Indigenous and Black people are much more likely to be killed by the police than white people in both Canada and the United States and the overall rates for each racial group are higher in the US than Canada.



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

# Systemic Racism in Canadian Policing

However, the disparity between races is actually greater in Canada than the United States.  To show this, we can divide the black and indigenous rates for each country by the white rate (ie. Normalizing again).  This will tell us how many times more likely a black or indigenous individual is to be killed by the police than a white individual in each country.  We can see that Indigenous and Black Canadians are 6.3 and 4.4 times more likely to be killed by police than a White Canadian.  These disparities are higher than in the US.


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


# Poll Questions:
### 7) Which country has a higher frequency of police violence?
    A) Canada
    B) The United States
    C) They're about equal
    
### 8) Which country has a greater racial disparity in incidents of police violence?
    A) Canada
    B) The United States
    C) They're about equal    

# A brief history of the policing in Canada.

This issue isn't restricted to America, it's pervasive in Canada as well and cannot be overlooked. 

* The RCMP were created by Prime Minister John A. Macdonald.  He got the idea for the Mounties from the Royal Irish Constabulary, a paramilitary police force the British created to keep the Irish under control.  Initially called the "North West Mounted Rifles", their primary purpose to clear Indigenous people off their land.  The name was changed to "North-West Mounted Police" because officials in the United States raised concerns that an armed force along the border was a prelude to a military buildup.  This organization was renamed the Royal Canadian Mounted Police in 1904.  If you want to learn more about the history of the RCMP, I suggest you listen to this [podcast](https://open.spotify.com/episode/1hiddm0ySVQUlJDBUtU0vj?si=jblh4sV5RMG7faychcMcQg) by The Secret Life of Canada


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


# Poll Questions:
### 11) Which map gives a more truthful representation of the data? 
    A) Race of Majority of Police Killing Victims
    B) Race Most Likely to be Killed by Police


# Data Classification: Histograms, Classification Schemes & Choropleth Mapping

# Data Types
There are two kinds of data, that both have two sub-types.  Qualitative (descriptive) data includes Nominal and Ordinal Data types.  Nominal data is categorical data with no inherent ranking.  Ordinal data is categorical data that does have a rank.  Quantitative (numeric) data includes Ratio and Interval Data.  Interval data is similar to ratio data, but it lacks an absolute zero point.  Ratio data has an absolute zero point and the difference between values is meaningful.  PKR is ratio data, it can't be negative and a PKR of 2 is twice as high as a PKR of 1.


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="DataTypes.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="DataTypes.png" target="_blank">View Image in New Tab</a>

# Rates by Province/State
We can normalize our data by demographic information at different administrative levels (eg. Province, Municipality) because PKR varies by administrative divisions.  If we want to classify rates, the first step is to look at a histogram.  A Histogram shows us the frequency distribution of a given variable.  Data is grouped into a set of bins and counted.


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Combined_Rate_Hist.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Combined_Rate_Hist.png" target="_blank">View Image in New Tab</a>

# Outliers
Histograms can be useful for spotting outliers in a dataset.  The Indigenous Police Killing rate histogram for the US shows an outlier.  Vermont has a rate many times higher than the nearest value.  This is because the at 1743 individuals, the Indigenoous population of Vermont only makes up 0.3% of the states population.  So one killing diruing this time period leads to a very high PKR.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Combined_Hist_by_Race.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Combined_Hist_by_Race.png" target="_blank">View Image in New Tab</a>

# Classification Methods

We'll cover five classification methods

1) Equal Interval
* Data is split to bins of equal width regardless of distribution

2) Quantiles
* Data is split by percentiles

3) Natural Breaks
* Data is split using the Jenks algorithm

4) Manual Breaks
* We define our own splits

5) Standard Deviation
* Data is split to bins based on distance from the mean

### A note on color choices
Sequential colormaps are the best choice for representing ratio data (eg. PKR).  I suggest you check out [color brewer](https://colorbrewer2.org/#type=sequential&scheme=OrRd&n=5) for help picking out color schemes. 

# Equal Interval
The simplest classification scheme is to just break the data into classes of equal sizes e.g. The minimum is 0.3 and the maximum is 10.6, so we can split that into four bins 2.6 units wide.

### Nunavut has the highest Police Killing Rate of any administrative sub-division in Canada or the United States.   The numbers presented here are contradicted by the [CBC's own reporting](https://www.cbc.ca/news/canada/north/nunavut-police-related-death-rate-high-data-1.5645619).  This article suggests the death rates may be much higher across the north than presented here.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="EqualInterval_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="EqualInterval_Map.png" target="_blank">View Image in New Tab</a>


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="EqualInterval_Hist.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="EqualInterval_Hist.png" target="_blank">View Image in New Tab</a>




# Quantiles
The simplest classification scheme that is based of nthe data distribution.  The data is ranked and broken up by percentiles:
  * class 1 contains 0-20%, class 2 is 20-40%, class 3 is 40-60%, class 4 is 60-80%, & class 5 is 80-100%


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Quantile_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Quantile_Map.png" target="_blank">View Image in New Tab</a>


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Quantiled_Hist.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Quantiled_Hist.png" target="_blank">View Image in New Tab</a>

# Natural Breaks
Data is split using the [Jenks algorithm](http://wiki.gis.com/wiki/index.php/Jenks_Natural_Breaks_Classification).  This algorithm optimizes the data split into "Natural" classes.  The algorithm maximizes within group similarity and between group dissimilarity


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="NaturalBreaks_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="NaturalBreaks_Map.png" target="_blank">View Image in New Tab</a>



<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="NaturalBreaks_Hist.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="NaturalBreaks_Hist.png" target="_blank">View Image in New Tab</a>

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

# Standard Deviation
This distribution-based classification method shows how far a value is from the mean in standard deviations.  It can be very informative to a knowledgeable user, but it is not particularly accessible for the general public.  The standard deviation classification method converts the data to interval data (deviations above/below the mean).  [Diverging colormaps](https://colorbrewer2.org/#type=diverging&scheme=RdBu&n=5) are a better choice for interval data in many instances, as they can better highlight what values are above or below the zero point.


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="STDBreaks_Map.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="STDBreaks_Map.png" target="_blank">View Image in New Tab</a>


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="STDBreaks_Hist.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="STDBreaks_Hist.png" target="_blank">View Image in New Tab</a>


# Poll Questions:

### 9) If you want to highlight the severity of systemic racism in policing, which classification method would be best?
    A) Equal Interval
    B) Quantiles
    C) Natural Breaks
    D) Manual Breaks
    E) Standard Deviation
    
### 10) What classification method might the RCMP choose to minimize the severity of systemic racism in policing?
    A) Equal Interval
    B) Quantiles
    C) Natural Breaks
    D) Manual Breaks
    E) Standard Deviation







