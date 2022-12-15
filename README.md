# project-MOOC
***
This repository includes a data analysis project I did to compare EdX, Coursera, and FutureLearn.

Please read the full report [here](https://hnuradhyaksa.github.io/posts/2022-11-10-mooc/).

## Description

This project starts with scraping data on the Class Central web. The process will continue with basic data processing using Python in the Jupyter Notebook environment.

Below is a summary of comprehension table containing the actions I took to get this project to completion:

|Comprehension|Technique|Tool|
|:---|:---|:---|
|Data mining|Extract|Python (Beautiful Soup)|
|Data preparation|Clean, Modify|Python (pandas)|
|Data manipulation & exploration|Joins, Ranking, Pivot Table, Statistical Measurement|Python (pandas, NumPy, SciPy)|
|Data visualization|- |Tableau, Python (matplotlib)|
|Reporting|Markdown language|Visual Studio Code|

## Key Insights

 - EdX is the most open platform, yet its popularity is below Coursera. They are also relatively expensive compared to other platforms.
 - Long-duration courses are getting more reviews. This shows that people like the course to be thorough rather than introductory.
 - Beginner courses are reviewed more than other levels. This could indicate that people mainly join online courses to close their knowledge gap of a certain topic.
 - Programming subject hold the most popular subject. This is in accordance with their entry-level salary which is quite high.
 - Personal development subject is also popular in Class Central. This shows that people are aware of their personal growth, mostly for their career advancement.

 # Contents
 ***

 ## Data

Data that has been compiled from the scraping process can be found in the `data/` directory in csv format. For the scraping process itself can be found in my [scraping-directory](https://github.com/hnuradhyaksa/scraping-directory) repository. 
The following is a description of the files in that folder:

 - `by_cost` : contains cost data for each existing courses
 - `by_duration` : contain the list of courses labeled by duration (long, moderate, short)
 - `by_level` : contain the list of courses labeled by level of study (beginner, intermediate, advanced)
 - `by_subject` : contain the list of courses labeled by subject for each platform

 ## Code

 Python:

 - `MOOC.ipnyb` : all data processing activities

 # Source
 ***

 All the data was scraped from [Class Central](https://www.classcentral.com/providers)