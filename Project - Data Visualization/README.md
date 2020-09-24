![Bikeshare](https://user-images.githubusercontent.com/49973760/94122630-6b682100-fe70-11ea-915c-b7ba24cd3b6b.jpg)

# Communicate Data Findings for Bikeshare Data
In this project, I made use of Python to explore data related to bike share system for `Los Angeles`, California in the United States of America. Written code to import the data and answer interesting questions about it by computing descriptive statistics. Utilized Python’s data visualization tools to systematically explore a selected dataset for its properties and relationships between variables. Then, created a presentation that communicates the findings through jupyter notebooks slide deck..

## Standouts:

```Generated nearly 600 plots related to univariate, bivariate, multivariate and, complex dashboards through out the project.```

## Project overview:
Over the past decade, bicycle-sharing systems have been growing in number and popularity in cities across the world. Bicycle-sharing systems allow users to rent bicycles on a very short-term basis for a price. This allows people to borrow a bike from point A and return it at point B, though they can also return it to the same location if they'd like to just go for a ride. Regardless, each bike can serve several users per day.

Thanks to the rise in information technologies, it is easy for a user of the system to access a dock within the system to unlock or return bicycles. These technologies also provide a wealth of data that can be used to explore how these bike-sharing systems are used.

In this project, I made use of Python to explore data related to bike share systems, provided by  [Metro Bikeshare](https://bikeshare.metro.net/about/data/). This data set includes information about individual rides made in a bike-sharing system covering the greater Los Angeles area.

## Project overview:
This project is divided into two major parts. This first part, uses Python visualization libraries to systematically explore a selected dataset and conduct an exploratory data analysis on a dataset of choosing. Uses Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part is structured, going from simple univariate relationships up through multivariate relationships. This part of the project gives the opportunity to ask questions on the data and make our own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what we’re truly looking for. Every step is documented carefully, and thoroughly.

### `Act 1` Data Wrangling:
Scapre the raw data from the source. Perform data wrangling by identifying missing data, handle NULL values, cleaning data, structure the data, perform feature extraction and finally save the cleaned dataset in the form of `relational database`.

### `Act 2` Exploratory Data Analysis:
Explore the data and document the findings as a report. The report should briefly introduce the dataset, then systematically walk through the points of exploration conducted. The headers and text should organize the thoughts and findings. Visualizations in this part of the project need not be completely polished: this is just exploration at this point. However, should still adhere to principles of using appropriate plot types and encodings so that accurate conclusions can be drawn. Enough comments and labeling should refelct the work, and help quickly grasp the analysis steps.

### `Act 3` Explanatory Data Analysis:
In this part, the main findings from the exploration are conveyed to others through an explanatory analysis. This part of the project made heavy use of the Act 2 of the project. Answered major queries in the exploration, with relevant visualizations along that path, and then polished them to construct a story for the readers to understand what I have found.

### `Act 4` Slide Deck:
To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. Leveraged the IPython's Jupyter Notebooks slide deck feature coupled with `NbConvertAPP` to create smooth slide show that clearly reflects the insights discovered.

## The Datasets:
Data scource: [Metro Bikeshare](https://bikeshare.metro.net/about/data/)

This data set includes information about individual rides made in a bike-sharing system covering the Los Angeles area.

Each trip is anonymized and includes:
+ **trip_id:** Locally unique integer that identifies the trip
+ **duration:** Length of trip in minutes
+ **start_time:** The date/time when the trip began, presented in ISO 8601 format in local time
+ **end_time:** The date/time when the trip ended, presented in ISO 8601 format in local time
+ **start_station:** The station ID where the trip originated (for station name and more information on each station see the Station Table)
+ **start_lat:** The latitude of the station where the trip originated
+ **start_lon:** The longitude of the station where the trip originated
+ **end_station:** The station ID where the trip terminated (for station name and + more information on each station see the Station Table)
+ **end_lat:** The latitude of the station where the trip terminated
+ **end_lon:** The longitude of the station where the trip terminated
+ **bike_id:** Locally unique integer that identifies the bike
+ **plan_duration:** The number of days that the plan the passholder is using entitles them to ride; 0 is used for a single ride plan (Walk-up)
+ **trip_route_category:** "Round Trip" for trips starting and ending at the same station or "One Way" for all other trips
+ **passholder_type:** The name of the passholder's plan
+ **bike_type:** The kind of bike used on the trip, including standard pedal-powered bikes, electric assist bikes, or smart bikes.


## Technologies Used:
+ **Python**
    > Used Python programming language to explore data related to bikeshare.

+ **Seaborn and Matplotlib**
    > Used to visualize the plots and customize them to improvize the plot aesthetics.

+ **Numpy and Pandas**
    > Used to explore and manipulate DataFrames and performed statistical analysis.

+ **Jupyter Notebooks**
    > Used through out the project as a python execution ground.

+ **Visual Studio Code**
    > Used to make exploratory analysis and write appropriate SQL queries to answer the posed questions.

+ **Git Version Control**
    > Used to control and record the project files. Shared the work on GitHub profile.


### Project Rubric

This project fulfilled all the requirements mentioned in the rubric below.

#### **Code Quality**

| CRITERIA | MEETS SPECIFICATIONS |
| ------ | ------ |
| Functionality of code | All code is functional (i.e. no errors are thrown by the code). Warnings are okay, as long as they are not a result of poor coding practices. |
| Does the project follow good coding practices? | The project uses functions and loops where possible to reduce repetitive code. Comments and docstrings are used as needed to document code functionality. |
| Use of packages | Packages are used to carry out advanced tasks. |
| Use of functions | Functions are used to reduce repetitive code. |
| Use of good coding practices | Docstrings, comments, and variable names enable readability of the code. |

#### **Exploratory Data Analysis**

| CRITERIA | MEETS SPECIFICATIONS |
| ------ | ------ |
| Is the data explored systematically? | The project appropriately uses univariate, bivariate, and multivariate plots to explore many relationships in the data set. Reasoning is used to justify the flow of the exploration. |
| Are questions and observations documented in the report? | Questions and observations are placed regularly throughout the report, after each plot or set of related plots. |
| Is the data visualized using appropriate plot types, encodings, and parameter choices? | Visualizations made in the project depict the data in an appropriate manner that allows plots to be readily interpreted. This includes choice of appropriate plot type, data encodings, transformations, and labels as needed. |


#### **Explanatory Data Analysis**

| CRITERIA | MEETS SPECIFICATIONS |
| ------ | ------ |
| Have the main findings from the exploration been documented? | A section in the submitted materials includes a summary of main findings that reflects on the steps taken during the data exploration. The section also describes the key insights that are conveyed by the explanatory presentation. |
| Does the presentation clearly convey key insights? | A slideshow is provided, with at least three visualizations used in the presentation to convey key insights. These key insights match those documented in the summary. Each visualization is associated with comments that accurately depict their purpose. |
| Are the plots polished? | All plots in the presentation have an appropriate title with labeled axes and legends. Labels include units as needed. Plot type, encodings, and transformations are all appropriate. |


#### **Things that Made the Project Stand Out!**

| Submission Phase, Reviewer Tips | 
| ------------ |
| During the exploration, used a variety of plot types to explore different relationships in the dataset. Rigorously explored the dataset to investigate unexpected relationships and open to hit a dead-end in the exploration. | |
| As part of my exploration, documented my thought processes to justify the steps U took. |  |
| When key insights are selected for the explanatory presentation, focussed on one or two paths that tell a compelling story. |  |
| When planning the explanation’s flow, documented the design decisions that make the visualizations information-rich but still easy to read. |  |
| Gathered feedback from others to get a different perspective on my explanatory presentation. |  |


## Software requirements:
To complete this project, the following software requirements apply:
- [x] You should have Python 3, NumPy, pandas, matplotlib and, Seaborn installed using Anaconda
- [x] IPython's Jupyter Notebooks to access notebook files.
- [x] nbconvert, a tool that can export notebooks in an HTML slides format.
- [x] A terminal application (Terminal on Mac and Linux or Cygwin on Windows).


## Acknowledgement:
Thanks to the [Udacity](https://www.udacity.com/) platform for providing the [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) program.

| Name | Designation|
| :------ | :------ |
| Sebastian Thrun | : `INSTRUCTOR` |
| `About` | As the founder and president of Udacity, Sebastian’s mission is to democratize education. He is also the founder of Google X, where he led projects including the Self-Driving Car, Google Glass, and more. |
| Derek Steer | : `CEO AT MODE` |
| `About` | Derek is the CEO of Mode Analytics. He developed an analytical foundation at Facebook and Yammer and is passionate about sharing it with future analysts. He authored SQL School and is a mentor at Insight Data Science. |
| Mike Yi | : `INSTRUCTOR` |
| `About` | Mike is a content developer with a multidisciplinary academic background, including math, statistics, physics, and psychology. Previously, he worked on Udacity's Data Analyst Nanodegree program as a support lead. |
| Josh Bernhard | : `DATA SCIENTIST` |
| `About` | Josh has been sharing his passion for data for nearly a decade at all levels of university, and as Lead Data Science Instructor at Galvanize. He's used data science for work ranging from cancer research to process automation. |
| David Venturi | : `INSTRUCTOR` |
| `About` | Formerly a chemical engineer and data analyst, David created a personalized data science master's program using online resources. He has studied hundreds of online courses and is excited to bring the best to Udacity students. |
| Sam Nelson | : `PRODUCT LEAD` |
| `About` | Sam Nelson is the Product Lead for Udacity’s Data Analyst, Business Analyst, and Data Foundations programs. He’s worked as an analytics consultant on projects in several industries, and is passionate about helping others improve their data skills. |
| Juno Lee | : `CURRICULUM LEAD` |
| `About` | Juno is the curriculum lead for the School of Data Science. She has been sharing her passion for data and teaching, building several courses at Udacity. As a data scientist, she built recommendation engines, computer vision and NLP models, and tools to analyze user behavior. |
| Mat leonard | : `CURRICULUM LEAD` |
| `About` | Mat, the curriculum lead is a former physicist, neuroscientist, and data scientist with a passion for education. Recently, he led the Deep learning Nanodegree foundation program covering state-of-the-art machine learning models. |


### Contact:
**`Vamshi Krishna Prime: Data Analyst`**
```
+ Email : vamshi.krishna.prime@gmail.com
+ website: https://www.vamshi-krishna.com
+ GitHub : https://github.com/vamshi-krishna-prime
+ LinkedIn : https://www.linkedin.com/in/vamshi-krishna-prime
```