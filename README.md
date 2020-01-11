# Project:HTML/CSS - Google Homepage
This is a HTML/CSS solution for a Web Development 101 [assignment](https://www.theodinproject.com/courses/web-development-101/lessons/html-css)
from The Odin Project. The objective of the assignment is to use developer tools to deconstruct the
[Google home page](https://www.google.com/) and rebuild it's appearance step-by-step. No functionality is included in
the assignment, only HTML and CSS.

## Project Post-Mortem
This was my first project for the Odin Project and having used WYSIWYG editors in the past to create HTML pages, doing
so by hand was an intimidating challenge at first. After getting the hang of it, I found the process to be enjoyable
and not that difficult. One thing I wanted to do was to not peak at the DOM and CSS through the Chrome developers tools
but and build it by eye but some parts required me to get a better look to align elements correctly.

My goal was to get it looking as close to the real page as possible and have it look good on desktop and mobile views.
Some things I made use of were semantic HTML elements instead of using all DIV's better define the purpose of the page
sections. For layout, I used a combination of Flexbox, inline-box and floats to position the elements just where I want
them.

As a stickler for details, I've used an onscreen ruler to align items more precisely.

## Screenshots
![Desktop](/screenshots/google-homepage-laptop.png)
![Mobile](/screenshots/google-homepage-mobile.png)

## To Do
The real Google home page combines multiple images into one composite images and then maps sections of the combined
image to make it look like separate images throughout the page. This would be nice to do to cut down on the number of
HTTP requests and speed up page loading times.

## Technologies Used
This project was built with HTML 5 and CSS 3 using WebStorm IDE and tested on Chrome.