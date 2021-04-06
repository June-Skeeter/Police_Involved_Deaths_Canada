---
layout: default
title: Sharing the Data
nav_order: 6
---


# Sharing the Data

This information needs to be disseminated more widely; systemic racism is swept under the rug too often in Canada.  The updated dataset is publicly available on my [github page](https://github.com/June-Spaceboots/Police_Involved_Deaths_Canada/tree/main/Inputs).  I intend to continue working to update, document, and share this dataset.  If anyone has any questions, comments, or interest in collaborating on this please contact me at: skeeter1@mail.ubc.ca

1) The original Deatly Force, downloaded from the article's webpaged.

2) An updated version of the Deadly Force dataset, with some of the Unknown categories (race, age, etc.) have been filled using information from secondary sources.
* Aditionally, I have added a new variable "DEATH CATEGORY", determined uisng the CAUSE DEATH and SUMMARY from the original dataset.
* The "DEATH CATEGORY" can take 4 possible values: Shooting, Use of Force (eg. Taser, Peper Spary, Beating, Restraing, Police Dog), Domestic Violence, Other (eg. Any  police-involved death not falling into another category).  Further subdivision in the futre might be helpful	

3) MissingRecords.csv contains:
* Police Killings that are missing from the original dataset
* Police-Involved Deaths that occured between January 1, 2001 and June 30, 2020
* Police Killings and Police-Involved Deaths from July 1, 2020 to April 4
	* -I've backtrakced everything from KillerCopsCanada thru Nov 2020

4) I've tried to aviod making assumptions on race of the victims when it is unspecified.  The only exception: if an incident occured in a first nation community, I have assumed the victim was Indigenous.