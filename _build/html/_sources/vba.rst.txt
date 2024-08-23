***********************************
Excel VBA
***********************************

We will start with a three week crash course in Excel VBA (2 weeks) and spreadsheet application development (1 week). 
Make sure you have the VBA for Modelers textbook.

A quote from Enterprise Data Analysis and Visualization: An Interview Study on the growing need for technically adept analysts:

    When discussing recruitment, one Chief Scientist said "analysts that can't program are disenfranchised here”

Objectives
====================

In this module you will learn the basics of Excel VBA programming. By the end of it, you should understand and/or be able to use/do the following:

* Understand the role of VBA in spreadsheet application development
* Use the VB Editor effectively
* Be able to create and modify basic programs using variables, conditional logic, loops, input boxes, message boxes, Excel objects (worksheets, ranges, etc.), and VB functions.

Readings
========

* In this 2-week crash course we'll be mostly drawing on material from Chapters 1-10 in VBA for Modelers.
* Chapter 5 (Getting started with VBA) is VERY IMPORTANT.
* Chapter 6 (Range object) is ALSO VERY IMPORTANT in terms of learning the most important object in Excel programming.
* Later in the term we'll be using other chapters when we learn more advanced spreadsheet application development skills.

Downloads
=========

* `Downloads-Module05-VBA.zip <https://drive.google.com/file/d/1FMQ3KbCUfQ-qq32COvhccAS8iFZ91Mx3/view?usp=sharing>`_


Screencasts and other activities
================================

Excel VBA 1 - Intro to VBA programming
---------------------------------------

Read Chapters 1-3 in VBA for Modelers. In Section 3.5 of VBA for Modelers, follow along and do "A First Program" on pages 24-29 (page numbers may vary by edition). Name your file ``First_Program-YourName.xlsm``. Depending on which edition of the VBA book you bought, use the appropriate file. 

* `SCREENCAST: Intro to VBA <https://youtu.be/1SvJz_jegt8>`_ (24:07)

Before we really get into programming, let's do some Macro Recording to get a preview of VBA and the Excel Object model.

* `SCREENCAST: Object model intro <https://youtu.be/p10k8zY_8Dc>`_ (40:38)

Now, let's become familiar with the VB Editor and get some understanding of basic logic flow in computer programs.

* `SCREENCAST: The VB Editor (VBE) and Program Flow Basics <https://youtu.be/9sadwfHLImI>`_ (17:20)

Ok, now let's dive in and learn about variables, Dim statements, and some basic concepts regarding subroutine and function procedures. We'll also learn basic debugging using stepping and the Immediate Window.

Exercise 5.1 - Displaying a Message. You should try to do this now yourself. You can find the solution in the ``\Exercise5_1and2`` folder inside of the Downloads folder.

* `SCREENCAST: Variables and Procedures Basics <https://youtu.be/2bIqk2YIG78>`_ (39:03)

And we will end this first session on VBA by learning about built in VBA functions via a little string parsing exercise.

Exercise 5.2 - Displaying a Message. You should try to do this now yourself. You can find the solution in the ``\Exercise5_1and2`` folder inside of the Downloads folder.

Next week we will dive into the Excel Object Model with a focus on Range Objects (Chapter 6).

* `SCREENCAST: Intro to VBA Functions via String Parsing Fun <https://youtu.be/DsmOVD81DmI>`_ (52:56)

Excel VBA 2 - The Excel Object Model
------------------------------------

Now that we've covered the very basics of programming, let's take our first real dive into the Excel Object model.

* `SCREENCAST: Dive Into the Excel Object Model <https://youtu.be/qvzMarYxvo8>`_ (32:27)

The first video ended with a challenge to solve Exercise 5.3. Let's see how it's done.

* `SCREENCAST: Solving Exercise 5.3 <https://youtu.be/qPOxIv_2eMo>`_ (11:45)


In this next video I'll show how to do the extensions to Exercise 5.3 mentioned in the slides.

* `SCREENCAST: Extensions Exercise 5.3 <https://youtu.be/XpbsSN2iubg>`_ (21:33)


After Exercise 5.3, we see the need to learn about control logic - things like loops and if-then statements.

* `SCREENCAST: If-Then and Looping <https://youtu.be/9-w3QZa_xF8>`_ (18:40)


Now we will revisit the First Program you did earlier and pick up a few more debugging techniques such as Watches and Breakpoints.

* `SCREENCAST: FirstProgram and More on Debugging Programs with the VBE <https://youtu.be/uPQSk9eWfyQ>`_ (20:03)


We'll use a simple averaging program to see loops and if-then in action.

* `SCREENCAST: The Averaging Program <https://youtu.be/4QSfc25mIH0>`_ (33:33)

We'll conclude this part of the VBA crash course with an in-depth look at the Range object.

* `SCREENCAST: The Mighty Range Object <https://youtu.be/BRcegYUXtr4>`_ (46:47)

Several people have asked questions related to copying a range in a spreadsheet to other places within the workbook or into another workbook. So, I worked up a quick set of examples. Download and extract `range_copy.zip <https://drive.google.com/file/d/1kd-_FPhTLdEjenf5nZQw1_1nabWWWqow/view?usp=sharing>`_ and then open the ``range_copy.xlsm`` file and you'll find buttons on the first sheet that are associated with different examples. The code is heavily commented.


Putting it all together - the Break Even problem
------------------------------------------------

Now, let's put it all together with a little exercise in which we'll use VBA to mimic the functionality of a one-way data table. I've broken this up into four short screencasts. There's also links below to the files uses in this exercise. I HIGHLY recommend that you work through this before attempting the VBA homework as it will give you a chance to make sure you understand how to use basic range referencing, looping, and conditional logic to accomplish a typical Excel task. All the files you'll need are in the ``\BreakEven`` subfolder of the Downloads file.

* `SCREENCAST: The Break Even Problem <https://youtu.be/znSr3BcinGE>`_ (5:45)
* `SCREENCAST: Filling the MyProfit range <https://youtu.be/WtTnkngW9yA>`_ (11:24)
* `SCREENCAST: Automated Goal Seek for break even volume levels <https://youtu.be/UC4AhB6Qa_Q>`_ (10:17)
* `SCREENCAST: Detecting the break even point (goes beyond the Basic Solution) <https://youtu.be/dXcoLpALNDI>`_ (14:04)

Explore
=======

Learn about Grace Hopper, a true software pioneer. You'll also find out where the programming term *bug* came from.

* `The Queen of Code <http://fivethirtyeight.com/features/the-queen-of-code/>`_

Nice example of how VBA can be used to generate custom spreadsheets for non-technical end-users.

* `Disseminating Emergency Preparedness Planning Models as Automatically Generated Custom Spreadsheets <https://www.jstor.org/stable/pdf/20141564.pdf>`_

Good example of using VBA to encapsulate complex, model specific, formulas in UDF's (user defined functions)

* `Spreadsheet Models for Inventory Target Setting at Procter & Gamble <https://www.jstor.org/stable/pdf/20141562.pdf>`_



