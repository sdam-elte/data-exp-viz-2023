# Course material for Data Exploration and Visualisation 
### 2023 spring semester

This course is part of the [Scientific Data Analytics and Modelling Programme](https://datascience.elte.hu/en/Default.aspx#top).
The aim of the course is that students gain practical skills in **accessing large databases/datasets**, handling **data stored in different formats**, **exploring/cleaning these data** and **presenting** the gathered information. During the course students will come across databases used in various scientific fields. Completing of the several projects allows students to gain useful experiences that will give a firm foundation for later courses on theoretical datamining and advanced computing laboratories.
In this course we intend to introduce **state of the art tools and methods** for data exploration and visualization. A library in a given programming language that we use today might become obsolete in a year or become the standard for a longer time. This field evolves rapidly and therefore the emphasis is not on the exact tool for solving a task, but the notions and algorithms. 

There is a useful tutorial into python and some data transformation/analysis methods http://bokae.web.elte.hu/numerical_methods.html), which gives a wide background knowledge, that comes handy. Also for those who prefer the language R there are several tutorials.

During the course every sample code will be shown in **jupyter notebooks**, which can be accessed on the [K8plex Edu platform](https://k8plex-edu.elte.hu) and in this Github repository.

The course is held in the **North Building** in computer lab **5.56** every **Tuesday between 2PM-4PM**.
  
#### Course info
Neptun code: 	**dsexplorf20vm** <br>
Instructor: 	**[Dávid Visontai](http://benedek.web.elte.hu/)**<br>
Semester: 	spring <br>
Type: 	Lecture + Practice <br>
Credit points: 	6 <br>
Requisites: 	programming in either **python**, **R**<br>

Each occasion starts with approximately a twenty minute of introduction into the current topic. After that everyone can work on the assignments and the consultants will be available to help with the any related problems and questions. For those who lack experience in either programming or data analisys it is highly recommended to attenda the lecture and practice sessions. There are many tricks and tips that can be learned much quicker from personal discussions.

### The schedule of the course 
1,  07.03.2023. **[Introduction to K8plex Edu](https://k8plex-edu.elte.hu/hub)**, **[Jupyter Notebooks](https://jupyter.org/)**, **Requirements for the course**,
                **[Timeseries analysis](Lectures/L-Timeseries/02-Timeseries.pdf)** and **[USGS water discharge statistics](Assignments/A-Timeseries)**<br>
2,  14.03.2023. **[Maps, shapes, coordinates](Lectures/L-Shapes-Maps-Coordinates)** <br>
3,  21.03.2023. **[Interactive Visualization](Lectures/L-Interactive_Visualization)** <br>
4,  28.03.2023. **[REST services](Lectures/L-HTTP-REST-API)**  <br>
5,  04.04.2023. **[SQL queries](Lectures/L-SQL)** <br>
6,  11.04.2023. **Consultation** <br>
7,  18.04.2023. **[Natural Language Processing on tweets](Lectures/L-NLP)** <br>
8,  25.04.2023. **[Working with large datasets](Lectures/L-LargeData)** <br>
9,  02.05.2023. **[Image exploration](Lectures/L-Image_Exploration)** <br>
10, 09.05.2023. **[Network exploration](Lectures/L-Networks)** <br>
11, 16.05.2023. **[Datacleaning, and Filtering, Reproducibility](Lectures/L-Datacleaning-reproducibility)**<br>
12, 23.05.2023. **[NoSQL - Elasticsearch and Kibana, GraphQL](Lectures/L-NoSQL-ES)** <br>
 
<!-- **[NoSQL - Elasticsearch and Kibana, GraphQL](Lectures/L-NoSQL-ES)** -->

### Covered topics

 * Datatypes, images, timeseries, tables, graphs, textual data
 * Standards of file- and dataformats ([csv](https://www.computerhope.com/issues/ch001356.htm), [hdf5](https://en.wikipedia.org/wiki/Hierarchical_Data_Format), [netcdf](https://en.wikipedia.org/wiki/NetCDF))
 * Raw and processed data, metadata, cleansing of data
 * Access data locally and through the web ([API](https://restfulapi.net/)s, [HTTP protocol](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol))
 * Access of scientific databases, Usage of relational databases ([SQL](https://www.w3schools.com/sql/))
 * Transforming data, sorting, combining [pandas](https://pandas.pydata.org/)
 * Basics of timeseries analysis
 * Handling datasets with geolocation ([shapely](https://shapely.readthedocs.io/en/stable/manual.html), [folium](https://python-visualization.github.io/folium/), [geoviews](https://geoviews.org/))
 * Basics of image processing ([opencv](https://opencv.org/))
 * Dimension reduction, clustering
 * Processing textual data, logs ([natural language processing](https://www.nltk.org/))
 * Infographics, visualisation (html, css, javascript libraries)
 * Interactive dataexplorative tools ([ipywidgets](https://ipywidgets.readthedocs.io/), [bokeh](https://bokeh.org/), [holoviews](http://holoviews.org/))
 * Developing open source softwares, reproducible research ([OSF](https://osf.io/))

### Assignments, the expected output and the name of the corrector

1. **[Following John Snow](Assignments/A-Shapes-Maps-Coordinates)**- HTML - Dávid Visontai
2. **[USGS water discharge statistics](Assignments/A-Timeseries)** - HTML - Dávid Visontai
3.
   * **a)** **[SQL queries on an NBA database](Assignments/A-SQL-A-Basketball)** NBA 2008-2009 season - HTML - Dávid Visontai
   * **b)** **[SQL queries to a Biological database](Assignments/A-SQL-B-Coveo)** Analysis of SARS-COV-2 mutation database - HTML - Dávid Visontai
  
4. **[Interactive Visualization](Assignments/A-InteractiveVisualizations)** ATLO.info reproduction - HTML or Hosted App - Csaba Kiss
5. **[REST API](Assignments/A-HTTP-REST-API)** - (REST service/API) A notebook or a python script - Dávid Visontai
6. **[Network exploration](Assignments/A-Networks)** - HTML - Csaba Kiss
7. **[Data extraction from images](Assignments/A-Image_Exploration)** - HTML - József Stéger
8. **[Natural Language Processing on tweets](Assignments/A-NLP)**  HTML - !!! Ex 7. and 8. is optional. - Dávid Visontai

All assigments should be converted into HTML unless it is stated otherwise!

The submitted results should look like a **report**, which can be generated from the notebooks. This will be explained on the [lecture](1-createreport). All figures should have *labels*, *title*, each exercise should end with a descriptive *conclusion* and explanatory comments should be inserted into the code. These are **must have features** of a work that is intended for presentation.

<span id="deadline"></span>
### (Final) Submission deadline
The assignments/projects will be released in the first couple of weeks, which you have to submit after the end of the course **23th June 1PM (this is the last deadline)**. Each submitted assignment will be corrected and a feedback will be given. After that you may resubmit your assignment **once more** but before the final deadline.

### Where to work on the assignments?
https://k8plex-edu.elte.hu/hub is where the notebooks will be handed out. It is available for all students with a valid **Neptun** or **caesar** account. Once you launch your environment you will find a folder with the course material. The notebooks will be available in this Github repository as well.
We will explain how to use the portal on the first lecture.
In case there is any problem with the portal you can run a notebook server locally on any other computer and upload your work later.

### Grading

Each assignment will be corrected after submission and a maximum of **20 points** will be given for it. **10** for all the **completed tasks**, **10** for the **quality** of the submitted report (look, clarity and comments). 
The final grades will be given according to the following point system:<br>
0 - 50: failed<br>
51 - 70: 2<br>
71 - 94: 3<br>
95 - 115: 4<br>
116 - : 5<br>

### Folder structure of the working environment

* Assignments will be visible in `/v/courses/dataesp2023.assignments`
* Example Datasets will be in the `/v/courses/dataesp2023.public/Datasets` directory you will find datasets, that you can work with.
* Other lecture materials will be in `/v/courses/dataesp2023.public/<lecture_name>` and on this github page

### Learning materials
* Python tutorial: http://bokae.web.elte.hu/numerical_methods.html (translated from the BSc course "numerical methods in physics I" by Eszter Bokányi, work in progress )
* SQL tutorial: https://www.w3schools.com/sql/ 
* RESTful service: https://en.wikipedia.org/wiki/Representational_state_transfer
* Networkx: https://networkx.github.io/

#### Recommended readings

* Wes McKinney: Python for Data Analysis, (O’Reilly 2013)
* Joel Grus: Data Science from Scratch (O’Reilly 2015)

### Simulation and data visualizations
* https://www.washingtonpost.com/graphics/2020/world/corona-simulator/

## List of tutors
* Ágnes Becsei
* Krisztián Papp
* József Stéger
* Dávid Visontai

