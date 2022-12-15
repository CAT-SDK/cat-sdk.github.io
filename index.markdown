---
title: Tools For Code Analysis and Mining
layout: default
---

Our source code repositories hold tremendous amounts of data on our development process.  They can provide valuable insights into development styles and methods that can increase our awareness of techniques, important developments in open source, and potential collaborators.  These can ultimately help us find ways to increase or understand what makes us most productive.

The Code Analysis and mining Tools Software Development Toolkit (CAT-SDK) provides methods for utilizing your repositories to generate summaries and suggestions for improving developer productivity and overall development experience.

These tools can find aspects of source code repos, but are not comprehensive.  This means they will not be useful for creating comparative metrics.  Instead, the tools' outputs are best for identifying unique defining characteristics, insights, and ideas of source code projects and their teams.  Some trends, like lines of code or commits over time, are helpful for creating an overall impression of a project - but these same outputs can be subject to systematic errors if some part of the project is not captured correctly in a repository or identified correctly by the tools.  For this reason, the tools work best when used by the project teams themselves.

The tools and resources below are available in release 1.0:

## [GremCat](https://github.com/CAT-SDK/GremCat)

![GremCat]({{site.url}}/assets/images/GremCat.png)

The collection of packages in this repository are developed as part of the DOE [IDEAS-ECP](https://ideas-productivity.org/) project on high-performance software development productivity. The GremCat set of tools is part of the larger [CAT-SDK](https://github.com/CAT-SDK) collection of git and related data mining and analysis software infrastructure. One of the important tools in GremCat is MeerCat, A Pull-Request Assistant.

![MeerCat]({{site.url}}/assets/images/MeerCat.png)

MeerCat attempts to alleviate some of the burden of those doing formal reviews of Pull Requests (PRs). It has tool support to check that documentation standards are being met, that testing is being kept up to date, that code quality standards are being met, and that important voices are brought into the discussion. It not only flags problems, it offers tool support to the PR author to fix those problems before they get to the review stage. To learn more about MeerCat, and how your project can be added to the MeerCat site, please contact Stephen Fickas (stephenfickas@gmail.com).

## [rateyourproject.org](https://rateyourproject.org)

![RateYourProject]({{site.url}}/assets/images/RYP.png)

Software engineering is a systematic approach to the design, development, and maintenance of a software system. Teams seldom have the time to stop development and focus solely on improving productivity or sustainability. However, teams can incorporate improvements on the way to developing new science capabilities.
The tools on this site will help you:

 - Assess your current practices
 - Create progress tracking cards
 - Integrate tracking cards with your workflow

The self-assessment introduces software engineering practices that increase in maturity. Check the practices that your project already uses to rate your project.


## [repometer](https://github.com/sandialabs/repometer)

![Repometer]({{site.url}}/assets/images/Repometer.png)

Online version control platforms offer insights into traffic and engagement with source code repositories, but only in limited ways and over short windows of time. Scientific software teams at Sandia and elsewhere want to collect and store engagement data to help tell their story and the impact their work has on the community. [Repometer](https://github.com/sandialabs/repometer) aims to supplement existing capabilities by collecting timely and insightful data from GitHub and GitLab repositories and passing it to a database for longer-term storage.

## [reposcanner](https://github.com/bssw-psip/reposcanner)

![Reposcanner]({{site.url}}/assets/images/Reposcanner.png)

Reposcanner provides a highly modular, extensible framework for defining routines for mining data from software repositories and performing analyses on that data to yield valuable insights on team behaviors. [Reposcanner](https://github.com/bssw-psip/reposcanner) provides a number of attractive features not normally seen in repository mining research codes, such as seamless support for different version control platforms like GitHub, Gitlab, and Bitbucket, smart parsing of URLs, intelligent credential management capabilities, and a comprehensive test suite.

## [PTC Catalog](https://github.com/bssw-psip/PTC-Catalog)

![PSIP]({{site.url}}/assets/images/PSIP.png)

The Progress Tracking Card (PTC) Catalog is a resource intended to provide ease-of-use and reusability of previously created PTCs. Within this site, you can find PTCs that can help you to practice better development, planning, performance, reliability, and collaboration on your scientific software projects.

The catalog can be accessed both in alphabetical and categorized formats. We encourage you to incorporate your card directly into your project's software repository.

 
## [PSIP Practice Guides](https://bssw-psip.github.io/practice-guides/)

![PSIP]({{site.url}}/assets/images/PSIP.png)

The Productivity and Sustainability Improvement Planning (PSIP) Practice Guides are resources intended to help new users get started with PSIP.
These guides include information on when and why to practice PSIP, how to kick off the process, how to set goals, and more.
If you are brand-new to PSIP, we recommend you begin with [Why practice PSIP?](https://bssw-psip.github.io/practice-guides/pages/why_practice_PSIP.html) to learn more about it and what it can do for your scientific software development team. Learn more about how to apply it by going through the following steps (as see below in the contents).

