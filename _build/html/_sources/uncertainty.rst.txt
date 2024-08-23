***********************************
Intro to modeling uncertainty
***********************************

Modeling uncertainty is a huge and important topic. We took our first steps in modeling it when we used Data Tables for one and two variable sensitivity analysis. Now we will follow up with more sensitivity analysis using the sensitivity analysis tools built into Palisade Decision Tools such as TopRank. However, all of this ignores the critical role played by probability and statistics. As we start to learn advanced techniques like Monte-Carlo simulation or data mining, we'll review the essentials of probability distributions and data modeling (Ch 4 and 5) and sampling distributions (Ch 7). Warning - many people find working with probability (and stats) to be challenging. In fact, we'll start out with some fun and interesting probabilistic challenges meant to make you a little uneasy. smile I'm sure most of you have had a basic probability and statistics course at some point and that this will be somewhat of a review. I'll be focusing on the things we need from probability and stats for doing more advanced business analytics. However, I certainly won't have time to review everything in class. I've included several screencasts below to help you review.

Then we will move on to more advanced analytics  topics like Monte-Carlo simulation  and data mining. I'll continue to inject more review of basic statistics into the sections on stochastic modeling and data mining (since one can't really do such things without a solid understanding of basic statistical methods such as probability distributions, descriptive statistics, estimation and confidence intervals, hypothesis testing, and regression modeling.)

Intro and Objectives
====================

We will start by talking about the perils and paradoxes of uncertainty and move on to different methods of baking uncertainty into our spreadsheet models. After this Module you should:

* Have a better understanding of the perils and paradoxes of uncertainty in the context of modeling business problems
* Be able to perform sensitivity analysis in spreadsheets using a variety of techniques
* Understand and be able to use probability and statistics to start to model uncertainty
* Understand the "Flaw of Averages" and its implications for building spreadsheet models
* Be well positioned to learn able to use @Risk and other specialized Excel add-ins to build simulation models, conduct simulation experiments and analyze and interpret the results.

Readings
========

To analyze simulation output we need statistics. To build models we need to understand probability. This is all stuff you should have had before and should be able to review.

* Business Analytics - Chapter 4,5,7: Review of probability models and sampling distributions

This is the new stuff.

* Business Analytics - Chapter 15: Introduction to simulation modeling


Downloads
=========

* `Downloads-IntroUncertainty.zip <https://drive.google.com/file/d/1o7_KwrjbN0uk9u6C9th42rh2yI3vP4AU/view?usp=sharing>`_


Screencasts and other activities
================================

Prelude to Simulation
---------------------

* `SCREENCAST: Intro to Uncertainty Modeling <https://youtu.be/V8mppjOZhLs>`_ (7:23)

Make sure you've got the slides open from the Downloads for this Module. We'll start by talking about sensitivity analysis and explore a tool that fills the gap between the kinds of sensitivity analyses we've done so far and the simulation modeling we are moving towards.

* `SCREENCAST: Sensitivity Analysis with Top Rank <https://youtu.be/CEE9GpohV_A>`_ (22:55)

Probability distributions and a preview of simulation
-----------------------------------------------------

Probability is the language of uncertainty. In order to explicitly model uncertainty in spreadsheet based simulation models, we need to have a working knowledge of probability and probability distributions. We'll review discrete and continuous distributions, learn a bit about how computers generage "random numbers" (they aren't random), and get our first taste of doing spreadsheet based simulation modeling.

* `SCREENCAST: Overview of Probability Distributions and Discrete Distribution Review <https://youtu.be/KhpU48p88dQ>`_ (16:45)
* `SCREENCAST: Review of Continuous Probability Distributions <https://youtu.be/1JMpRyS24hw>`_ (20:37)

Simulation relies on random numbers. How do computers generate random numbers? Well, they are NOT really random.

* `SCREENCAST: How do Computers Generate Random Numbers? <https://youtu.be/v3bQmMae3sM>`_

Now we will build a simple simulation model using Excel only (no special add-ins). This will provide a nice intro to Monte-Carlo simulation, including using probability distributions to model uncertain quantities, generating random variates, and statistically analyzing output.

* `SCREENCAST: 3 Product Simulation Model  <https://youtu.be/cR0JRn-7TzA>`_ (23:09)
 
This concludes our introduction to the huge world of modeling uncertainty. Next week we'll start a module on Monte-Carlo simulation that uses all of this stuff.

Descriptive Statistics (OPTIONAL)
---------------------------------

Excel ships with an add-in called the Data Analysis Toolpak which includes a number of statistical tools, procedures and tests. We used the DAT in an earlier module for creating histograms. Here's a short screencast showing the use of the Descriptive Stats part of the DAT. In addition I show how to use Excel functions to compute the various quantities shown in the Descriptive Stats output. Like the DAT histogram tool, the output is static - if your data changes you must rerun your analysis with the DAT. Formulas, however, will automatically update if your data changes (especially nice if you use range names and just make sure you keep your range name definitions updated).

* `SCREENCAST: Doing Descriptive Statistics with the DAT and with Excel Formulas <https://youtu.be/w888X_1gNew>`_

A handy statistical rule to know about is the Empirical Rule. Here's a `little screencast <https://youtu.be/uPVevBLeP7E>`_ I put together to show you you can use Excel array formulas to check how closely a dataset conforms to the empirical rule.

While the DAT is nice, it's not anywhere close to a real statistics package. I want to show you one such package, JMP. It's actually part of the SAS family of products and while a little quirky in its interface, is extremely powerful and easy to use. The SBA has a site licence for JMP and you can get it for free. Go to the SBA Resources page.
To help the SBA community become familiar with JMP, I made a few screencasts. Here's the intro which includes the basics of JMP interface, getting data into JMP from Excel (using JMP add-in as well as via CSV and copy-paste), doing descriptive stats, histograms, box plots, and a one-sample hypothesis test.

* `SCREENCAST: Getting started with JMP <https://youtu.be/_-KLQpLKQLU>`_ (7:15)

This Module will end with a brief introduction to Monte-Carlo simulation and we'll use descriptive statistics (and a confidence interval) to analyze the output.

Explore
=======

ExcelIsFun YouTube channel
------------------------------------------------------------

The "Excel is Fun" YouTube channel has tons of great Excel videos. Here's a `whole series of videos on using Excel for doing statistical analysis <https://www.youtube.com/playlist?list=PL5F2E2CD779B25058>`_.

