***********************************
Excel application development
***********************************

Now it's time to start to put your new found Excel VBA skills to work in creating analytical, spreadsheet based applications.
 
Intro and Objectives
====================

In this module you'll learn about:

* VBA topics such as arrays, more control logic structures and advanced use of the MsgBox
* principles for designing and developing spreadsheet based applications
* creating VBA driven user forms for user interfaces that go beyond just the worksheet grid

While VBA is very powerful, we'll also see that you can do pretty neat things with no VBA (but that look like VBA must have been needed).

Readings
========

In this session we'll be mostly drawing on material from Chapters 7-12 in VBA for Modelers.

Downloads
=========

* `Downloads-Module-AppDevBasics.zip <https://drive.google.com/file/d/1OuDJI-8zPwXDrGDq3YHxnDqFtISHQg1r/view?usp=sharing>`_
* `Downloads-Module-UserForms.zip <https://drive.google.com/file/d/16mtAXrZ589RfmpiCfcy6QDIfb7iQHl_l/view?usp=sharing>`_





Screencasts and other activities
================================

Intro to Excel application development
--------------------------------------

Now it's time to start to put your new found Excel VBA skills to work in creating analytical, spreadsheet based applications. 

In this session we'll be mostly drawing on material from Chapters 7-12 in VBA for Modelers.

Overview document of this module: `ExcelVBASession3-Overview.pdf <https://drive.google.com/file/d/1SHf0xd_wmVwU-BpssspCsAxaz8sTZlDG/view?usp=sharing>`_


* `SCREENCAST - Intro to Excel Application Development <https://youtu.be/hncOmn9TwUA>`_ (2:08)
* `SCREENCAST - Arrays <https://youtu.be/B3vJeOEkx4U>`_ (9:30)
* `SCREENCAST - For-Each loops <https://youtu.be/GTmrG-88ZQ4>`_ (3:02)
* `SCREENCAST - Select-Case as an alternative to crazily nested If-Then-ElseIf <https://youtu.be/P7Rz6Gj8TZg>`_ (4:40)


While VBA allows you to do some incredible things with Excel, you can do some pretty incredible stuff with NO VBA.

* `SCREENCAST - Example of a VBA-free Climate Data Viz Tool <https://youtu.be/_aOPyZ-FjBA>`_ (9:03)


One of the best ways to learn how to develop VBA based apps is to have a need for some tool or functionality and use that as an excuse. So, I'm going to share just such an experience with you.  It's a nice little example that helps illustrate the thought process one might go through to solve a relatively focused little problem - create a subroutine to list out all the comments on a worksheet. See slides 13-14 and the file ``PatientTypes.xlsx`` if you want to see a few versions of the "answer.

* `SCREENCAST - Creating a Cell Comment Lister Tool <https://youtu.be/VVbGCE_67fg>`_ (23:59)


There are a few things you can do to make your life easier as you are learning to develop VBA driven apps. These include maximizing *design time development* and developing modular applications. Please read the chapters referenced in the slides and see the referenced examples. Focus on basic understanding of subs vs functions as well as passing input parameters into subs and functions. Then move on to more advanced concepts such as *scope* and different methods of argument passing.

* `SCREENCAST - Design Time Development <https://youtu.be/uJ_zn42b7kQ>`_ (14:22)

* `SCREENCAST - Creating Modular Applications <https://youtu.be/MOg0rGOnMIg>`_ (31:45)


We'll end this module with a series on creating user forms in Excel so that you can create a GUI that goes beyond just using the spreadsheet grid. We're actually just going to follow along with the example constructed in Chapter 11 of the VBA book (of course, I have a bunch of other niceties to add but the book covers the essentials).

* `SCREENCAST - User Forms: Getting Started <https://youtu.be/tdk6fDF8F8o>`_ (7:31)
* `SCREENCAST - User Forms: Adding Controls <https://youtu.be/_8tqoERWK7c>`_ (30:19)
* `SCREENCAST - User Forms - Adding Code <https://youtu.be/RsEK2G_-MzI>`_ (33:48)

A VBA driven scheduling optimization application
-----------------------------------------------------------

A VBA driven, optimization based application

The following example is from Ch 22 in our VBA for Modelers text. It's a nice example of a relatively straightforward VBA app. It illustrates some important concepts such as:

* minimize VBA use via design time development
* modular programming via use of multiple subroutines
* validation of user form inputs
* automation of Solver

``.Text`` property vs ``.Value`` property for form controls? Nice explanation at http://stackoverflow.com/questions/2844193/distinction-between-using-text-and-value-in-vba-access

* `Downloads-SolverSchedulingApp.zip <https://drive.google.com/file/d/1k0R8fib8sxGY535Eg3IsUQ9zc7Ia5tL8/view?usp=sharing>`_
* `SCREENCAST - Intro to Scheduling App and Validating User Inputs <https://youtu.be/1m00BIgsMQg>`_ (39:23)
* `SCREENCAST - Solve scheduling problem and create report <https://youtu.be/taoz0eIBp2I>`_ (18:26)

Porfolio Optimization with Automated Web Queries (OPTIONAL)
-----------------------------------------------------------

.. warning::

   As we saw the very first week of class, a few years ago `Yahoo stopped allowing these types of web queries <https://www.thespreadsheetguru.com/blog/add-real-time-stock-prices-and-metrics-to-excel/>`_. I'm keeping this material up here as they are still
   useful from a learning perspective. Furthermore, many of the concepts can still be used if a replacement for the financial data is found. I've
   had students do final projects that have done exactly that. 

With the glut of data available on the web, it's nice to be able to use VBA to automatically retrieve web based data for use in spreadsheet models. In this example, we are going to get stock price data from Yahoo Finance and use it in a portfolio optimization model that we create and solve in Excel using Solver. In addition, we'll see the use of additional form controls such as calendars and multi-select list boxes. This example is based on Chapter 32 in VBA for Modelers.
One of the files I use to teach web queries, ``DJI_StockQuery-MI.xls``, uses Microsoft's Calendar Control to allow the user to pick start and end dates for a set of historical stock prices. This control has been around FOREVER. So, I noticed last semester that the Calendar Control was not in the Additional Controls dialog and confirmed it when I tried my stock price app, it's gone. Microsoft killed it. Follow this link for alternatives. Thankfully, It was simple to just replace the Calendar Control with the new Microsoft Date and Time Picker Control. I then just renamed those controls to the same names as the original Calendar Controls (calStartDate and calEndDate) and didn't have to change a single line of code. The new file is included in the Downloads zip file.

* `Downloads-WebQueriesAndPortfolioOpt_W18.zip <https://drive.google.com/file/d/1OBNrq0-EOKlo8Up4QBavpO0uQFd6hTwk/view?usp=sharing>`_
* `SCREENCAST - Web Queries - Part 1: Introduction to Creating and Understanding Web Queries <https://youtu.be/ZtCa5rnR1C8>`_ (21:47)
* `SCREENCAST - Web Queries - Part 2: The User Forms (including multi-select list box and date/time pickers) <https://youtu.be/ITW-fZMaSvs>`_ (24:29)
* `SCREENCAST - Web Queries - Part 3: VBA Based Web Queries <https://youtu.be/vXwv0_IcGkE>`_ (29:24)

There have been a number of books that have come out recently about finance quants on Wall Street.

One book is entitled "The Quants: How a New Breed of Math Whizzes Conquered Wall Street and Nearly Destroyed It" by Scott Patterson.

It looks like the author along with the famous Ed Thorp (did you see the movie, "21") were also interviewed by Terry Gross on the radio show Fresh Air. Here's the link to a book excerpt and to the radio interview: http://www.npr.org/templates/story/story.php?storyId=123209339

Other recent books on the subject include:

* How I Became a Quant: Insights from 25 of Wall Street's Elite
* My Life as a Quant: Reflections on Physics and Finance

Explore (OPTIONAL)
==================

A former student passed these on to me. They are tutorials from Chris Newman, the creator of https://www.thespreadsheetguru.com/ and focus on advanced user form techniques. He also has some practical advice for application design.

* `Episode 01: Turning Ideas Into Reality <https://www.youtube.com/watch?v=9qn8-Ix1O88&feature=youtu.be>`_
* `Episode 02: Building Modern Userforms <https://www.youtube.com/watch?v=s5xAWx3sPuA&feature=youtu.be>`_
* `Episode 03: VBA Tips For Your Userforms <https://www.youtube.com/watch?v=dqVU_Z8Wlmk&feature=youtu.be>`_
* `Episode 04: Taking Excel Userforms To The Next Level <https://www.youtube.com/watch?v=pO2tqE278Sg&feature=youtu.be>`_