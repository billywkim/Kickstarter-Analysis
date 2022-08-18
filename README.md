# Kickstarting with Excel

## Overview of Project

The purpose of this analysis is to determine the best possible outcome (Specifically for theaters) by sorting the data by Launch Date and Goals. The data was filtered to provide an easily legible chart and graph for anyone to read.

## Analysis and Challenges

### Analysis of Outcomes by Launch Date

On the Analysis of Outcomes by Launch Date, a Pivot Table was created to focus on data that would break down the raw data by months of a given year. In this case, the report represents all years but can be filtered to present a specific year. Furthermore, additional filters of Parent Categories were added. In this case, the report was filtered to show only the 'theater' parent category. The image below shows the data based on outcomes of theaters in all years. A line chart was added to represent this information. 

![Launch Date Data](https://user-images.githubusercontent.com/88448731/185032198-ef602416-e504-4153-abc4-927011805c37.PNG)

### Analysis of Outcomes Based on Goals

On the Analysis of Outcomes Based on Goals, the goals were distributed by increments of 5000 and the data was filtered and organized by the number of outcomes (successful, failed, canceled),and also showing its respective percentages. CountIf formulas were used to calculate. Furthermore, a line graph was added to represent each outcome. Based on the line graph, one can see that 0 kickstarters were cancelled, therefore the successful and failed kickstarters mirror each other. 

![image](https://user-images.githubusercontent.com/88448731/185283817-0e38688f-297a-413d-ad9d-49a0d711c9f2.png)

### Challenges and Difficulties Encountered

One of the biggest challenges was the size of the data. With so much information, a tiny mistake can cause a large misinterpretation of the analysis. By double checking formulas, one can ensure that the accuracy of the report is met. The biggest challenge on the 'Outcomes Based on Goals' report was manually adding all of the Goal texts and also creating the formulas between B2:D13. Adding the formulas was simple since most cells could have been copy-pasted but was very repetitive and tedious.

## Results

Two conclusions that can be made for Theater Outcomes by Launch Date are that 1) there are always more successful thater campaigns than failed and canceled campaigns. 2) May was the most successful month for all years. This means that a theater kickstarter will have the highest chance of success if it is launched in May.

A conclusion we can draw for Outcomes Based on Goals is that the Kickstarters with the highest success rates are projects that are Less than 1000 (76% success rate) and 1000-4999 (73% success rate). This means that setting a lower goal will have a higher chance of being successful.

Some limitations of this dataset is that the dataset only ranges between the years of 2009 and 2017. Having information from other years may help to provide more accurate information. Other limitations is that it does not provide the city in which the kickstarters were launched. A city in a large country, like the US, could play a large factor in the outcome of a kickstarter.

With large datasets, it is thankfully easy to create pivot charts and generate all different types of graphs such as success rate by country (pie chart) and number of backers versus outcomes (line chart).
