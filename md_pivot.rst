***************************************************
Multidimensional data exploration and visualization
***************************************************

Pivot Tables are an extraordinarily useful and powerful way of exploring business data, especially when we have data consisting of both measures (e.g. sales volume, delivery time, speed to answer in a call center) and dimensions (e.g. time, region, customer, supplier, product). Our BA textbook provides a brief introduction to Pivot Tables in Section 17.2. However, I'm going to provide a much more comprehensive and advanced tutorial on this topic. You can feel free to go as deeply into this as you'd like but I think that mastering pivot tables and pivot type analysis in general is a critical business analytics skill.

Pivot tables are based on a way of structuring data called multi-dimensional (MD) data modeling. For those of you with some database background, this MD approach differed in some profound ways from the entity relational (ER) database model. The MD approach grew out of the data warehousing movement, which in turn, grew out of the desire to analyze the wealth of data in transaction processing systems (using something gentler than high level programming languages for even SQL - Structured Query Language). Now, I know that many of you do not have much background in relational databases, SQL and data warehousing. However, some of you do.

So, what I do in my class is introduce a bit on MD modeling and then do a hands-on tutorial on pivot tables. That leads us to an exciting new tool called Tableau which takes pivoting to a whole new level. If during the screencasts on MD modeling and the pivot table tutorial, I make reference to previous screencasts on data warehousing, ER modeling or SQL, just ignore them if you wish. However, at the bottom of this lesson, I've included a set of screencasts that do cover the basic of relational databases, SQL and data warehousing for those who are interested. They aren't needed for doing basic pivot analysis but I think that anyone desiring to be a business analytics focused pro must have a solid understanding of these database topics.

If you are interested, I've also included a bunch of **optional** material on basic relational database concepts and basic data querying with MS Access. Effective use of databases and knowledge of queries (including SQL) has been identified as a key skill needed by data analytics professionals. Included are some data warehousing 101 items - why data warehouses, how are data warehouses structured and how data warehouses fit into the business analytics food chain. I know that some of you (especially the MSITM students) have had course that covers databases, SQL, and data warehousing, but many of you have not. So, if you want to learn, dive in.

Readings
========

* Business Analytics: Section 3.5 - Pivot tables
* Business Analytics: Chapter 4 - BI Tools for Data Analysis (7ed) (or Section 17.2 - Data Exploration and Visualization (5/6ed))
* `Is BI dead? <https://benn.substack.com/p/is-bi-dead>`_
* `Data's horizontal pivot <https://benn.substack.com/p/datas-horizontal-pivot>`_

After learning VBA, Chapter 15 - Working with Pivot Tables and Tables, in our VBA for Modelers text shows how you can programmatically create and manipulate Pivot Tables.

Downloads
=========

* `Downloads-DataWarehousingPivot.zip <https://drive.google.com/file/d/1aLPfoC6348XBRpyNz9wGNnPOn6OWQlQc/view?usp=sharing>`_


Screencasts and other activities
================================

We'll start with an intro to some data warehousing and multidimensional data modeling concepts.

* `SCREENCAST: Intro to Excel Tables <https://youtu.be/h9wI9Z-hQRI>`_ (13:37)
* `SCREENCAST: Intro to basic data warehousing concepts <https://youtu.be/xcX4AAaclUk>`_ (8:37)
* `SCREENCAST: Intro to multi-dimensional data modeling concepts <https://youtu.be/ATxqBhuGdGc>`_ (8:42)

Within the Downloads folder you'll find the tutorial, CallCenterPivot.docx, that 
is associated with the following screencast. It will be an intro to basic and
intermediate Pivot Table use.

* `SCREENCAST: Call Center Pivot Tutorial <https://youtu.be/O9pzqM191lo>`_ (36:11)

In the next two sections, I give an overview of Tableau and Excel's newish
Power Pivot tool. Microsoft has also gone directly at Tableau with its
Power BI Desktop tool (also discussed below). It is well worth your time
to become familiar with these tools as they are changing the way people
do "pivoting" style analysis. They are relatively simple to learn but
have a ton of power under the hood. Power Pivot and Get & Transform start
to blur the lines between databases, data prep tools and data visualization
tools.

Introduction to Tableau
-----------------------

I mentioned that we were going to be using a relatively new piece of software called `Tableau <http://www.tableausoftware.com/>`_. It takes pivot tables to a whole new level. While the software is installed in our lab, we also have an agreement with Tableau that allows you to download and install Tableau on your own computer. It is super cool stuff. See the link in the Textbook and Software section on the main page of our Moodle site.

I've create a short getting started screencast and there are numerous other resources listed below.

* `SCREENCAST: Introduction to Tableau <https://youtu.be/ImQctMqWwNQ>`_ (22:24)

More resources:

* A collection of Tableau tutorials is available in the Downloads\Tableau folder. They have names that start "Tutorial 1", "Tutorial 2", and "Tutorial 3". The first covers the basics while the second and third cover more advanced topics including calculated measures and dimensions as well as using Tableau's mapping features (ala GIS type analyses).
* As an alternative to downloading Tableau, you can learn it by using `Tableau Public <http://www.tableausoftware.com/public/>`_ - a hosted version.
* `Tutorial: Getting Started with Tableau Desktop <https://help.tableau.com/current/guides/get-started-tutorial/en-us/get-started-tutorial-home.htm>`_ - good place to start learning Tableau
* `Tableau Student Resource Center <https://community.tableau.com/s/students>`_
* `Tableau Desktop Starter Kit <http://www.tableau.com/learn/starter-kit>`_ - a guide with tutorials and videos to get you going in Tableau
* Here's a bunch of `"whitepapers" from Tableau <http://www.tableausoftware.com/learn/whitepapers>`_

Perhaps you'll find Tableau useful for the data visualization assignment or some aspect of your final project. 

Introduction to Microsoft Power Pivot and Power BI Desktop
-----------------------------------------------------------

Since Excel 2010, Microsoft has been adding more powerful data acquisition, cleaning, data modeling and analysis tools to its familiar spreadsheet. 

Power Pivot and Get & Transform
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`Power Pivot (formerly PowerPivot) <https://support.office.com/en-us/article/power-pivot-powerful-data-analysis-and-data-modeling-in-excel-a9c2c6e2-cc49-4976-a7d7-40896795d045>`_ is a relatively new addition to the Pivot Table ecosystem. It's available as a free add-in to Excel 2010 and in 2013 was integrated into Excel as a COM add-in. In Excel 2016 it became available through the Data tab and was fully integrated into Excel. Essentially, it helps Excel analysts to:

* create a "multidimensional data model" by linking to and/or importing multiple data sources
* provides autodetect features for building relationships (joins) between these data sources
* build Pivot Tables on top of this new "data model"
* enhance your Pivot Tables with Slicers (a new to 2010 feature adding visual filtering to Pivot Tables)
* publish results as nice looking dashboards either within Excel or via Sharepoint

Check out the link above for some good introductory videos and general information. In addition, Power Pivot is covered in Section 17-2 of our Business Analytics textbook. If you'd like to explore Power Pivot in more detail, consider taking it on as your class project. For example, you could create a set of materials to help people learn to use Power Pivot (nothing like creating teaching materials to force you to really learn something).

There are some strange shortcomings of PowerPivot in that it makes certain Pivot Table functionality, specifically Grouping, unusable if the Pivot Table is based on what is known an *OLAP-based data source*. This `Contextures blog post <https://contexturesblog.com/archives/2018/01/18/problem-grouping-pivot-table-items/>`_ does a nice job of explaining the issue and a workaround. 

I decided to create a quick intro to Power Pivot based on some bike share data from Seattle. It covers the basics of:

* using Get & Transform to import several data tables - station, trip, and weather
* adding those tables to the Data Model
* building a relationship between the station and trip table
* adding a second copy of the station table to handle need for multiple joins between station and trip
* computing a trip date field in the trip table using DAX formula
* joining trip to the weather table using trip date
* specifying that the weather table will serve as the "date table"
* creating a Pivot Table in Excel to count trips out of each station over time
* computing a station group field for both copies of the station table
* creating a Pivot Table to compute average trip duration for trips between all the station groups

Obviously, there's so much more that could be done including analyzing how weather impacts
ride volume and ride length. Also, since latitude and longitude are in the station tables, you
could use the Power Map capability to generate, for example, maps with bubbles whose size is
proportional to ride volume.

* `SCREENCAST: Getting started with Power Pivot using bike share data <https://youtu.be/XTp9hR5Y2Uo>`_ (23:32)

The Get & Transform tool (also available in Excel's Data tab) used to be called PowerQuery. We saw this
tool earlier in the course when we used it for getting data into Excel from text files and for
doing data reshaping (the unpivoting example).

Here is link to a `nice set of videos and other learning resources for Get & Transform and Power Pivot <https://support.microsoft.com/en-us/office/get-transform-and-power-pivot-in-excel-42d895c2-d1d7-41d0-88da-d1ed7ecc102d>`_.

Power BI Desktop
^^^^^^^^^^^^^^^^

And even more recently, MS released a free version of Power BI Desktop that is Tableau-ish. Here's a link to a whole set of learning materials for this tool.

* https://powerbi.microsoft.com/en-us/guided-learning/

A nice `article summarizing the direction of Excel and its companion Power BI offerings <http://www.cio.com/article/2979725/enterprise-software/why-power-bi-is-the-future-of-excel.html>`_ appeared in CIO magazine back in Sept of 2015.

With respect to R and MS's acquisition of Revolution Analytics a few years ago, it's not clear how this is going to play out.

Overview of relational databases, SQL, data warehousing (OPTIONAL)
------------------------------------------------------------------

For those of you interested in getting a basic understanding of relational databases, SQL and data warehousing, here is a set of screencasts I did as well as some additional resources. BTW, knowledge of relational databases, SQL and data warehousing is pretty important for any business analytics person.

Chapter 14 - Importing Data into Excel from a Database, in our VBA for Modelers text, has a very nice introduction to relational database concepts.

`Databases are Rocks, Spreadsheets are Water <http://www.juiceanalytics.com/writing/databases-are-rocks-spreadsheets-are-water/>`_ - this is my favorite essay on the relationship between databases and spreadsheets.


Screencasts and Downloads
^^^^^^^^^^^^^^^^^^^^^^^^^
	
* Screencast - `The Excel Database "D" Functions <https://youtu.be/EiLF8ZT0rbA>`_
* Screencast - `Relational DBs: Tables, Records, Fields <https://youtu.be/K70j9lq8Zwc>`_
* Screencast - `Relational DBs: Keys and Relationships <https://youtu.be/WB9TeMhVo68>`_
* Screencast - `Relational DBs: Intro to SQL <https://youtu.be/TqnQ4jERbvY>`_
* Screencast - `Relational DBs: SQL Aggregate Queries for Analysis <https://youtu.be/7shc1foHlDI>`_


`Downloads-RelationalDBsSQLandADO.zip <https://drive.google.com/file/d/1XFvU81z9wJLu5ZKYXhKSTIqbgtdERGL0/view?usp=sharing>`_

Here is a series of screencasts by David Langer covering everything from the basics up to more advanced topics with a focus on the things that are useful for business analytics.

* `Introduction to SQL Programming for Excel Users <https://www.youtube.com/playlist?list=PLTJTBoU5HOCSrExoOVTjDG33lFpDvmz2w>`_

Explore (OPTIONAL)
==================

Data analytics at Kellogg's
------------------------------------------------------------

A few years ago, I attended a terrific talk by Nolen Akerman of Kellogg's describing their journey to analytics. He's shared a few links that we can share with students including some Tableau Public visualizations he's done as well as a YouTube video of their "immersive analytics room". Very cool.

* `Public Tableau visualizations <https://public.tableau.com/profile/nolen.akerman#!/>`_
* `Immersive room video <https://www.youtube.com/watch?v=XM6lOyRYYHI>`_

Open source alternatives to Tableau / Power BI
----------------------------------------------

* `Lyra: An interactive visualization design environment <http://idl.cs.washington.edu/projects/lyra/>`_
* Learn R or Python and use tools like `ggplot2 <https://ggplot2.tidyverse.org/>`_, `shiny <https://shiny.rstudio.com/>`_, `plotly <https://plotly.com/>`_, `matplotlib <https://matplotlib.org/>`_, `seaborn <https://seaborn.pydata.org/>`_, `holoviz <https://holoviz.org/>`_, `altair <https://www.altair.com/data-analytics/>`_, or `streamlit <https://streamlit.io/>`_.







