# Alex Clayton's Portfolio Project

## Introduction
This project was developed by Alex Clayton as part of the KU Coding Bootcamp 02-Advanced-CSS Challenge.  This is a first draft depoloyment of a portfolio webpage that may or may not see future use beyond the bootcamp.  

## What's in the project?
The acceptance criteria for this project are as follows:

1.  WHEN I load the portfolio
    THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

    The project meets these requirements in the header section.

2.  WHEN I click one of the links in the navigation
    THEN the UI scrolls to the corresponding section

    This criteria is also met in the header section.

3.  WHEN I click on the link to the section about their work
    THEN the UI scrolls to a section with titled images of the developer's applications

    The portfolio link in the nav bar takes the user to the portfolio located in the main section.  Aesthetically pleasing placeholder images were used for any projects that do not already exist or are yet to be completed.

4.  WHEN I am presented with the developer's first application
    THEN that application's image should be larger in size than the others

    This was achieved by using the grid-template-columns property in the CSS stylesheet.
    <pre> .portfolio-grid {
        display: grid;
        grid-template-columns: repeat(2, 1fr);
        grid-auto-rows: 200px;
    }
    
    .box1 {
        grid-column-start: 1;
        grid-column-end: 3;
        grid-row-start: 1;
        grid-row-end: 3;
    }

5.  WHEN I click on the images of the applications
    THEN I am taken to that deployed application

    As only one of the linked projects actually exists, clicking on the larger box titled first project will link the user to the challenge we submitted during the 01-HTML-Git-CSS challenge of the bootcamp.

6.  WHEN I resize the page or view the site on various screens and devices
    THEN I am presented with a responsive layout that adapts to my viewport

    Working on this with flexboxes...

The completed project resembles the following image when deployed:
[ADD SCREENSHOT OF FINAL PRODUCT]

