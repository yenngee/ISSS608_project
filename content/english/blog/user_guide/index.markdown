---
title: "User Guide"
author: "Joanna Lian & Ng Yen Ngee"
date: 2020-8-8T21:21:47-05:00
image: "images/blog/user_guide.jpg"
slug: []
categories: []
tags: []
---





### Introduction

This is the user guide to the [Application]() that we have designed. The objective of the application is to allow the user to make their own analysis and eventually judge for themselves, who are suspicious employees of GASTech. 

### Structure of App 

Before we begin, let us understand the structure of the application. 

![](../../images/blog/user_guide/structure.jpg)

We have the navigation bar on top to toggle between analyses. The middle portion is where the analysis will happen. There is usually a side panel that allows you to select various types of input, this will result in a change of visualization on the main panel. 

Based on the analyses that you have made, you would have some GASTech employees in your mind that are suspicious. As and when you can add their names to the bottom section. This will further support any analysis that you would have made. 


### Analyzing Credit Card Data 

In this section, we will be analyzing the credit card transactions of the GASTech employees.

#### Histogram 

![](../../images/blog/user_guide/cc_histogram.JPG)

We first start off with some Exploratory Data Analysis where we visualize the data in a form of a histogram and a data table. Below are the options to filter the credit card transaction data: 

+ **Employment Type**
	+ To choose the employment type of the GASTech Employees
	+ Can select more than one department as a filter.
	+ Selection options are: Administration, Engineering, Executive, Facilities, Information and Security
+ **Category of spending**
	+ To choose the expenditure type of each transaction. We have defined each of the spendings as a specific category (see selection options below) 
	+ Can select more than one category as a filter 
	+ Selection options are: Company, Food, Gas, Leisure, Retail 
+ **Category of spending**
	+ To choose whether the transaction is done during Weekday or Weekend. 
	+ Can select only select one. 
	+ Selection options are: Weekday/Weekend
+ **No. of Years in Employment**
  + Slider to choose the range of Years in Employment of the GASTech Employees. 
  + This function will keep the transactions of Employees with selected range of No. of Years in Employment.
+ **Age**
  + Slider to choose the range of Age of the GASTech Employees. 
  + This function will keep the transactions of Employees with selected range of Age.
+ **No. of bins**
  + Slider to choose the number of bins for the histogram visualization. 
  + i.e. the higher the number of bins, the more bars will 'appear' in the histogram visualization. 
+ **Show data table**
  + If selected, the data table containing the credit card transaction will appear. 
  + If not selected, the data table containing the credit card transaction will not appear. 
	
#### Inferential 

![](../../images/blog/user_guide/cc_inferential.JPG)


### Analyzing Email Data 



#### Network Viz 

![](../../images/blog/user_guide/email_network_viz.JPG)

#### Upload your categorization of Email Type

In the visualization we can see the top words that appear in the email subject based on the different categorization of email. Below that bar chart, there is a data table to view the actual data table. 

![](../../images/blog/user_guide/email_load.JPG)

If you are not satisfied with our definition of Email Type, you can upload your own categorization in this tab.

To obtain the excel template of this categorization, click on `Download` and a window to save the file will pop up. 

![](../../images/blog/user_guide/email_load_download.JPG)

Save the file and open it. The file will consist of 2 columns: 

+ Subject: which represents all the email headers between GASTech employees. 
+ EmailType: which is defined by us. The original file consist of 2 categories: Work Vs Non-Work. 

Please edit in the column EmailType. For example: 

![](../../images/blog/user_guide/email_load_excel.JPG)

After you have defined the email type you wish, you would want to upload it into the system. Click on `upload` in the app and select the file you wish to upload. 

![](../../images/blog/user_guide/email_load_upload.JPG)

The category that you have defined will be now stored in the App as can be seen for the additional `EmailType` category in this bar graph. 

![](../../images/blog/user_guide/email_load_after.JPG)

This will also be reflected in the `Network viz` tab. 


### Profile 

![](../../images/blog/user_guide/.jpg)


## Go Forth and Have Fun! 