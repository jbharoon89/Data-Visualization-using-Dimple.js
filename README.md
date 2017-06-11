P6 Data Visualization Project
=============================

This project is in fullfilment to the Udacity Data Analyst Nanodegree
Programme.

Summary
=======

In this project, I have obtained the dataset from RITA | Bereau of
Transportation Statistics, to analyze the performance of the top 6 US
Civil Airlines from January 2010 to March 2017.

Overall, I have analyzed three data visualizations on the aspects of
Overall Delay caused by the Airlines, Delay caused by Airline Carriers
and Ontime performance aspect of the Airlines.

Design - EDA
============

The Exploratory Data Analysis was carried out using RStudio, on intial
loading and analysis of the data, I found out that there were a total of
22 Airlines present in the Dataset and plotting all these airlines
together in a chart will have a lot of disturbances and will make the
data visualization process very streneous, hence, I decided to
concentrate on airlines having a average arrival rate above or equal to
75%.

The top Six Airlines are;

1.  American Airlines Inc.
2.  Delta Air Lines Inc.
3.  ExpressJet Airlines Inc.
4.  Skywest Airlines Inc.
5.  Southwest Airlines Co.
6.  United Air Lines Inc.

From the dataset, I decided to chart out three visualizations to
calculate the performance of the top 6 airlines. The three
visualizations are as follows;

1.  Overall Average Delay per flight(minutes)
2.  Average Delay per flight by Carrier(minutes)
3.  Ontime performance in percentage(%)

I have selected Line Charts for this particular dataset, as we calculate
the overall performance of the airlines over a period of time(years).

The final data visualizations is done using Dimple.js (Charting API for
D3) and the overall visualization is thus improved.

**Visual Encodings:** Generall, the X-axis reperesents performance over
the years and Y-axis represents the time scale in minutes/perfromance
percentages. The data type is a Quantative and Categorical data and
hence, I have used Planar Variables to represent my data.

**Layouts:** Since, the data is in time period(years), I have used Line
Plots for simplicity and better readability.

**Chart Type:** Line Plot

Post Feedback Changes
=====================

After the intial feedback received, I then modified the present Visualization by changing Colors(added fixed colors - by Carrier), added legends to all the charts and also added a short narrative which provides a brief outlook of the visualization.

Feedback
========

As per the project requirement's, I have reviewd the intial data
visualization charts to three reviewers and obtained feedback from them.

index_intial.html, is used for review purpose.

**Question's Asked:**

1.  What do you notice in the visualization?
2.  What questions do you have about the data?
3.  What relationships do you notice?
4.  What do you think is the main takeaway from this visualization?
5.  Is there something you don't understand in the graphic?

**Review 1:**

The visualization does what it's asked to do, but, it would be better if
you can add legends and improve up the visualizations by adding
summmary/information regarding what the chart is intended for. The
relationships are depicted well, but, as said earlier please do improve
on the readability aspect.

**Review 2:**

Color's are off the chart, please use a fixed color for the airlines,
its hard to understand this way. Do add legends and provide appropriate
information on what each chart is intended for.

**Review 3:**

The performance for the six airlines is well depicted in the charts. Can
you please fix the colors in the charts and add appropriate titles and
legends, aslo why is that all the year point is depicted in red, please
change it, as it makes the chart look very bad. Animations are good,
provides the information needed. however, please do add a story for each
chart.

Final Output Preview:
=====================

[Data Visualization Preview](http://bl.ocks.org/jbharoon89/raw/885fc202d9e8f0c12fc40a83e18fb9f5/)

Resources
=========

1.[Chart Types](http://extremepresentation.typepad.com/files/choosing-a-good-chart-09.pdf)

2.[Data Resource](https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp?pn=1)

3.[Dimple.js Reference](https://github.com/PMSI-AlignAlytics/dimple/wiki/dimple.chart#methods-1)

4.[Stackoverflow Resources - Dimple and R](https://stackoverflow.com/)
