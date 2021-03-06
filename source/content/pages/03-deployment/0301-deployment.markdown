title: Deployment
category: page
slug: deployment
sort-order: 031
choice1url: /servers.html
choice1icon: fa-sort-amount-asc fa-inverse
choice1text: Show me options for bare metal, virtualized servers, and infrastructure-as-a-service.
choice2url: /platform-as-a-service.html
choice2icon: fa-puzzle-piece fa-inverse
choice2text: How do I use a platform-as-a-service to deploy my Python web app?
choice3url: /web-frameworks.html
choice3icon: fa-code fa-inverse
choice3text: I'm not yet ready to deploy. Show me web frameworks I should use to create an app.
choice4url:
choice4icon:
choice4text:


# Deployment
Deployment involves packaging up your web application and putting it in a 
production environment that can run the app.


## Why is deployment necessary?
Your web application must live somewhere other than your own desktop or 
laptop. A production environment is the canonical version of your current 
application and its associated data.


## Deployment hosting options
There are four options for deploying and hosting a web application:

1. ["Bare metal" servers](/servers.html)

2. [Virtualized servers](/servers.html)

3. [Infrastructure-as-a-service](/servers.html)

4. [Platform-as-a-service](/platform-as-a-service.html)

The first three options are similar. The deployer needs to provision one or
more servers with a Linux distribution. System packages, a web server, 
WSGI server, database and the Python environment are then installed. Finally
the application can be pulled from source and installed in the environment.

Note that there are other ways of installing a Python web application through
system-specific package management systems. We won't cover those in this
guide as they are considered advanced deployment techniques.


## Deployment learning checklist
<i class="fa fa-check-square-o"></i>
If you're tight on time look at the 
[platform-as-a-service (PaaS)](/platform-as-a-service.html) options. You can
deploy a low traffic project web app for free or low cost. You won't have to
worry about setting up the operating system and web server compared to going
the traditional server route. In theory you should be able to get your 
application live on the web sooner with PaaS hosting.

<i class="fa fa-check-square-o"></i>
[Traditional server options](/servers.html) are your best bet for learning
how the entire Python web stack works. You'll often save money with a virtual
private server instead of a platform-as-a-service as you scale up.

<i class="fa fa-check-square-o"></i>
Read about servers, [operating systems](/operating-systems.html), 
[web servers](/web-servers.html) and [WSGI servers](/wsgi-servers.html) to get
a broad picture of what components need to be set up to run a Python web 
application.


## Deployment resources
* [Thoughts on web application deployment](http://omniti.com/seeds/thoughts-on-web-application-deployment)
  walks through stages of deployment with source control, planning, 
  continuous deployment and monitoring the results.

* [Practical continuous deployment](http://blogs.atlassian.com/2014/04/practical-continuous-deployment/)
  defines delivery versus deployment and walks through a continuous deployment
  workflow.


### How would you like to deploy your web app?
