---
layout: post
title: Panama Papers, Cybersecurity Fails, & The Very Definition of Insanity
date: 2016-04-12 13:14:52.000000000 -04:00
---
This is unfortunately how we view the current state of CyberSecurity programs and initiatives. The latest security breach at [Mossack Fonseca](http://www.wired.co.uk/news/archive/2016-04/06/panama-papers-mossack-fonseca-website-security-problems), which was due to a mis-configuration that resulted in a [SQL injection](https://www.owasp.org/index.php/SQL_Injection) vulnerability being exposed and exploited, reinforces that assertion.

![](http://www.informationsecuritybuzz.com/wp-content/uploads/SQL_Injection.jpg)

SQL Injection vulnerabilities have been in the OWASP Top 10 since the project started. It seems intuitively obvious to us at Cybric that current, passive approaches to security vulnerability detection are falling further and further behind, though somehow we all continue to expect different results.

The same disparate set of point solution tools and Open-Source projects that are deployed at literally every large Enterprise across the globe, are typically what hackers are using to gain unauthorized access via vulnerabilities, so what is the difference? 

It really comes down to Passive versus Active and Aggressive stances. Hackers don’t care about wreaking havoc against your production application infrastructure, so they launch these tools in “active mode” with the most aggressive command-line arguments possible. Enterprises, on the other hand, typically only execute passive scans during off-hours on a weekly, monthly, or quarterly basis, not in a continuous mode.

What we are developing at Cybric is a **Continuous Security Delivery Fabric** that will allow Enterprises to integrate security into the entire software development, delivery, and deployment lifecycle, and perform inline, aggressive vulnerability scans so we can help CISOs and DevOps teams across the globe “Stop The Insanity!”
