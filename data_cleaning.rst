***********************************
Data cleaning
***********************************

Rarely is data all clean and ready for analysis. Enormous amounts of
time are spent on a myriad of data cleaning and preparation tasks such as:

* extracting data elements from text files using string functions,
* getting data into a specific format required by some analysis tool,
* creating new fields or variables,
* dealing with missing or incorrect data,
* ... and many more tasks required to get data ready for modeling and analysis.

Intro and Objectives
====================

In completing the activities in this module you will:

* learn about common data cleaning challenges,
* use advanced Excel techniques to clean up a set of text files,
* start to gain an appreciation for the value of developing text cleaning skills.
* get a first glimpse into the complex and powerful world of regular expressions

Readings
=========

Most of the readings are things I created or web based resources (links throughout in appropriate places). However, the 7th edition of our BA textbook does include a new section 4.5 - Data Cleansing that is worth looking at.

Downloads
=========

* `Downloads-MuddyData.zip <https://drive.google.com/file/d/15ezGNjOwuUiXx1SQCEJPlZVE_jXoqJID/view?usp=sharing>`_


Screencasts and other activities
================================

Evil Excel Error
----------------

I'd like to start by sharing a horrifying example from the bioinformatics industry of how importing data in Excel can lead to incorrect results.

* `SCREENCAST: Excel and bioinformatics <https://youtu.be/9RzlDrAl1SI>`_ (5:35)

`Mistaken Identifiers: Excel and Bioinformatics <https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-5-80>`_

You can find the data file, named **hgnc_downloads.txt** in the Downloads file for this module. There's also an `eSupplement <http://www.webcitation.org/query.php?url=http://discover.nci.nih.gov/symbolmutation&refdoi=10.1186/1471-2105-5-80>`_ to the article. Frightening.

**Postscript:** In August, 2020, the `scientists gave up and renamed the genes <https://www.theverge.com/2020/8/6/21355674/human-genes-rename-microsoft-excel-misreading-dates>`_!

**Postscript Postscript:** In August, 2021, `this problem is still an issue and in this article the authors ends with call for using Python and R instead of Excel <https://theconversation.com/excel-autocorrect-errors-still-plague-genetic-research-raising-concerns-over-scientific-rigour-166554>`_.

Muddy Data Tutorial
-------------------

I realized early on that "data wrangling" or dealing with messy data was something not taught in textbooks or classes. It was learned, painfully, on the job. So, many years ago I created this tutorial to try to teach a few concepts for getting messy data into spreadsheets.  

Now, of course, everyone talks about data cleaning all the time. 

    "80% of your time in data science projects is spent on data cleaning and the other 20% is spent on complaining about data cleaning". [someone, somewhere]

You can find the zip file containing the tutorial document (**MuddyDataTutorial.docx**) as well as supporting data files above in the Downloads. 

Here is a screencast to help you get started on the tutorial. Just work your
way through it and learn to embrace data cleaning. :)

* `SCREENCAST: The Muddy Data Tutorial - Getting Started <https://youtu.be/9We5vKaMreI>`_ (21:11)

Text files, text editors and a regex preview (OPTIONAL)
-------------------------------------------------------

Text files are the "common currency" of data exchange. You need
to get good at manipulating text files.

* `SCREENCAST: Text files and text editors <https://youtu.be/RCpCKIKIBuo>`_ (12:25)

Regular expressions (regex) are magical, extremely powerful and simply must be a part of your analytics toolbox for data wrangling. In this class, we just touch
on the basics and I go into more depth in MIS 4470/5470 - Practical Computing
for Data Analytics.

Let's start with a few basic concepts.

* `SCREENCAST: Getting started with regular expressions <https://youtu.be/rsLPAkIL_VM>`_ (16:55)

A great basic interactive tutorial is available at http://regexone.com/. We'll work through a few of the lessons in the screencast above.

My favorite interactive website for exploring and learning regex is http://regexr.com/.

Three more really good sites for learning regular expressions:

* http://www.regular-expressions.info/
* http://gnosis.cx/publish/programming/regular_expressions.html
* http://www.rexegg.com/

Another good resource is the following blog post on regex. It also contains links to sites containing the "bare bones" regex that EVERY analyst should know.

* http://www.codinghorror.com/blog/2008/06/regular-expressions-now-you-have-two-problems.html

Explore (OPTIONAL)
==================

Tableau releases new data prep tool
-----------------------------------

`Tableau expanding to more pieces of the data analysis workflow <https://www.tableau.com/products/prep>`_ pipeline with a focus on simplicity for end user (read "no programming"). Interesting quote from the `press release <https://www.tableau.com/about/press-releases/2018/tableau-expands-platform-new-product-tableau-prep>`_ :

“Tableau Prep will do for data preparation what Tableau did for analytics and Business Intelligence. It will take an otherwise painstaking and difficult task, and make it easy, visual, and direct, empowering more people to get to analysis faster,” said Francois Ajenstat, Chief Product Officer at Tableau. “Our customers often tell us that they love working with Tableau, but struggle when data is in the wrong shape for analysis. We believe data prep and data analysis are two sides of the same coin that should be deeply integrated and look forward to bringing fun, easy data prep to everyone regardless of technical skill set.” 

Data cleaning matters
---------------------

Below you'll find a link to OpenRefine.org. This was a project initiated by Google (and called Google Refine) that they decided to stop development on and just release the code base to the open source community. It's a web based tool for dealing with messy data and doing various data wrangling tasks. It's got some nice videos to give you a sense of what it does. Very cool.

* `OpenRefine.org <http://openrefine.org/>`_ - This was a Google project (based on a technology they acquired) and then Google let it go to the open source community.
* `Wrangler <http://vis.stanford.edu/wrangler/>`_ - This tool came out of Stanford's Data Visualization Lab
* `For Big-Data Scientists, ‘Janitor Work’ Is Key Hurdle to Insights <https://www.nytimes.com/2014/08/18/technology/for-big-data-scientists-hurdle-to-insights-is-janitor-work.html>`_
* Several years ago I wrote a `journal paper about the Muddy Data Tutorial and this class in general <https://pubsonline.informs.org/doi/pdf/10.1287/ited.3.3.23>`_ - check it out if you are interested.

Heroics and fun with data cleaning
----------------------------------

I'll close this module with some favorite regex comics from xkcd. Remember to hover over the comic to see the mouseover message...

* `Regex xkcd 1 - regular expressions (elaborate scenarios) <http://xkcd.com/208/>`_
* `Regex xkcd 2 - s/keyboard/leopard/ <http://xkcd.com/1031/>`_
