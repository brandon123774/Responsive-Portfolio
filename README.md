# Responsive-Portfolio
* Introduction
* Technologies Used
* How to Use

# Introduction
The goal of this assignment was to be able to resize out portfolio without using any Bootstrap and Bootstrap components so that the window can resize and still be correctly formatted in various sizes/ platforms. This allows users to view the Portfolio from platforms such as a desktop view, tablet view, and even a mobile phone view. The changes were made using media queries in CSS.

 /* desktop view */
    @media screen and (max-width: 980px)  {
        .container  {
            max-width: 980px;
        }
    }      

    /* tablet view */
    @media screen and (max-width: 768px)  {
        .container  {
            max-width: 768px;
        }
    }

    /* mobile view */
    @media screen and (max-width: 640px)  {
        #logo  {
            position: static;
        }
        .container  {
            max-width: 640px;
        }
        nav {
            position: static;
            display: inline-block;
            text-align: center;
        }
        nav a {
            position: static;
            display: inline-block;
            text-align: center;
        }

    }
# Technologies
* HTML
* CSS

# How to Use
To view the Porfolio, click on the Github link and then using a computer or any other platform, resize the webpage and it should respond accordingly.