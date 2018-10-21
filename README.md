## Table of Contents

* [Installation](#installation)
* [Project Overview](#project-overview)
* [Acknowledgments](#acknowledgments)

## Installation

1. Download or clone repository.

2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

# Project Overview

For the Restaurant Reviews projects, we will incrementally convert a static webpage to a mobile-ready web application. In Stage One, we will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. We will also begin converting this to a Progressive Web Application by caching some assets for offline use.

Note: using Google API key.

## Acknowledgments

* [Matthew Cranford's Tutorial](https://matthewcranford.com/category/blog-posts/walkthrough/restaurant-reviews-app/)
* [Kevin Ngo's Simple Service Worker Reference](http://supermedium.strikingly.com/blog/service-workers)
* [Dan Fabulich's How to Fix the Refresh Button When Using Service Workers](https://redfin.engineering/how-to-fix-the-refresh-button-when-using-service-workers-a8e27af6df68)
* Helpful Udacity program and team
