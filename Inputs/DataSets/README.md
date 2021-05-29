---
layout: default
title: Dataset Docs
nav_order: 6
nav_exclude: true
---

The folder linked contains:
1) The original Deadly Force, downloaded from the article's web page.

2) MissingRecords.csv contains:
* Police Killings that are missing from the original dataset
* Police-Involved Deaths that occurred between January 1, 2001 and June 30, 2020
	* So Far, I've backtracked through KillerCopsCanada's records through January 1, 2019.  Still working on getting through the rest.
* Police Killings and Police-Involved Deaths from July 1, 2020 to April 6
	* -I've backtracked everything from KillerCopsCanada, except postings crosslisted from la C.R.A.P.
* Additionally, I have added a new variable "DEATH CATEGORY", determined using the CAUSE DEATH and SUMMARY from the original dataset.
* The "DEATH CATEGORY" can take 4 possible values: Shooting, Use of Force (eg. Taser, Pepper Spray, Beating, Restraint, Police Dog), Domestic Violence, Other (eg. Any  police-involved death not falling into another category).  Further subdivision in the future might be helpful	
* If an incident occurred in a first nation community, I have entered the victim's race was Indigenous.   Otherwise, I've avoided making assumptions on race of the victims when it is unspecified.

3) An updated version of the Deadly Force dataset, with some of the Unknown categories (race, age, etc.) have been filled using information from secondary sources.
* Added the DEATH CATEGORY
* If I have come across records with information that has been released (name, race, etc.) while working through things, I've added it, but I need to backtrack and add the sources for the updated info.
* In cases where killercopscanada contradicts the CBC data, I've left it as is for now.