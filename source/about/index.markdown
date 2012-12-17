---
layout: page
title: "about"
date: 2012-12-04 12:36
comments: false
sharing: false
footer: false
---
<img src="images/crawljax-logo.jpg" width="150px" style="float:left;margin:0 10px 0 0;">Crawljax is an open source Java tool for automatically crawling and testing modern web applications.
Crawljax can explore any JavaScript-based Ajax web application through an even-driven dynamic crawling engine. It automatically creates a state-flow graph of the dynamic DOM states and the event-based transitions between them. This inferred state-flow graph forms a very powerful vehicle for automating many types of web analysis and testing techniques:

* Test generation 
* Invariant-based testing 
* Non functional testing (Accessibility, validation, I18n, security, …)
* Detecting broken links/images/tooltips
* Detecting unused code, and much more...

Crawljax can easily be extended through its easy-to-use <a href="https://github.com/crawljax/crawljax/wiki/Writing-a-plugin">plugin architecture</a>.


## History
The idea of crawling Ajax-based web applications started in 2007 as part of the PhD research of [Ali Mesbah](http://ece.ubc.ca/~amesbah/) working with [Arie van Deursen](http://www.st.ewi.tudelft.nl/~arie/).
The initial idea, written in a technical report titled [Exposing the Hidden-Web Induced by Ajax](http://swerl.tudelft.nl/twiki/pub/Main/TechnicalReports/TUD-SERG-2008-001.pdf), was to automatically generate a static linked mirror of the dynamic DOM states, to make the web application accessible to search engines.
Later in 2008, the event-based crawling technique was [published at ICWE’08](http://swerl.tudelft.nl/twiki/pub/Main/TechnicalReports/TUD-SERG-2008-022.pdf) and many applications for Crawljax began to emerge. Extending and using Crawljax for automatically testing modern Web 2.0 applications through structural DOM invariants was the next step, which resulted in an [ICSE’09](http://swerl.tudelft.nl/twiki/pub/Main/TechnicalReports/TUD-SERG-2009-005.pdf) paper. Furthermore, we have been using Crawljax for security testing ([ESEC/FSE’09](http://swerl.tudelft.nl/twiki/pub/Main/TechnicalReports/TUD-SERG-2009-011.pdf)), regression testing ([ICST’10](http://swerl.tudelft.nl/twiki/pub/Main/TechnicalReports/TUD-SERG-2009-028.pdf)), cross-browser compatibility testing ([ICSE’11](http://2011.icse-conferences.org/research-papers)) and many other interesting domains of web analysis and testing.

## General support and technical discussion

If you encounter any problems or have questions, don’t hesitate to use our mailing list, which can be found at:

[http://groups.google.com/group/crawljax](http://groups.google.com/group/crawljax)

## Bug Tracker

If you find bugs or would like to propose a new feature, you can open an issue in our bug tracker, which can be found at:

[https://github.com/crawljax/crawljax/issues](https://github.com/crawljax/crawljax/issues)

