---
layout: post
title: Importing CSV into database
date: 2018-08-06 12:00
categories: project
---

Today, I imported Chris' CSV into the database. How I imported was a bit tricky because he gave me a heavy-sized ones with a few errors. When I tried importing it, the first error I noticed was when a few rows had multiple columns than the required sections (screenshot below). For now I'm going to import a CSV containing 2000 articles and test them out before I import the rest, another error is that some rows had blank columns so I resolved it by adding an if statement to exclude all rows containing them. I also managed to imported the date of each article by reading from the Python website as the date for SQL requires the stricture of YYYY-MM-DD.

David also wanted me to visualize the most common words from one year and compare them for another, this would include a very long query and I reckon that it would work once I find information on what to do. He also want's me to learn about importing CSV files using delimiters on Python to resolve these errors.

<img src="{{ site.baseurl }}/assets/img/csverror.PNG" alt="image not found" width="100%">

<a href="https://sqlchoice.azurewebsites.net/en-us/sql-server/developer-get-started/python/windows/step/2.html">Inserting data to SQL server using Python - Step 2.3</a>
<br>
<a href="https://docs.python.org/2/library/csv.html">CSV parsing</a>
<br>
<a href="https://docs.python.org/3.4/library/datetime.html">Converting date string to SQL format</a>