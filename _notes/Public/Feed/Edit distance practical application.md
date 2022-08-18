---
title : Edit distance practical application
feed: show
date: 18-08-2022
---

When was the last time you had a direct implementation for an algorithm?

At work today we needed to filter out malformed email domains from a list of 4.2 Million email ids.
e.g gnail.com instead of gmail.com 

Looking at the problem, it just occurred to me 
Oh this can be done using -  [Levenshtein distance](https://pypi.org/project/editdistance/0.3.1/) (edit distance) 

I decided to use [pandas.py](https://pandas.pydata.org/) as it provided some high level constructs for manipulating csv.
Also found this simple package implementing editdistance:  [editdistance · PyPI](https://pypi.org/project/editdistance/0.3.1/)

In less than an hour, i hacked a script together using and we processed the 4.2M email ids to get 1342 email domains along with count of email ids using such domains.





<blockquote class="twitter-tweet"><p lang="en" dir="ltr">When was the last time you had a direct implementation for an algorithm?<br>At work today we needed to filter out malformed email domains from a list of 4.2 Million email ids.<br>e.g <a href="https://t.co/CtHbFCEc0w">https://t.co/CtHbFCEc0w</a> vs <a href="https://t.co/R8Qi3DgZCD">https://t.co/R8Qi3DgZCD</a>, <a href="https://t.co/dIpqGlmaOm">https://t.co/dIpqGlmaOm</a> vs <a href="https://t.co/9SJSZ7sdRT">https://t.co/9SJSZ7sdRT</a></p>&mdash; Shubham Sethi (@suave_sethi) <a href="https://twitter.com/suave_sethi/status/1559525125388509185?ref_src=twsrc%5Etfw">August 16, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>


