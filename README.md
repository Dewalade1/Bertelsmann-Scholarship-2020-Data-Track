# Bertelsmann Scholarship 2020 Data Track Course Learning Progress
------------------------------------------------------------

#### Hello,Thank you for coming. This repository is a record of my learning progress on the Bertelsman scholarship data track course. It also contains my progress on fulfilling the 60 days of udacity challenge. I took the pledge on December 14, 2020 but I could not keep up with it so I decided to start over from the beginning starting on January 26th, 2021. I decided to review the entire course in order to refresh my memory and get a little practice in with alteryx before the main nanodegree starts.

* **Credits:** Unless specified, all images were gotten from Bertelsman scholarship data challenge course: Introduction to Problem Solving with Advanced Analytics Nanodegree Program by Udacity*

# Let us begin!

## Day 1 (26/01/2021) | The journey begins

* Restarted the pledge and reviewed lesson 1.
* The basis of this lesson is to use the **Cross Industry Standard Process for Data Mining (CRISP-DM)** as a **Problem Solving Framework** for our Analysis.
* CRISP-DM consists of the following steps: 
  1. Business Issue Understanding
  2. Data Understanding
  3. Data Preparation
  4. Analysis/Modeling
  5. Validation
  6. Presentation/ Visualization.
* Steps of the CRISP-DM framework may be performed multiple times or restart the entire problem solving framework and revise some of the assumptions and decisions made along the way.

**Thoughts:** Don't throw all your data at your model and hope for the best

![The Problem solving framework](./images/the-problem-solving-framework.png)

*Credit: The six steps to the problem-solving framework PDF file I Downloaded from the Bertelsmann Scholarship Data Track Slack Channel*

## Day 2 (27/01/2021) | The methodology map

* Studied lesson 2.1 - 2.8
* The methodology map is meant to be used as we work our way through the analytical problem solving framework.
* It helps us decide which methodology to use to solve a business problem.
* There are 2 types of businesss problems: Predictive and Analytical.

**Thoughts:** The type of bussiness problem you have depends on the purpose of the analysis

![Types of Data Analysis](./images/types-of-data-analysis.png)
*Credit: Lesson2.pdf I downloaded from the Bertelsmann Scholarship Data Track Slack Channel*

## Day 3 (28/01/2021) | Types of data

* Completed Lesson 2
* The methodology map can be used to select the proper model for solving a business problem.
* There are three types of numerical data: 
    * Count
    * Categorical
    * Time-series
* There are two categories of classification data: 
    * Binary classification
    * Non-binary classification

**Thoughts:** Data comes in different types

![numeric datatypes](./images/numeric-data-types.png)

*Numeric Datatypes*

![Binary classification](./images/binary-classification.png)

*Binary classification*

## Day 4 (29/01/2021) | Linear Regression

* Started Lesson 3
* Learnt to perform linear Regression and multiple linear regression analysis using excel
* Learnt about correlation between predictor and target variables.

**Thoughts:** There must be correlation between predictors and target variable to make good predictions with linear regression

![linear Regression](./images/linear-regression.png)

*Graph of Linear Regression*

![plot](./images/tickets-value-plot.png)

*Graph of correlation between predictor and target variables*

![plot](./images/value-contract-no-linear-relationship.png)

*Graph of lack of correlation between predictor and target variables*

## Day 5 (30/01/2021) | Parallel Processing

* Learnt about parallel processing in python on Dataquest.
* Parallel processing can be used to run multiple tasks at the same time.
* There are several workflows for running parallel processes such as starting and joining them simultatiously using for loops or starting each process individually at your prefered times.
* Processes take in functions and arguments for those functions as separate arguments
* Each process is has its own unshared memory
* A shared memory location (shared value) can be created for all processes using the `multiprocessing.Value()` command
* Shared values can be locked from processes preventing them from being updated by certain processes by using a **lock**

**Thoughts:** Parallel processing is a way to run multiple tasks concurrently

## Day 6 (31/01/2021) | Time management

* Studied a course on Time Management
   * Learned that you need to focus on doing what is urgent and important first
   * Delegate all unurgent and unimportant tasks
   * Perform all unurgent or onimportant tasks when free

**Thoughts:** Time management is an effective way to get tasks done

## Day 7 (01/02/2021) | Executive Datastory Telling

 * Took a course on executive datastory telling by Data Story Acadamy
 * I learnt about the general types of executives and their prefered data story and dashboard delivery methods
 * The 5 executive types are: 
    * **The Data Geek:** loves to look at data.
    * **Emailer:** prefers getting reports through emails.
    * **Traveler:** travels a lot so their always on their phones. Send reports designed for phones.
    * **Presenter:** loves presentations. Prefers that you present your reports on a spreadsheed. 
    * **Old School** prefers reporting through PDFs & printouts
 * I learnt that understanding your executives priorities help deliver better data stories.
 * To understand them, ask questions about:
    *  what questions they wanna answer
    *  what actions they intend to take with the results
    *  what key results or metrics they are after

**Thoughts:** Learning about your excecutives would make one a more useful analyst for the company
 
## Day 8 (02/02/2021) | Flowcharts

* Studied Chapter 2: Flow control of automate the boring stuff with python.
* Learnt about using flowcharts and the elements of flow control.

**Thoughts:** Flowcharts are a diagramatic way of representing algorithms. They are very easy to understand.

## Day 9 (03/02/2021) | Alteryx installation

* I spent the day downloading and installing alteryx on my windows PC

![Alteryx downloader](./images/alteryx-installation.png)

*Credit: Me*

**Thoughts:** Alteryx is easy to install and setup

## Day 10 (04/02/2021) | Data visualization

* I learnt how to choose colors to [make your visualizations look more professional](https://blog.datawrapper.de/beautifulcolors/)
* I also learned to [never use pure black in visualizations](https://ianstormtaylor.com/design-tip-never-use-black/)
* I also learnt good ways to choose color lighting is to [check colors in greyscale](https://blog.datawrapper.de/colorblind-check/) using [Color Oracle](http://www.colororacle.org/) and [Vizcheck](http://vischeck.com/)
* I found some useful tools to help me select better colors for my visualizations. These tools are: [Adobe Color](https://color.adobe.com/create/color-wheel), [Color Calculator](https://www.sessions.edu/color-calculator/), and [Learnui color palette picker](https://learnui.design/tools/data-color-picker.html#palette) 
* I found tools to pick out image colors using [Color Picker](https://image-color.com/) and [Adobe Capture](https://www.adobe.com/products/capture.html)

**Thoughts:** Visualization design is all about color understanding 

![Color Wheel](./images/color-wheel.png)

*The Color wheel*        *Image credit: [Datawrapper](https://blog.datawrapper.de/beautifulcolors/)

![dark-background-color-usage](./images/dark-background-color-usage.png)

*Good colors for dark backgrounds*        
*Image credit: [Datawrapper](https://blog.datawrapper.de/beautifulcolors/)

## Day 11 (05/02/2021) | R-squared and adjusted R-squared 

* Learnt about r-squared and adjusted r-squared for linear and multiple linear regression analysis
* To know how good the formula is at approximating the data by calculating the coefficient of determination, or r-squared. R-squared is a coefficient between 0 and 1.
  * **closer to 1:** nearly all variance in the target variable is explained by the model
  * **closer to 0:** nearly none of the variance in the target variable is explained by the model.
  * In general, above 0.7 are considered strong and below 0.3 are considered weak.
  
![R squared](./images/r-squared.png)

*R-Squared*

* Signed up for Alteryx trial version

**Thoughts:** adjusted r-squared is more useful for assessing multiple linear regression models than linear regression models.

## Day 12 (06/02/2021) | Alteryx Data Analysis Reports

* Completed lesson 3
* Learnt how to read an alteryx data analysis report
* Learnt about p-values and r-squared values

![alteryx](./images/results.png)

*Linear Regression Report from Alteryx*

**Thoughts:** Alteryx gives a very detailed report

## Day 13 (07/02/2021) | Scholarship course practice project

* Started on lesson 4
* Still working on developing a good model for the practice project.

![workflow](./images/practice-project-workflow.png)

*My practice project workflow (still a work in progress)*

**Thoughts:** Developing a good workflow for the pracrice project wasn't an easy tast

## Day 14 (08/02/2021) | Datasets

* started creating an analytical dataset course
* Learnt about types and sources of datasets

**Thoughts:** There are different types of datasets and sources

## Day 15 (09/02/2021) | Worked on project 1

Had to go to the hospital to see my Dad
* Finally started project 1
* Checked all numerical and categorical variables for a relationship with the avg_sale_amount column
* Started working on my workflow

**Thoughts:** Project one is progressing fine

## Day 16 (10/02/2021) | Practice project

* Completed the practice project
* Scored my model and got a bid recommendation of approximately $8,236,000 for 3000 diamonds

![](./images/)

*Practice project workflow*

**Thoughts:** Worked on practice project today

## Day 17 (11/02/2021) | Data types and sources

* Finished lesson 1 of the creating an analytical dataset course
* Learnt about the different data types and data sources

![]()

**Thoughts:** There are several data types and sources

## DAY 18 (12/02/2021) | Predicting catalog demand project

* Continued working on project 1
* Finished a workflow for project 1

**Thoughts:** Made progress with project 1

## Day 19 (13/02/2021) | Progress on practice project

* Created a working working workflow for the practice project
* Solved the question but my profit is still out of range so im going to revisit the formula i'm using

**Thoughts:** Making good progress on the practice project workflow

## Day 20 (14/02/2021) | One-third of the way completed milestone

* Celebrating completing a third of the challenge!!
* Finally figured out the correct formula for calculating profit. Lets move forward!!
* Happy Valentine's day

**Thoughts:** Feels good to have come this far

## Day 21 (15/02/2021) | Types of algorithms

* Read Chapter two of the book: Learn algorithms through problem solving
* Learnt about the diffent types of algorithms
  * Recursive algorithms: Called in themselves
  * Divide and conquer algorithms: Split problems into subproblems
  * Randomized Algorithms: Randomizes solving process
  * Exhaustive search: Most inefficient algorithms
  * Greedy algorithms: Make the best possible choice at the time

**Thoughs:** There are many kinds of algorithms

## Day 22 (16/02/2021) | Dirty Data

* Started lesson 2 of the creating an analytical dataset course
* Learnt about the properties of dirty data and dealing with missing data. Dirty data usually contains:
    * Not correctly parsed data
    * Extra Characters
    * Misspelled Entries
    * Duplicate records
    * Incorrect data
    * Unexpected Patterns
* Learnt reasons to deal with missing data which are:
    * Prevent model bias
    * some models don't work with missing data

**Thoughts:** Its best not to perform analysis with dirty data

## Day 23 (17/02/2021) | Dealing with missing data

* Finished Lesson 2 of the creating an analytical dataset course
* You can deal with missing data by either one of the following:
  * imputing the mean, median or mode
  * multiple imputation method 
  * full information maximum likelihood
  * Delete the rows or columns with missing data (least recommended)

**Thoughts:** There are several methods of dealing with missing data

## Day 24 (18/02/2021) | Missing data

* Started lesson 3 of the creating an analytical dataset course
* Learnt about how to impute missing data
* Learnt that we should consider missing data factors such as:
  * How much data is missing?
  * How the missing data is distributed?
  * Is the missing data significant?
  * Is the missing data categorical or numerical?

**Thoughts:** Missing data can affect data in many ways.

## DAY 25 (19/02/2021) | Outliers

* Started lesson 4 of the creating an analytical dataset course
* Learned about outliers and their effects on the dataset

**Thoughts:** Outliers can affect data

## Day 26 (20/02/2021) | Dealing with outliers

* Finished lesson 4 of the creating an analytical dataset course
* Learnt about dealing with outliers
* Learnt about performing analysis on spacial data with alteryx

**Thoughts:** Outliers may have good effects on data or not. Removing them is dependent on how much bias they introduce to the data and if they are true or not.

## Day 27 (21/02/2021) | Dealing with outliers (cont.d)

* Learned there are different ways of dealing with outliers
    * **Cross-tabbing:** taking data within a field and summarizing other data to the values within that field & create a matrix.
    * **Truncating:** changing outlier to the maximum or minimum possible value

**Thoughts:** There are ways of figuring out how best to handle data

## Day 28 (22/02/2021) | Time Series Forecasting

* Started studying Time series forecasting on udacity
* Learnt about forecast methods:
    * Average method
    * Moving average method
    * Naive method
    * Seasonal Naive method
    * Exponential Smoothing method
* Learnt about trends and trend cycles

**Thoughts:** There are many forecast methods


## Day 29 (23/02/2021) | ETS Models

* Continued studying Time series forecasting on udacity
* Learnt about ETS models
* ETS stands for Error, Trend and Seasonality
* There are four types of ETS models:   
  * Simple Exponential Smoothing Method: Useful for No Trend, No seasonality Scenarios
  * Holt's linear Trend (Aka Double Exponential Smoothing) method: Useful for Trend, No seasonality Scenarios
  * Exponential Trend Method: Useful for Trend, No seasonality Scenarios
  * Holt's-Winters Seasonal Method: Useful for Trend and Seasonality Scenarios

**Thoughts:** ETS models are a family of models used to solve time series problems.

## Day 30 (24/02/2021) | 50% Milestone

* Yay!! I'm at the half way point
* Took a quiz today made by @Asad.Udacity from the #quizzes channel

**Thoughts:** The quiz was a nice reminder of the course

![quiz-result](./images/quiz-result.png)

*Quiz Result*

## Day 31 (25/02/2021) | Working with my mentor
* Reviewed Lesson 3 of the course
* Working with my mentor @Giulio Baldessari to finish and understand lesson 5

**Thoughts:** I'm learning a lot from my mentor

## Day 32 (26/02/2021) | Reinforcement Learning

* Watched a lecture on Reinforcement Learning on YouTube
* Learned that reinforcement learning is the third branch of machine learning
* Learnt about policy making

**Thoughts:** Reinforcement Learning seems like a good area to explore

## Day 33 (27/02/2021) | ETS models

* Studied lesson 2 of the Time series forecasting course on Udacity
* Learnt about ETS models
* Learnt the effects of error trend and seasonality on time series data
* Learnt to make time series forecasts using ETS models on alteryx

**Thoughts:** ETS models can account for seasonality in time series data

## Day 34 (28/02/2021) | ARIMA models

* Studied lesson 3 of the Time series forecasting course on Udacity
    * Learnt about ARIMA and seasonal ARIMA models
    * Learnt abut the Auto Regressive, Integrated and the moving average properties of time series data
    * Learnt how to read ACF and PACF plots 
    * Learnt how to make a time series plot stationary (by differencing)
    * Learnt to make time series forecasts using ARIMA models on alteryx

**Thoughts:** ARIMA models account for seasonality better than ETS models

## Day 36 (01/03/2021) | Study Jam Quiz

* Took the study jam quiz @shereen bashar made for the study jam on saturday. Thank you for the quiz

**Thoughts:** The quiz helped me refresh my memory of the course's lessons

## Day 37 (02/03/2021) | Analyzing and Visualizing time-series forecasting results

* Learnt about residual plots
* Learnt about calculating and interpreting errors

**Thoughts:** Minimize errors for the most accurate results

## Day 38 (03/03/2021) | Web app project

* Started working on a personal web app project

**Thoughts:** Really excited to start working on this project

## Day 39 (04/03/2021) | Sick day

* Couldn't do much today because I fell ill

## Day 40 (05/03/2021) | Resource gathering

* Gathered resources for my web development project moviecritics
* Found some useful images

**Thoughts:** These should help spice up the website

## Day 41 (06/03/2021) | Work on celebrities page

* Worked on the celebrities page of my moviecritics app
  * Added a profile section layout

**Thoughts:** The profile gives details of the celebrity

## Day 42 (07/03/2021) | Changed style from inline css to file css

* Changed inline css of files in pages folder of moviecritics

**Thoughts:** Moving the styles to css files makes the code neater

## Day 43 (08/03/2021) | About us page of Moviecritics

* created an about us page for moviecritics

**Thoughts:** Its a simple page with placeholder text

## Day 44 (09/03/2021) | SQL Fundamentals

* Studied the fundamentals of SQL on Dataquest the SQL skill path
* Learnt about `SELECT` and `FROM` clauses

**Thoughts:** SQL is very useful for managing data

## Day 45 (10/03/2021) | SQL Intermediate

* Studied about functions and clauses in SQL queries on Dataquest.
* Learnt about:
  *  `CASE` statements
  *   `ORDER BY`
  *   `LIMITS`

**Thoughts:** Learnt a lot about querying SQL databases

## Day 46 (11/03/2021) | SQL ANALYSIS

* Studies the queries and methods used in making analysis in SQL
* Learnt how dynamic an SQL query can be

**Thoughts:** SQL queries are used to make analysis in SQL

## Day 47 (12/03/2021) | Data Analysis

* Learnt about the different forms of data analysis

**Thoughts:** SQL queries and Python scripts are tools used in data analysis

## Day 48 (13/03/2021) | Data Analysis (contd)

* Learnt more about the various data analysis processes

**Thoughts:** There are various data analysis processes

## Day 49 (14/03/2021) | Rest day

* Took the day off from the course to get some much needed rest

**Thoughts:** Rest helps a lot with improving productivity

## Day 50 (15/03/2021) | Report Writing

* Learnt the basics of report writing

**Thoughts:** Report Writing is essential to become a good analyst

## Day 51 (16/03/2021) | Report writing
* Worked on my report today

**Thoughts:** Making good progress on my report

## Day 52 (17/03/2021) | Blog reading on the Ray library in python

* Read a blog about python's [ray](https://towardsdatascience.com/10x-faster-parallel-python-without-python-multiprocessing-e5017c93cce1) library.
  * [Ray](https://towardsdatascience.com/10x-faster-parallel-python-without-python-multiprocessing-e5017c93cce1) is a parallel processing library.
  * It is reported to be 10x faster than the multiprocessing library which also serves the same purpose as [ray](https://towardsdatascience.com/10x-faster-parallel-python-without-python-multiprocessing-e5017c93cce1)
  * Learn more about Ray here: https://towardsdatascience.com/10x-faster-parallel-python-without-python-multiprocessing-e5017c93cce1

**Thoughts:** [Ray](https://towardsdatascience.com/10x-faster-parallel-python-without-python-multiprocessing-e5017c93cce1) seems like a very useful multiprocessing library. Its worth checking out and using on multiprocessing projects with large datasets.

## Day 53 (18/03/2021) | Read a blog on getting a data science job

* Skills required include:
  * Python
  * SQL
  * Statistics
  * Mathematics
  * Analytics

**Thoughts:** Data Science jobs are not so easy to get

## Day 54 (19/03/2021) | SEO improvement blog

**Thoughts:** To beat your competition in SEO you need to be alert

## Day 55 (20/03/2021)

## Day 56 (21/03/2021)

## Day 57 (22/03/2021)

## Day 58 (23/03/2021)

## Day 59 (24/03/2021)

## Day 60 (25/03/2021)

# Hooray!!!! 60 days of udacity challenge complete!
