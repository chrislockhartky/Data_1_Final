README

Project Requirements satisfied in project

1.Read_CSV function 

2.Use built in pandas functions to remove things that don't belong in dataset- I dropped personal names and irrelevant columns from the dataset

3.Make custom functions- entire project is contained in functions but I specifically would like to 
draw attention to me creating a function that returns the share of Overtime, regular and Other pay of a department's total payroll
so that I could create 5 different piecharts of different departments for comparison using only copy and paste and changing two arguments
and the return variable

4.Make 2 basic plots with MatPlotLib- I created a bar chart and a pie chart

5.Interpret your data- As this is in a Jupyter notebook I put this between cells. I would like to draw particular attention to using
this to draw scrutiny to media reports of the understaffing of Louisville Corrections as the Overtime rate there is lower
than the overtime rate of Fire and EMS which receive less media attention.

About

This project is about analyzing payroll trends between departments in Louisville Metro. It compares how much money is spent on each department in terms of employee payroll. It 
also selects 5 departments in order to analyze how much of their payroll is spent on overtime in order to identify ways to make the government more efficient for the taxpayer.
In the end we also find that EMS and Fire possess the greatest share of their payroll spent on OT. This is also contrasted with how much of Corrections is spent on OT as we are
often told og how understaffed Corrections is in the media. This project scrutinizes and nuances this with hard data.

One weakness of the data is that the data does not do a good job defining what the categories mean. Some are self-explanatory like Overtime Pay but others like a category called Other
are not the city assumes that all categories are equal here when theyre not.

Instructions

Run project from Jupyter notebook. Run cells sequentially. Make sure you have internet connection as notebook fetches the spreadsheet from GitHub rather than locally.

Requirements
This project requires the following dependencies:

Pandas
Numpy
Matplotlib
Seaborn
Internet connection to retrieve the CSV
Jupyter Notebook or you can run it directly from Google Colab here: https://colab.research.google.com/drive/1Ob_4LoINyFt5TEgk1Z-PIe2Ve6uskeXF?usp=sharing 
in which case there are no dependencies.