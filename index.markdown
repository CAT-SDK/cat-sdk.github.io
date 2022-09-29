---
title: Tools For Code Analysis and Mining
layout: default
---


Our source code repositories hold tremendous amounts of data on our development process.  They can provide valuable insights into development styles and methods that can increase our awareness of techniques, important developments in open source, and potential collaborators.  These can ultimately help us find ways to increase or understand what makes us most productive.

This toolkit provides methods for utilizing your repositories to generate summaries and suggestions for improving developer productivity and overall development experience.

These tools can find aspects of source code repos, but are not comprehensive.  This means they will not be useful for creating comparative metrics.  Instead, the tools’ outputs are best for identifying unique defining characteristics, insights, and ideas of source code projects and their teams.  Some trends, like lines of code or commits over time, are helpful for creating an overall impression of a project - but these same outputs can be subject to systematic errors if some part of the project is not captured correctly in a repository or identified correctly by the tools.  For this reason, the tools work best when used by the project teams themselves.

Five separate tools/resources are available:

## [GremCat](https://github.com/CAT-SDK/GremCat)

![GremCat]({{site.url}}/assets/images/GremCat.png)

## [rateyourproject.org](https://rateyourproject.org)

![RateYourProject]({{site.url}}/assets/images/RYP.png)

Software engineering is a systematic approach to the design, development, and maintenance of a software system. Teams seldom have the time to stop development and focus solely on improving productivity or sustainability. However, teams can incorporate improvements on the way to developing new science capabilities.
The tools on this site will help you:
Assess your current practices
Create progress tracking cards
Integrate tracking cards with your workflow
The self-assessment introduces software engineering practices that increase in maturity. Check the practices that your project already uses to rate your project.


## [repometer](https://github.com/sandialabs/repometer)

![Repometer]({{site.url}}/assets/images/Repometer.png)

Online version control platforms offer insights into traffic and engagement with source code repositories, but only in limited ways and over short windows of time. Scientific software teams at Sandia and elsewhere want to collect and store engagement data to help tell their story and the impact their work has on the community. Repometer aims to supplement existing capabilities by collecting timely and insightful data from GitHub and GitLab repositories and passing it to a database for longer-term storage.

## [reposcanner](https://github.com/bssw-psip/reposcanner)

![Reposcanner]({{site.url}}/assets/images/Reposcanner.png)

Reposcanner provides a highly modular, extensible framework for defining routines for mining data from software repositories and performing analyses on that data to yield valuable insights on team behaviors. Reposcanner provides a number of attractive features not normally seen in repository mining research codes, such as seamless support for different version control platforms like GitHub, Gitlab, and Bitbucket, smart parsing of URLs, intelligent credential management capabilities, and a comprehensive test suite.

## [PTC Catalog](https://github.com/bssw-psip/PTC-Catalog)

![PSIP]({{site.url}}/assets/images/PSIP.png)

The Progress Tracking Card (PTC) Catalog is a resource intended to provide ease-of-use and reusability of previously created PTCs. Within this site, you can find PTCs that can help you to practice better development, planning, performance, reliability, and collaboration on your scientific software projects.
The catalog can be accessed both in alphabetical and categorized formats. We encourage you to incorporate your card directly into your project's software repository.
