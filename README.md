# BENCHMARKS: A Citizen’s Scorecard on Judicial Accountability

This project aims to determine the conditions under which judicial rulings are likely to be reversed in Massachusetts. Focusing on cases appealed to the Massachusetts Supreme Judicial Court and Appellate Courts from 2008–2019, the goal was to use data science as a tool of investigative journalism to uncover never before-seen patterns of judicial behavior. This project was done as a class project in the CS 506:Tools for data science class @ Boston University.  

## Ouestions we aim to answer

* What proportion of cases are reversed in Massachusetts? 
* What are the similarities between cases that are reversed?
* Is it possible to predict when a case is going to be reversed ? 

## Data 

The main data source is [masscases](http://masscases.com/), a collection of reports, from the Massachusetts government website. Public opinions text of the Supreme Judicial Court (SJC) and the Appeals Court cases were scraped from here. The data covers civil and criminal cases in the state of Massachusetts from 2008 to 2019. Many features of cases were collected including hearing dates, judges, defendants, verdicts, reversals, etc. 

## Results of Analysis

The figure below shows the ratio of case affirms/reversals among the supreme and appellate courts. 

![Case reversals](/images/reversal_ratio.png)

The figure below shows judges of interest who had a reversal ratio of > 50%.

![Case reversals by Judge](/images/judge_reversal_histogram.png)

The figure below shows judges with the most reversed cases recently.

![Case reversals by Judge](/images/highest_judge_reversals.png)

The figure below shows factors which contribute the most to case reversals with their relative importances plotted on the y axis.

![Case reversals by Judge](/images/reversal_factors.png)

This is a brief overview of the results. For an in depth view please check out the [jupyter notebooks here](/src/jupyter).

## Running instructions

For a quick run just clone the repo and go to the [jupyter notebooks here](/src/jupyter). The notebooks cover the code for preprocessing and the classifiers built for case reversal prediction. More detailed running instructions are provided in the respective folder

### Directory Structure

* `data`: All data for project
* `src`: All code for project
* `report` : Project reports
* `images` : poster, readme images, etc
