---
layout: page
title: "about"
date: 2014-02-17 17:28
comments: false
sharing: false
footer: true
---

<img style="float: right; border-radius: 125px; margin-left: 20px; margin-left: 1rem; width: 240px;" src="http://www.gravatar.com/avatar/3b8eb0fbda380a377f6c685fcc091c1c.jpg?s=240" alt="portrait" />

<b>Hi.</b> My name is Ümit Seren. I have been working as a software engineer and computer scientist in a wide range of fields (business & science) for over 10 years.
 
Currently I am a software developer/computer scientist at the [Gregor Mendel Institute (GMI)](http://gmi.oeaw.ac.at) working on scientific (web-)applications, data analysis and visualizations. 

[StackOverflow](http://stackoverflow.com/users/356594/mit) &middot; [GitHub](https://github.com/timeu)

<h1>History</h1>

The first time I started to look into computers beyond just playing games, was around the age of 14 when I tried to get some DOS games to run by loading device drivers into highmem and playing around with QEMM. 

My first steps into the field of programming was with 15, when I tried to code my first applications in Basic and Turbo Pascal. 
My first real project was a GUI in Visual Basic for some data analysis in the field of geophysics for the [ZAMG](http://zamg.ac.at)

In the course of my university curriculum I programmed in C/C++ and Java. I had an internship in a company that was primarily using C# and Microsoft .NET for web-development. My master thesis was about ORM frameworks and I ended up implementing one in C# and .NET. 
After graduating from university I had to do my community service in the [Archives of the Concentration Camp of Mauthausen](http://www.mauthausen-memorial.at/). 
Our job there was to manually process information inquiries and requests. There was potential for automating some tasks of this process and so I decided to develop a MS Access Database Application that interacted with Microsoft Word in order to minimize the amount of manual repetitive work for the users.
 
My first real project (that I was paid for) was a full stack CRM web-application for a big hosting provider. It was developed in PHP and MySQL. I had to do a lot of system integration (automatically creating web-space and databases for new customer, integration with other services, payment processing, etc). I also ended up developing my own ORM called ObjectBag. Back then there was no real solid ORM in PHP or at least I wasn't aware of any (I feel sorry for the developer who has to maintain ObjectBag now ;-))

After 6 years of maintainng and extending the CRM and working on a couple of different projects (Migration of VB to VB.NET) I switched into the field of science, specifically bioinformatics. 
This was more an "accident" than a deliberate decision. 
The [Gregor Mendel Institute (GMI)](http://gmi.oeaw.ac.at) was looking for a computer scientist/software developer (someone inbetween a bioinformatician and traditional software developer) and I ended up to be that guy.

I took over a web-application that was developed with [Pylons](http://www.pylonsproject.org/) (Python) and [Elixir](http://elixir.ematia.de/trac/wiki)/[SQLAlchemy](http://www.sqlalchemy.org/) for the backend and [Google Web Toolkit](http://www.gwtproject.org/) (Java/Javascript) for the frontend. I got quickly interested in scientific visualizations and data analysis. I was looking into ways to improve the visualizing and processing of biological information. I tried to improve the performance of [scipy/numpy](http://stackoverflow.com/questions/5260068/multithreaded-blas-in-python-numpy/7645939#7645939) scripts on our HPC cluster and looked into HTML5 Canvas to efficiently visualize huge amounts of data points in the browser. 

Together with [Bjarni Vilhjalmsson](http://www.linkedin.com/pub/bjarni-vilhjalmsson/10/a38/163) we developed a Python web-application that allowed biologists to run [Genome Wide Association Studies](http://en.wikipedia.org/wiki/Genome-wide_association_study) and display the results in the web-browser (GWAPP). It was published in [Plant Cell](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC3556958/).

Currently I am working on the successor of GWAPP that allows users to compare different studies with each other and to share information with other people. It's a full stack web-application that uses a [Spring](http://spring.io/) (Java) backend and GWT on the frontend. It has integration with our HPC cluster using [RabbitMQ](https://www.rabbitmq.com/) message broker, numpy/scipy (Python) for data-analysis and [Elasticsearch](http://www.elasticsearch.com/) for fulltext search. The data is stored in a [PostgreSQL](http://www.postgresql.org/) database and [HDF5](http://www.hdfgroup.org/HDF5/) files. 






