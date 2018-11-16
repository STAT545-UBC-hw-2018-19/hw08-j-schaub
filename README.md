# STAT 547M : Homework 8 - Making a Shiny App

This repository contains the files associated with Homework 8 from the STAT 547M course at UBC. 
For more information, please see the [assignment](http://stat545.com/Classroom/assignments/hw08/hw08.html)

## Additions

For this assignment, I have added to our existing B.C. Liquor Stores app in the following ways:
  1. Changed some of the visual aspects of the data display:
    a. Sorted liquor type by color in the histogram, so the user can determine where each type falls.
    b. Added conditions to the table to only display the data that is being presented in the graph.
  2. Added a drop-down menu so the user can filter by country.
  3. Changed the theme to "cyborg" using `shinythemes` package.
  
Note: I wanted to learn to use conditional panels to filter by country, but I can't get the `if` statement to work when I try to filter the table and graph. 
So the table and graph are always being filtered by country, even if the box is not checked. The default is set to "Canada".

## Files

The following files are relevant for the reviewers:

- [App Code](https://github.com/STAT545-UBC-students/hw08-j-schaub/blob/master/bcl/app.R) : Contains the code for the app
- [App](https://j-schaub.shinyapps.io/BC_Liquor_Price_App/): A link to the online app
- [Data](https://github.com/STAT545-UBC-students/hw08-j-schaub/blob/master/bcl/bcl-data.csv): A link for the liquor data, it has been tidied and rendered as a `.csv` by Dean Attali.
