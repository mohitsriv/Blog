---
layout: post
title: New Tech, New Content 
description: "New tech and new content"
modified: 2015-12-18
category: 
tags: [hosted software, jekyll, microsoft azure]
imagefeature:
comments: true
share: true
excerpt_separator: <!--more-->
excerpt_image: new-tech-jekyll-azure.png
---
Lots has happened in the **six** years since the last post. The industry has evolved. I've grown. 
That means I read some of my old posts and cringe a lot. I'm still happy though I went through the exercise of
blogging, taking out some time to reflect on topics that were top of mind then. So, I'm going to try to pick up the habit again 
but not set a hard post/week commitment either. <!--more-->

# Updated blog engine

![JekyllAzure]({{ site.baseurl }}/images/new-tech-jekyll-azure.png) 

As part of taking the blog out of hibernation, I updated the technology that powers this blog. A goal was to use at least some technologies I am less familiar with. I've migrated the blog engine from WordPress + MySQL to [Jekyll](https://jekyllrb.com/) hosted on [Microsoft Azure App Service](https://azure.microsoft.com/en-us/services/app-service/). I author my
posts in Markdown, mostly using Visual Studio Code as my editor. I then push the posts to [GitHub](http://github.com/mohitsriv/Blog). Finally, I have setup [Travis CI](https://travis-ci.org/) to automatically test, build and publish to Azure from GitHub when a commit is detected. I am satisfied
with the workflow and plan to share the details in an upcoming post. 

# Content changes

While the topics I'll blog about are largely the same, here are some changes (industry and personal) that will be reflected in upcoming content and hopefully make it less cringeworthy.

- Program Management (although IMHO it should just be called **Product Management** now) as a discipline **has evolved at Microsoft**, with greater emphasis on [customer development](http://www.amazon.com/Lean-Customer-Development-Building-Customers/dp/1449356354), business impact, sophisticated data-driven decision making, and agile service-oriented "hypothesize-test-repeat" delivery.  
- I've grown as a product manager through running a number of product management teams delivering web and 
cloud development products – services, tools and SDKs. I also have a richer business toolchain and context after completing an MBA.
- **SaaS adoption** -- both consumer and enterprise -- **has continued to accelerate**. Enterprise SaaS **purchasing** decisions are often **decentralized** and agile without IT involvement. These trends mean that **SaaS integration** is an increasingly critical part of building enterprise services and solutions in the cloud.
- **Building software is in some ways easier and some ways harder**. 
  - Easier: PaaS has moved further "up the stack" with offerings
such as Microsoft Azure App Service and Heroku. A number of development frameworks -- e.g. jQuery, Bootstrap & Angular on
the client and API Management & ASP.NET Web API on the server -- have emerged to make it much easier to target different devices and form factors.
  - Harder: There is an expectation that sotware targets a variety of form factor and devices. With IoT, the
volume of data has increased exponentially. And, there is a much higher standard for usability and aesthetics, even
in enterprise software.
- I've become a better developer and am fortunate that I can dive deep into Web and cloud development both in my job and personal time.   
