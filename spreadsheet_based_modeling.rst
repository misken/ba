***********************************
Spreadsheet based modeling
***********************************

Intro and Objectives
====================

We will spend the first few weeks of the semester building a basic foundation of spreadsheet modeling/engineering skills before diving into more advanced modeling and spreadsheet application development topics. We will start by focusing on:

* Basic modeling principles
* Basic spreadsheet modeling and spreadsheet engineering principles
* Continued development of Excel skills to facilitate modeling

After completion of this module:

* You will have a better appreciation for the wide variety and pervasive use of models and modeling in business.

* You should be able to use basic model building principles such as simplification, decomposition, input/output identification, prototyping, parameterization, 
  quieting the critic, working backwards, and focusing on structure instead of data.

* You should start to understand the different things we do with models such as sensitivity analysis and/or simulation (what if?), optimization (what's best?), 
  exploration, visualization and communication.

* Understand and be able to use Excel concepts and techniques such as absolute and relative cell addressing, R1C1 notation, range names, Data Tables, Goal 
  Seek, date/time values and functions, VLOOKUP(), SUMPRODUCT() and other advanced Excel functions.

* Understand and be able to use spreadsheet design and engineering principles such as logical layout, avoiding hard coding, isolating input parameters, 
  designing for use and maintainability, finding and avoiding errors, simplification through formula decomposition and range naming, documentation, use of dynamic visual cues, formula auditing and other testing techniques.

Readings
========

The readings for this module are intended to provide an introduction to basic modeling principles, get you used to the style of our textbook (which mixes conceptual material with hands on Excel implementation details), and increase your awareness of spreadsheet design and construction principles that will help you create better spreadsheet models. We will use these ideas throughout the semester.

* If you have the 7th edition of our BA:DADM textbook, it now includes the intro to spreadsheet modeling material in Chapter 1 (thank you W&A for putting this material into your BA:DADM textbook). If not, you can use the Practical Management Science - Chapter 2: Intro to Spreadsheet Modeling pdf that we used for the Prep Problem.
* Errors are rampant in business spreadsheet models. Check out a few of the horror stories at: http://www.eusprig.org/stories.htm
* Then to help you avoid similar mistakes, read:  `How do you know your spreadsheet is right? <http://arxiv.org/ftp/arxiv/papers/1301/1301.5878.pdf>`_

Downloads
=========

* `Downloads_SBM.zip <https://drive.google.com/file/d/1nOY3myKTy1AhMoHE8JZl5-OcS-2V61is/view?usp=sharing>`_


Session Activities
================================

This is a pretty packed session, but will give us a great foundation for moving forward learning spreadsheet based modeling.

Excel technique review
----------------------

Let's start by reviewing a very important spreadsheet concept - absolute and relative cell addressing. It is essential that you firmly master this concept before moving on to spreadsheet model building. The following short video will review this topic and give you a chance to practice using it. In addition, we will review two related topics, R1C1 reference style and range names. In the Downloads file you'll find a folder
named \Tutorials. In it you'll find the `Excel Tutorial from Albright's Free Downloads page <https://kelley.iu.edu/albrightbooks/Downloads/Excel%20Tutorial%20for%20Windows.xlsx>`_ along with an older version that I've added some things to. We'll use the older version - it's called
**excel_tutorial.xlsm**.

As you will see, these tutorial files provides a very comprehensive review of numerous Excel techniques that we will use throughout this course. Time spent reviewing this file will be time well spent. So, download the file and get it open on your computer. Then, watch the following short video and work along with it in the file provided above.

NOTE: There were some screen zooming issues in the R1C1 section, and I've fixed them.

* `SCREENCAST: Absolute/relative cell addressing, R1C1, range names (27:25) <https://youtu.be/5vecp_9x7No>`_

Intro to Modeling
-----------------

Here's an introduction to basic modeling concepts, part 1. The Powerpoint slides from the Downloads file will be used during some of the video content in this module:

* `SCREENCAST: Intro to Modeling <https://youtu.be/gWi-ia-Bv6Q>`_


Influence Diagrams
------------------

The first modeling technique we will learn is called an influence diagram. It's a great technique for getting started on building a spreadsheet model. There are some guidelines for creating influence diagrams in the slides for this module and here's a short video on creating influence diagrams:

* `SCREENCAST: Getting started with influence diagrams <https://youtu.be/5ur7qr7opC0>`_


Prep Problems
-------------

Within the Downloads zip file for this module you'll find my versions of the NCAA T-shirts and the Bookshelves prep problems. Take a look at them. Here's a short video with my comments on my versions of the Prep Problems.

* `SCREENCAST: Prep Problems: Tshirts and Bookshelves (4:16) <https://youtu.be/crtIwv3YxKA>`_

Building and using a break-even model
-------------------------------------

Now we will build a simple break even model and use it to do some sensitivity analysis and "backsolving". This is Example 2.3 from the PMS Ch2 PDF (or Chapter 1 in 7ed of BA textbook). However, I demonstrate a number of additional techniques not covered in the chapter and also try to relate the model building process to some of the modeling building hueristics discussed earlier in this lesson. I've broken up the model building session into a few separate videos. You'll need the **Ex0203-BreakevenAnalysis-template.xlsx** file included in the Downloads zip file for this module.


In the first video, we construct the base model and learn some model verification techniques.


* `SCREENCAST: Break Even - Base Model (35:44) <https://youtu.be/gGhMwL-MkDk>`_


In the second video, we do some sensitivity analysis using a one way data table.


* `SCREENCAST: Break Even - One Way Data Table (17:41) <https://youtu.be/dSgCl14mO5I>`_


In the third video we find the break even point using Goal Seek and see how we can automate the process by recording a simple macro. Simple conditional formatting is also demonstrated and an advanced conditional formatting challenge is posed. We also do a little graphing to visualize the break even point and the form of the profit function.


* `SCREENCAST: Break Even - Find Break Even Point (9:44) <https://youtu.be/8HNORy3oc8M>`_


In the fourth video we take the sensitivity analysis one step further with a two way data table.


* `SCREENCAST: Break Even - Two Way Data Table (8:42) <https://youtu.be/io3Oq9xdRLc>`_

More modeling heuristics and spreadsheet design tips
----------------------------------------------------

Slides 25-37 in the ``BA-Modeling-1.pptx`` file have several more modeling heuristics and a summary of 
spreadsheet design tips (many of which we've seen in action in the Break Even model). Take a look
at these as they will prove helpful throughout the semester.

Explore (OPTIONAL)
==================

* `Why airlines overbook: Using toy models to maximize revenue <https://online.hbs.edu/blog/post/why-airlines-overbook-using-toy-models-to-maximize-revenues>`_ - captures the spirit of the value of simple, "toy" models

As someone who learned 
spreadsheeting on Version 1a* of Lotus 1-2-3, I have a fondness for the history of spreadsheets. Life was simple, just do /rnc and you can make a new range name.

* `'Recalc or Die': MS veterans recall early days of Excel <https://www.geekwire.com/2015/recalc-or-die-30-years-later-microsoft-excel-1-0-vets-recount-a-project-that-defied-the-odds/>`_ - This just came out a few years ago. It's a great read.
* While we're on the subject of spreadsheet anniversaries, check out these two terrific sites dedicated to the history of the spreadsheet. The first, `Software Arts and Visicalc <http://www.bricklin.com/history/sai.htm>`_, was created by Dan Bricklin, one of the original creators of Visicalc. It's a fascinating site with the history of the Visicalc's development, screenshots of the original documentation cards and even a link to a working(!) version of Visicalc. For another look at the `Story Behind the Story of Visicalc <http://dvandusen.no-ip.info:8080/visicalc_story/Visicalc_wiki_2.htm>`_ ...
* Next is Dan Power's `A Brief History of Spreadsheets <http://dssresources.com/history/sshistory.html>`_. 




