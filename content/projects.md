+++
title = "Projects"
description = "The semi-professional website of Dan Decker, Data and Business Intelligence Professional"
date = "2022-03-31"
aliases = ["projects"]
author = "Dan Decker"
+++

1. [US Covid-19 Tracking](https://github.com/therealdandecker/COV19Tracking)
* When the pandemic first hit there was actually not as much data around tracking COVID-10 so early on I wrote a web-scraper to gather some information and track it.  
* The scraper used Beautiful Soup to scrape HTML data from a web page and land it in SQL (Microsoft SQL Server)

2. [MS SQL - Python - PYODBC Container](https://github.com/therealdandecker/PySQLBase/)
* Periodically as a 'data person' you need to build or re-create an environment to work with SQL and Python.  
* Working in a Microsoft shop and some of the Python documentation being what it is, until recently it was hard to figure out exactly how to scale out the right set-up.  
* I wrote a Dockerfile for a custom container image that gets the dependencies for Python, MS ODBC 18, Pyodbc, and SQL Alchemy ORM so that there is always a stable start point.  
* This is updated periodically, just copy the docker file or curl the repo if you wish to use


