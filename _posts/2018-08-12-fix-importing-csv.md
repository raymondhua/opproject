---
layout: post
title: Success Importing
date: 2018-08-12 12:00
categories: project2
---

I managed to fixed these problems by replacing the invalid date strings by adding a 0 in front of the single digit dates (e.g Jan. 1, 1999 would become Jan. 01, 1999)

<img src="{{ site.baseurl }}/assets/img/week2/singleDigit.PNG" alt="image not found" width="100%">

I also fixed the invalid string dates by replacing the invalid (shortened) months (e.g. Jan, Feb, Aug....) with full names of the months (e.g. January....)

<img src="{{ site.baseurl }}/assets/img/week2/monthReplacement.PNG" alt="image not found" width="100%">

I was struggling on how to fix these errors at first because it took a lot of time to understand the CSV, my next challenge is to minimize the use of code duplication.

These errors are very easy to fix

Stackoverflow resources
<a href="https://stackoverflow.com/questions/10037742/replace-part-of-a-string-in-python">Python substring replace</a>
<br>
<a href="https://stackoverflow.com/questions/3437059/does-python-have-a-string-contains-substring-method">Python substring replace</a>