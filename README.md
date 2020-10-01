# BENCHMARKS: A Citizen’s Scorecard on Judicial Accountability

This project aims to determine the conditions under which judicial rulings are likely to be reversed in Massachusetts. Focusing on cases appealed to the Massachusetts Supreme Judicial Court and Appellate Courts from 2008–2019, the goal was to use data science as a tool of investigative journalism to uncover never before-seen patterns of judicial behavior. This project was done as a class project in the CS 506:Tools for data science class @ Boston University.  

## Ouestions we aim to answer

* What proportion of cases are reversed in Massachusetts? 
* What are the similarities between cases that are reversed?
* Is it possible to predict when a case is going to be reversed ? 

## Data 

The main data source is [masscases](http://masscases.com/), a collection of reports, from the Massachusetts government website. Public opinions text of the Supreme Judicial Court (SJC) and the Appeals Court cases were obtained from here. The data covers civil and criminal cases in the state of Massachusetts from 2008 to 2018. Many features of cases were collected including hearing dates, judges, defendants, verdicts, reversals, etc. 

## Results of Analysis

![Case reversals](/images/reversal_ratio.png)

This is a brief overview of the results. For an in depth view please check out the [jupyter notebooks here](/src/jupyter).

## Running instructions

### Directory Structure

1. data: All data for project
2. src: All code for project
3. report : Project reports
4. images : poster
