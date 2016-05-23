# nebraskacode2016
Five Keyhole Software employees - Chase Aucoin, Adam Costenbader, Rusty Divine, Billy Korando, and Brice McIver - presented a series of talks and workshops at the 2016 Nebraska Code Conference. We have compiled resources from those presentations in this repository. 

##Workshops
###Let's Do Microsoft Micro-Services!
####Speaker: Chase Aucoin
Full-Day Workshop, 8:00 AM Wednesday, May 18, 2016 

A full day of fun, excitement, and Micro-Services!

We will work together to understand some the Micro-Services paradigm and together we will build a high-scale, fault tolerant, production ready system. By the end of this session you will be able to confidently start bringing highly scalable, maintainable, systems to your organization.
* Understanding Business Needs and Plan Architecture
* Identify Core Dependencies
* Build Our Foundation
* Service Discovery
* Data Processing
* Real-Time Aggregation for Dashboards and Statistics
* Data Durability
* Understanding Read-Through|Write Behind
* Scaling Up
* Baking in Fault Tolerance

###Agile Requirements Workshop: Start Your Project with A Prioritized Backlog
####Speakers: Adam Costenbader, Rusty Divine, Keil Wilson (unaffiliated with Keyhole, but wonderful)
Half-Day workshop, Wednesday 1:00 PM, in Breakout D

Learn how to start your software development project off on the right foot with shared understanding and a clear path forward!

Maybe you have a startup idea, or your organization has a concept for a new software solution and now you're on the project team to build it. What's the first step? Weeks or months of business analysis to create detailed specifications? Jump in and start building?

This session takes a fresh approach to defining the task at hand. As a member of this project team, you will participate in a short and disciplined assessment process to develop a shared vision and prioritized backlog that prepares you to start building the system. Agenda (4 hours):

* Introduction to the agile requirements workshop - 20m
* Introductions and ground rules – 5m
* Break into 3 groups led by the 3 facilitators (Adam, Keil, & Rusty):
* Define the solution's objective - 20m
* List user roles and integrations - 10m
* Brainstorm the features - 90m
* Break - 10m
* Prioritize the features - 20m
* Agree on the core feature set for the minimum viable product (MVP) – 15m
* Come back together:
* Each group presents their MVP – 20m
* Discussion, Q&A, Workshop Retrospective – 30m

##One-Hour Breakout Sessions

###Azure Service Fabric: Microservice Architecture Made Ridiculously Simple
####Speaker: Chase Aucoin 
8:30 AM Thursday, May 19, 2016, in Breakout A1

CPU and RAM costs continues to plummet, Multi-Core systems are ubiquitous, writing code is easier than it has ever been. Why then, is it still so darn hard to make a scalable system?

With Service Fabric, Microsoft has provided a best-in-breed way of developing, deploying, distributing, and managing service oriented systems. We'll see how this can be applied to the micro services paradigm, as well as how you can drive immediate value into your devops processes by taking existing applications and easily migrating them to service fabric with zero code changes creating amazing horizontal scalablity. Not just in the cloud but on-premises in linux or windows.

Talk includes 2 brief demos:
* Hello world in 10 minutes or less
* Convert an existing MVC application in 10 minutes or less

###Don't Hate the HATEOAS
####Speaker: Billy Korando
9:45 AM Thursday, May 19, 2016,, in Breakout B1

Many organizations today are developing RESTful services to serve as backends for SPAs or mobile applications. REST has become an extremely popular technology because it’s lightweight, statelessness allows for easy scaling, and using the HTTP verbs allows for a level of self-documentation. This talk will cover how using HATEOAS can more your REST beyond just GETing data or allowing a user to PUT data on your server.

HATEOAS, or, Hypermedia as the Engine of Application State, allows servers to communicate the state of the application to clients keeping business logic located on the server and allowing clients to become thinner and more focused on how to present the UI to the user and not enforcing the state the application should be in.

Topics to be covered during this presentation

Principles behind REST and HATEOAS
Real world use case of HATEOAS
frameworks/tools that make the process of implementing HATEOAS easier

###Circuit Breaker: stop the fire before it happens
####Speaker: Brice McIver
2:15 PM Thursday, May 19, 2016, in Breakout A2

Have you ever had a network request fail in an application? If you have been coding web apps for more than 5 minutes, I'm guessing that your answer is yes.

This talk will focus on a fundamental pattern for protecting your system from problems commonly experienced when integrating with other systems: the Circuit Breaker pattern.

We'll talk about:
* some of the common problems enterprise applications can face, including downstream dependencies, latency, and others.
* how we can protect against some of these problems by using circuit breakers.
* a short demonstration on how you would code a circuit breaker.
* why you shouldn't code your own circuit breaker and use a well-supported third-party library instead.
* an example of using Hystrix as your circuit breaker, and more.
 
###A Guide to Effective C# Unit Testing
####Speaker: Rusty Divine
8:30 AM Friday, May 20, 2016, in Breakout B2

Come to this breakout session to learn how to write effective C# unit tests that fail when your business logic changes (not when you refactor your code), make it easy to pinpoint the failure, and give you confidence that your tests cover the scenarios that are important.

Attendees will see some non-trivial C# unit testing examples and come away with some simple guidelines and a checklist to help create effective unit tests.

###Google Chrome Dev Tools 101
####Speaker: Adam Costenbader
9:45 AM  Friday, May 20, 2016, in Breakout A2
This is an intermediate to advanced session that will not cover the basics of unit testing, but hopefully will be good information even for someone new to unit testing.

Chasing bugs in web applications can be tough but with the right tools the job can be made a lot easier. Google Chrome offers great tools to hunt, find, and test resolutions for bugs as well as for determining optimizations. Let's dive into a quick overview of what can be done with Chrome Developer tools and run through some test scenarios that happen day to day with web application development.

###Information: ASP MVC/Web API Model Validation with FluentValidations
####Speaker: Adam Costenbader
11:00 AM Friday, May 20, 2016, in Breakout A3

DataAnnotations are great for quick simple validations or mostly matching the model to the structure needed to fit into the database but what do we do if we have more complex business rules we want picked up in the ModelState checks? Enter FluentValidation.

FluentValidation is a 3rd party Nuget package that allows for the creation of easily testable validator classes that can tap into the ModelState checks performed by ASPI MVC/Web API. In this session we'll review:

* When should we use DataAnnotations and when should we use FluentValidations
* How to create simple to complex FluentValidations
* How to Unit Test FluentValidation validators
* Review using IoC with FluentValidations and why we'd need this
* NOTE: This session assumes you are familiar with ASP MVC / Web API, DataAnnotations, and model state checking
