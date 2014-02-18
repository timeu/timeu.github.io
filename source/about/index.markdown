---
layout: page
title: "about"
date: 2014-02-17 17:28
comments: false
sharing: false
footer: true
---

<img style="float: right; border-radius: 125px; margin-left: 20px; margin-left: 1rem; width: 240px;" src="http://www.gravatar.com/avatar/3b8eb0fbda380a377f6c685fcc091c1c.jpg?s=240" alt="portrait" />

<b>Hi.</b> My name is Ümit Seren. I've been working as a software engineer and computer scientist for over 10 years in a wide range of fields from business to scientific applications.
 
Currently I am a software developer/computer scientist at the [Gregor Mendel Institute (GMI)](http://gmi.oeaw.ac.at) working on scientific (web-)applications, scientific data analysis and visualizations. 

[StackOverflow](http://stackoverflow.com/users/356594/mit) &middot; [GitHub](https://github.com/timeu)

<h1>History</h1>

The first time I started to look into computers beyond just playing games was around the age of 14 when I tried to get some DOS games to run by loading device drivers into highmem and playing around with QEMM. 

My first steps into the field of programming was with 15 when I started to play around with Basic and Turbo Pascal. 
My first real project was to develop a GUI in Visual Basic for some data analysis in the field of geophysics for the [ZAMG](http://zamg.ac.at)

In the course of my university curriculum I programmed in C/C++ and Java. I had an internship in a company that was mainly using C# and Microsoft .NET for web-development. My master thesis was about ORM frameworks and I ended up implementing one in C# and .NET. 
After finishing university I had to do my community services in the [Archives of the Concentration Camp of Mauthausen](http://www.mauthausen-memorial.at/). 
We had to manually process a lof of inquiries. There was some potential for automating some tasks so I decided to develop a MS Access Database Application that interacted with Microsoft Word to solve some of these problems. 
 
My first real project (for which I was paid) was a full stack CRM web-application for a big hosting provider. It was developed in PHP. There was a lot of system integration involved (automatically creating web-space and databases for new customer, integration with other services, payment processing, etc). I ended up developing my own ORM called ObjectBag. Back then there was no real solid ORM in PHP or at least I wasn't aware of it (I feel sorry for the developer who has to maintain ObjectBag now ;-))

After 6 years of maintainng and extending the CRM and working on a couple of different projects (Migration of VB to VB.NET) I switched into the field of science, specifically bioinformatics. 
This was more an "accident" than a deliberate decision. 
The [Gregor Mendel Institute (GMI)](http://gmi.oeaw.ac.at) was looking for a computer scientist/software developer (something inbetween a bioinformatician and traditional software developer) and I ended up to be this guy. 

I took over a web-application that was developed with [Pylons](http://www.pylonsproject.org/) (Python) and [Elixir](http://elixir.ematia.de/trac/wiki)/[SQLAlchemy](http://www.sqlalchemy.org/) for the backend and [Google Web Toolkit](http://www.gwtproject.org/) (Java/Javascript) for the frontend. I got quickly interested in scientific visualizations and data analysis. I was looking into ways to improve visualizing and processing biological information. I tried to improve the performance of [scipy/numpy](http://stackoverflow.com/questions/5260068/multithreaded-blas-in-python-numpy/7645939#7645939) scripts on our HPC cluster and looked into HTML5 Canvas to efficiently visualize huge amounts of data points in the browser. 

Together with [Bjarni Vilhjalmsson](http://www.linkedin.com/pub/bjarni-vilhjalmsson/10/a38/163) we developed a Python web-application that allowed biologist to run [Genome Wide Association Studies](http://en.wikipedia.org/wiki/Genome-wide_association_study) and display the results in the browser (GWAPP). It was published in [Plant Cell](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3556958/).

Currently I am working on the successor of this GWAPP that allows to compare different studies together and users to share information with other users. It's a full stack web-application that uses a [Spring](http://spring.io/) (Java) backend and GWT on the frontend. It has integration with our HPC cluster using [RabbitMQ](https://www.rabbitmq.com/) message broker, numpy/scipy (Python) for data-analysis and [Elasticsearch](http://www.elasticsearch.com/) for fulltext search. The data is stored in a [PostgreSQL](http://www.postgresql.org/) database and [HDF5](http://www.hdfgroup.org/HDF5/) files. 






