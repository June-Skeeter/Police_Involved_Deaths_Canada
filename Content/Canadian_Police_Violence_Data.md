---
layout: default
title: The Data
nav_order: 2
---
# Deadly Force (2020)

This dataset covers January 2000 to July 2020 and was collected by the [CBC](https://newsinteractives.cbc.ca/fatalpoliceencounters/).  

*"There is no government database listing deaths at the hands of the police available to the public in Canada, so CBC News created its own. The CBC’s research librarians have collected detailed information on each case, such as ethnicity, the role of mental illness or substance abuse, the type of weapon used and the police service involved, to create a picture of who is dying in police encounters."*

This is not an official count because police departments in Canada are not mandated to collect/release all of this information.  This dataset is a collection of second-hand information in the form of press releases and news articles, etc.  Some records are missing or incomplete.  The total number of incidents is higher than detailed here.  For example, this dataset does not include the killings of Rodney Naistus and Lawrence Wegner in January and February 2000.

* Rodeny and Lawrence were victims ["starlight tours"](https://en.wikipedia.org/wiki/Saskatoon_freezing_deaths), a heinous practice where police, abduct indigenous people during winter and drop them off in rural areas far from their homes, leaving them to freeze to death if they couldn't make it home.  
* I have reached out to to the CBC for comment on why these incidents were omitted from the data set, but they were unable to clarify wheter this was an oversite or an intentional omission.

Another key issue with relying on a news corporation to collect this information, is that it is not updated at regular intervals.  The last time the dataset was updated prior to this summer was in 2017. They updated it in 2020 after the killing of George Floyd.  But once the subject falls out of the news cycle, they have little incentive to continue.
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