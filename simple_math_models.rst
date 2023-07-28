***********************************
Simple mathematical models
***********************************

In this module we'll explore a handful of simple mathematical models for relating input and output variables of interest - linear, power, exponential, and logistic. We'll even take a look at the Pythagorean Theorem of Baseball - if you've seen Moneyball (or read the book), this equation was actually shown in one of the film sequences. I hope you come away with an appreciation for the power and elegance of such simple models. Of course, along the way, we'll pick up some more serious Excel wizardry.

I'll make available a set of skeleton notes that we'll use to explore the different model forms in more detail.

Recall, last time we started to talk about various modeling heuristics - common sense ways to approach complex problems. Here's a good heuristic ...

.. image:: images/heuristic.jpg

Learning Objectives
====================

In completing the activities in this module you will:

* become familiar with common mathematical models that can be useful for business modeling,
* learn to fit common models using data and assess model fit using different metrics
* learn how to use advanced Excel functions and tools such as LINEST and the Data Analysis Toolpak,
* start to gain an appreciation for the relative ease of fitting models compared to the difficult nature of using models to accurately predict using new data.



Readings
========

* Example 2.5 - Estimating sensitivity of demand to price at the Links company in the same PDF we used for the Prep Problems. Equivalently, the material in this PDF has now been included in Ch1 of the 7th edition of our Business Analytics textbook.
* Sections 12.1-12.4 in our Business Analytics textbook are also relevant.

Downloads
=========

* `Downloads-Module03-SimpleMathModels.zip <https://drive.google.com/file/d/1mXZaNLueF5E1Irn76ZR-Jmep9bdKg4Tb/view?usp=sharing>`_


Session Activities
================================

Getting Started
---------------

You can find the slides and the short Lecture Note used to structure this session inside the Downloads file.
You'll notice that there are a few optional topics. Feel free to skip these for now and you can always take a look at them later.

Introduces idea of simple mathematical models for capturing relationships between important variables in some business problem (such price v demand, sales v time)

* `SCREENCAST: Simple Math Models - Getting Started (11:31) <https://youtu.be/JpiTxtwogfM>`_

Pythagorean Theorem of Baseball
-------------------------------

Now let's look at an interesting little model developed by the grandfather of sabermetrics, Bill James. It was featured in Moneyball. We'll use this as an example to talk about the power of simple models, the role of model parameters and comparing competing model forms.

* `SCREENCAST: SimpleMathModels - Pythagorean Theorem of Baseball (14:03) <https://youtu.be/DYrJLIswLes>`_

Linear Model
------------

While we will cover a handful of mathematical model forms, we'll start with the model that's probably most familiar to you. However, you might not know 6 different ways to do linear regression in Excel. This will also highlight the very important topic of metrics for evaluating model performance.

* `SCREENCAST: Simple Math Models - Linear (32:05) <https://youtu.be/FHJw3vgLyoQ>`_

Power Model
-----------

Power models see wide use in everything from economics to laws of nature such as the relationship between an animal's metabolic rate and their body mass.

* `SCREENCAST: Simple Math Models - Power (18:30) <https://youtu.be/44osywKlFM8>`_

Exponential and Logistic Models
-------------------------------

Exponential growth can be scary.

* `SCREENCAST: Simple Math Models - Exponential (19:49) <https://youtu.be/iWNzdFDdgHY>`_

Did you know it's easy to turn an exponential growth model into a linear growth model? See Moore's Law in action and also learn some useful chart construction techniques including addition of new series to existing charts and solving the mystery of Excel refusing to plot your exponential trend line.

* `SCREENCAST: Simple Math Models - Exponential becomes Linear (10:58) <https://youtu.be/eRsh1L84MdA>`_

[OPTIONAL] This model is a remedy to unrealistic sustained exponential growth. Again, gets wide use in both business and the natural world to capture the fact that there are usually limits (resources, competition, obselescence, ...) to continued exponential growth. Right near the end of this screencast is something
pretty cool that happens in Excel with this model. :) And, if you want to know a little more about this phenomenon and how the logistic model is
related to the chaos theory, fractals, and the Mandelbrodt set, check output
this `video on the Veritasium channel. <https://www.youtube.com/watch?v=ovJcsL7vyrk>`_

* `SCREENCAST [OPTIONAL]: Simple Math Models - Logistic (18:50) <https://youtu.be/usxVqd-tyD4>`_

The Golf Clubs Pricing Problem
------------------------------

This is another example that we'll borrow from the PMS Ch2 PDF. It is Example 2.5 Estimating Sensitivity of Demand to Price at the Links Company. You will find a subfolder named \GolfClubsPricingExample inside the Downloads file for this module. It's got the skeleton Excel file you'll need as well as a PDF giving a 30,000 foot overview of the problem.

We will fit three different models and learn how to compare their fit using a variety of metrics such as MAD, MSE, and RMSE.

* `SCREENCAST: Golf Clubs Pricing - Model Fitting (19:16) <https://youtu.be/KTX9vTgzdkc>`_

Now that we have a pricing model, we can embed it a pricing optimization model. Includes some fancy function footwork using INDEX and MATCH.

* `SCREENCAST: Golf Clubs Pricing - Optimal Price (23:06) <https://youtu.be/QGHiw_PdrwQ>`_


Uncertainty - The elephant in the room 
-----------------------------------------------------------

What about uncertainty? We've dealt with it only via some rather rudimentary sensitivity analysis and curve fitting. This last screencast will discuss this issue a bit, demonstrate a real model from the healthcare world that directly deals with uncertainty, and closes with some concluding thoughts on the difficult craft that is quantitative and computer modeling. We will be revisiting the question of modeling uncertainty later in the semester.

* `SCREENCAST: Simple Math Models - 7-11 and Conclusion (34:19) <https://youtu.be/MZ5MLrhp32E>`_


Explore (OPTONAL)
=================

`xkcd on trend fitting in Excel <https://xkcd.com/2048/>`_

`Mathematical Doodling <https://www.youtube.com/playlist?list=PLF7CBA45AEBAD18B8>`_
-----------------------------------------------------------------------------------

Vi Hart was featured in the `Jan 18, 2011 Science section of the NY Times <https://www.nytimes.com/2011/01/18/science/18prof.html>`_.The first one of her videos I ever saw was `Doodling in Math Class: Binary Trees <https://www.youtube.com/watch?v=e4MSN6IImpI&t=0s&list=PLF7CBA45AEBAD18B8&index=2>`_.

The Crater model
----------------

Here are links to two follow up stories on the use of the Crater model.

* http://www.nytimes.com/2003/06/08/us/questions-raised-on-equation-nasa-used-on-shuttle-peril.html?src=pm
* http://www.nytimes.com/2003/08/25/us/computer-program-that-analyzed-shuttle-damage-was-misused-engineer-says.html?pagewanted=all&src=pm

Excel's 2016 Forecasting tool
-----------------------------

Microsoft added some `basic time series forecasting models to Excel 2016 <https://www.microsoft.com/en-us/microsoft-365/blog/2015/10/06/one-click-forecasting-in-excel-2016/>`_. We now have an entire class on time series forecasting in the SBA - QMM 4520.


More on trend line fitting
--------------------------

We have seen how easy it is to fit a trend line to data in an X-Y scatter chart. Excel allows us to fit a linear, power, exponential, logarithmic or polynomial function to our data and display the equation (the fitted model) on the chart.

While this is very handy, sometimes we want to use the various parameter values from the fitted trend lines in our spreadsheets. That's often why we fit the trend line (our model of the data) in the first place. So, how can we fit these trend lines using Excel functions in such a way that we can get the actual parameter values into cells (and so they are not just a label on the graph)?

The spreadsheet TrendFittingFunctions.xlsx (found in the Downloads zip file for Module 3) shows how this can be done for linear, exponential, logarithmic, power and polynomial trend lines. While the details differ for each of the five models, several features pop up in more than one model: use of LINEST(), the array function for fitting linear regression models, use of LN(), LOG10() functions and the properties of exponentials and logarithms to transform non-linear regression problems into linear regression problems (for which we can use LINEST()).



