# Introduction to Scientific Computing 2022 Bootcamp Materials
This repo houses data and notebooks for the 2022 DSEER "Introduction to Scientific Computing" bootcamp.

## Instructions:
0) Follow the setup instructions on [this page](https://carpentries.github.io/workshop-template/#setup) titled "The Bash Shell", "Git" and "Python". Basically, everything under "Setup" not including "R" or "text editor." 
      - For python, install Anaconda.
      - The videos may be helpful. 
      - These additional tutorials may also be helpful to skim:
            _Unix shell/command line:_ http://swcarpentry.github.io/shell-novice/
            _Version control with git:_ http://swcarpentry.github.io/git-novice/
1) If you don't already have a preffered text editor, install the free version of BBEdit [here](https://www.barebones.com/products/bbedit/). If you already use a text editor you are familiar with, you can skip this step.
2) Open Terminal or other application for the bash or zsh command line (for Windows its the git bash introduced in the instructions above, for Mac and Linux its the Terminal)
3) `cd` into a directory that you want all of your bootcamp materials to live.
4) Type `git clone https://github.com/NRT-DSEER/intro-programming-2022.git`
5) Type `cd intro-programming-2022`
6) You're all set up! To start using notebooks, type `cd notebooks` 
7) Then type `jupyter notebook` 
8) This should open a new tab in your default browser and print a bunch of stuff in your terminal.
9) In the new tab that was just opened in your browser, click the notebook for the day of the course that you are on. For the first day, open "Day1_Setup.ipynb" and follow the instructions in that notebook to make sure you followed all the steps correctly.
10) Each day, start class by going into your bootcamp repo directory (`cd intro-programming-2022`) and typing `git pull`. Then follow steps 6-9.

## Directory Structure:
`data` holds data

`notebooks` holds notebooks

`solutions` contains answers to the daily check-ins and homeworks

`output` is where you will save your own files

Don't change the structure!


# Syllabus

### Instructors:
All the instructors are also on Slack, we prefer that you send us a slack message if you have any questions over sending an email. Slack is only available for students taking the live version of the course. Please check your email for information on how to join slack.

- Amanda Farah (she/her or they/them), 4th year PhD Candidate, Astrophysics
- Katie Dixon (she/her), 6th year PhD Candidate, Ecology and Evolution
- Maria D Hernandez Limon (she/her), 4th year PhD Candidate, Geophysical Sciences

### Teaching Assistants:
Contact over slack
- Salman Yousaf, incoming graduate student, MS Analytics Program 
- Shrikanth Subramanian, 2nd year graduate student, MS Computer Science 

### Class Time:
- Aug 29-Sept 14
- 09:30am-12:30pm CT 
- We will dedicate at least 20mins at the end of class to answer questions. 
- We will not have class on Labor Day 9/5.

-You will receive an email with the zoom link for class.

### Structure:
- Instructors will go over pre-written code and discuss the mechanics of what is going on
- We will stop intermittently for skill practice and breaks 
- Any code not covered should be completed outside of class with help from TAs
- Occasional, short skill practice problems as homework 

### How to ask for help:
- Ask questions on slack or in person - there is a high likelyhood someone will have the same question as you that's why we want questions on slack 
- Plan to stay the entire class period as we will offer office hours towards the end of class.
- If you need help outside of class time or office hours, contact one of the TAs via slack.
- During class, post to your slack channel and your TA will respond in real time

### Recordings:
The folder for the recordings will be posted over Slack or sent over email. We will add each day's recordings a few hours after classtime.

## Week 1: Foundation 
### 1. General instruction and go over syllabus (8/29)
- Goals for the workshop/syllabus 
- Motivation
- How this course works
- How to ask for help
- Expectations
- Rules
- Growth-mindset  
- What is programming? Why python and not R?
- Directories and file structure
- Installation- Run JN
- Introduction to jupyter notebooks-the structure 30m
- Import libraries 
- Interface, running a cell
- Markdown- comments
- Error messages-learn from mistakes
- Google
- Stack overflow
- 12:00 SET-UP and installation 

### 2. Introduction to data types and storage (8/30)
- Variables
- Booleans (side note on how bits work -transistor in 0 or 1)
- Ints 
- Floats
- Lists-indexing 
- dictionary
- Strings, and string manipulation

### 3. Automation (8/31)
- Loops- for/while
- if/else statements 

### 4. Numpy (9/1)
- Array Wise operations and math
- 2D arrays, linear algebra
- All numpy knowledge we learned here is enough for basic data manipulation

### 5. Numpy Continued (9/2)

## Week 2:  Functions and Pandas

### 1. Functions (9/6)
- User-defined functions
- docstrings!!!
- List python built-in functions
- Discuss how functions relate to libraries

### 2. Introduction to Plotting (9/7)
- plotting with matplot
- using functions for automating plots

### 3. Introduction to pandas (9/8)
- Create a dataframe from scratch
- Read in tabular data into a dataframe
- View and access data in the dataframe
- Save and export a dataframe

### 4. Introduction to pandas (9/9)
- Modify dataframe
- Modify values
- Clean data and make a function to import data
- Merge, concat, append
- Automation (functions, for loops)

## Week 3: Applied

### 1. Pandas applications (9/12)
- Intro to Math/Stats  
- Intro to pivot, groupby
 
### 2. Advanced Plotting (9/13)
- Seaborn
- Maps
- gif 

### 3. Automation  (9/14)
- .py/.sh scripts


## For those of you who signed up to take the machine learning course:

### 4. Machine learning (9/15)
- Introduction to Random Forests

### 5. Machine learning (9/16)
- Introduction to Neural Networks

