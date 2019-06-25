# Mobile Web Specialist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Specification

You have been provided the code for a restaurant reviews website. The code has a lot of issues. It’s barely usable on a desktop browser, much less a mobile device. It also doesn’t include any standard accessibility features, and it doesn’t work offline at all. Your job is to update the code to resolve these issues while still maintaining the included functionality.

### Project Rubric

Your project will be evaluated by a Udacity code reviewer according to the [Restaurant Reviews project rubric](https://review.udacity.com/#!/rubrics/1090/view). Please review for detailed project requirements. The rubric should be a resource you refer to periodically to make sure your project meets specifications.

### What do I do from here?

1. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

    * In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. Explore the provided code, and start making a plan to implement the required features in three areas: responsive design, accessibility and offline use.
4. Write code to implement the updates to get this site on its way to being a mobile-ready website.

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
## STEPS TAKEN TO COMPLETE THE TASK
+ To load map, I used JavaScript token from `mapBox`.
+ And also added link in index.html, restaurant.html to connect with `mapBox`.
## Changes Made in index.html
+ Added a Meta Tag to display website responsive using viewport.
+ I had removed height property from filter-options and added padding property for it in style.css.
+ Checked accessibility and made some changes to get maximum accessibility, to minimize issues like color contrast and labes for form controls.
+ I also did some change in colors of the website, so that its attractive along with responsive.
## Changes made in restaurant.html
+ For the section restaurant-container, I edited it to two sub divisions, so that it can place aside.
+ For the review-container, added some CSS styles so that it is displayed attractively.
+ Added a Meta Tag to display website responsive using viewport.
+ I registered Service-worker in index.html by using <script> tags and given path of `serviceWorker` ( sw.js ).
+ Created `manifest.json` file with few properties and also compressed images with `flexable` sizes. Included the images paths in `manifest.json` file.
+ I had manipulated the code in dbhelper.js to work with any server. Committed the `url` with port and assigned direct path,
**NOTE** : I run this project using PYTHON SERVER, we can also run this project using 200 OK server, for that we need to implement some changes in dbhelper.js.

**NOTE** : This webpages is responsive for DESKTOP, MOBILE, Tablet Mode.
## Feeling at the end of project.
+ This project help me to learn `serviceWorker` concept, which is very helpful for us to run a application
+ I am really amazed of the how the working of project, so that I get to know the real world application usage of products.
+ I am very thankful to **UDACITY TEAM**, for giving me this opportunity to learn this challenging platform.
