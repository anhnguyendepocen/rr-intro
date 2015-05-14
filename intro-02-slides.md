Reproducible Science Workshop - Intro II
========================================================
font-family: 'Helvetica'
date: May 14, 2015

Intro I summary
========================================================

* We learned that everyone struggles with reproducibility and that it is a hindrance to moving science forward

* We focused on 4 problems: organization, documentation, automation, and dissemination with a fairly simple analysis. Over the two day workshop, data analysis tasks will become more complex as we gather more data and ask more complicated questions

Four facets
========================================================

* Organization: you will be given tools to organize your projects so that you don't have a single folder with hundreds of files

* Documentation: you will learn the difference between binary files (e.g. docx) and text, files and why text files are preferred for documentation using a simple tool called markdown that you can use to write descriptions of your data and your workflow so that anyone can pick up your data and follow what you are doing

* Automation: you will learn about the power of scripting in the R programming language and how you can integrate that into markdown to create automated data analyses

* Dissemination: you will see that publishing is not the end of your analysis, rather it is a way station towards your future research and the future research of others

Toolkit
========================================================

![R](img/Rlogo-1.png)

* * * 

![RStudio](img/RStudio-Logo-Blue-Gradient.png)

Why R?
========================================================

* Programming language for data analysis
* Free!
* Open source
* Widely used and supported across all disciplines
* Can be used on Windows, Mac OS X, or Linux

* * * 

![RSplashScreen](img/RSplashScreen.png)

Why not language X?
========================================================

* There are a number of other great programming tools out there that can also be used to improve the reproducibility of your analysis

* The key is to use some type of language that will allow you to automate and document your analysis

* Once you master one language you'll probably find it easier to learn another

Why RStudio?
========================================================

* Gives you a single environment to combine your documentation and your analysis with markdown support
* Runs on top of R
* Gives you a bunch of really cool features that we'll explore throughout the workshop

* * * 

![RSplashScreen](img/RStudioSplash.png)

Anatomy of RStudio
========================================================

<center>
![RSplashScreen](img/RStudioSplash.png)
</center>

Exercise 2: Dive deeper
========================================================

1. Append the new data gapminder-seventies-and-eighties.csv and gapminder-nineties-and-later.csv to your existing data set. <br>*Be careful* as you do so, as the ordering of columns in the data set may not match between the different CSV files!

2. Create line plots of life expectancy over time for Canada, Mexico, and the United States that run from 1952 to 2007.<br>
*Stretch goal:* In the same plot, add similar line plots for Cambodia, China, and Japan and Uganda, Egypt, and South Africa.

3. Create a scatter plot depictcting GDP vs. life expectancy of countries in Europe for 2007. <br>
*Stretch goal:* In the same plot, add another scatter of points for Asia, Africa, and the Americas, coloring the countries from each region (continent) with the same color.