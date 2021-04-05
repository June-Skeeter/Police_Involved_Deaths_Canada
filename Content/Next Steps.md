---
layout: default
title: Next Steps
nav_order: 4
---

# What's Next?

### Data Validation and Verrificatoin
More work needs to be put into filling gaps in the data
	* There are more incidents, they need to be added
	* The unknonw varibles for existing records need to be filled where possible
	* Add multiple references to verify the records

### Sharing the Data
This data needs to be shared more widely, Systemic Racism is swept under the rug too often in Canada

### Instructional contnent
The workshops are still being refined and updated.  I hope to get them to a point where I can post them on youtube as asynchronous videos to make them more widely accessble.

If any one has any questions, concenrs, comments, or is interested in collaborating on this please contact me at skeeter1@mail.ubc.ca





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



### Statistical Testing

What would we expect from a uniform proportional distribution? 
* If Systemic Racism did not exist in Canada, as the RCMP commissioner Brenda Lucki claimed ... The National PIDR would apply to each demographic group.
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