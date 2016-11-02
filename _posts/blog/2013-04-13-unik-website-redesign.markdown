---
layout: post
title: Unik - Website redesign
categories: blog
excerpt: Unik launched today a redesign of it new website including a total revamp of the technology behind, we moved from Drupal to a CMS free approach using Jekyll.
authorname: Ismail Mechbal
authornickname: The boss
authorcity: Casablanca & Stockholm
authorphone: +212 600 828 689
authoremail: ismail@unik.ma
googleauthor: https://plus.google.com/110158564608845019382
---

[Unik](http://unik.ma/ "Unik") launched today a redesign of it new website including a total revamp of the technology behind, we moved from [Drupal](http://drupal.org/ "Drupal") to a CMS free approach using [Jekyll](https://github.com/mojombo/jekyll/ "Jekyll").

>Jekyll is a simple, blog aware, static site generator. It takes a template directory (representing the raw form of a website), runs it through Textile or Markdown and Liquid converters, and spits out a complete, static website suitable for serving with Apache or your favorite web server.


This short article will describe the process and tools used for the redesign of our website.

#### **1. Agile project management (Kanban method)**
[Jira](http://www.atlassian.com/software/jira/overview/ "Atlassian Jira"), Jira is used heavily in every project, it allows us to collaborate easily using less emails and meetings, in overall it makes our work much faster and very organised.
Here is a screenshot of some interaction between our team members.

![Unik Atlassian Jira expert in morocco](../../images/blog/unik-creation-site-maroc-redesign-jira-maroc-1.jpg "Unik Atlassian Jira expert in morocco")

The first picture is a general description of the tasks, it status and the attachments; while the next picture shows a typical interaction between our team members using the comments feature.

![Unik Atlassian Jira expert in morocco](../../images/blog/unik-creation-site-maroc-redesign-jira-maroc-2.jpg "Unik Atlassian Jira expert in morocco")

#### **2. Frontend development**
Frontend UI development using [Bootstrap](http://twitter.github.io/bootstrap/ "Bootstrap") and [Sass](http://sass-lang.com/ "Sass")

![Unik creation site maroc](../../images/blog/unik-creation-site-maroc-redesign-SASS-maroc-3.jpg "Unik creation site maroc")

#### **3. Backend development**
Backend development is as we mentioned earlier is done through a CMS Free approach using Jekyll; in order to use Sass and [Coffeescript](http://coffeescript.org "coffeescript") we had to work with [Jekyll AssetsPlugin](https://github.com/ixti/jekyll-assets "Jekyll AssetsPlugin")


#### **4. Versioning**
For the versioning, we use [Bitbucket](http://bitbucket.org "Bitbucket") as it interact smoothly with Jira.
Bitbucket allows you to choose between GIT and Mercurial, we're not sorry that we choose GIT over SVN.

![Unik creation site maroc](../../images/blog/unik-creation-site-maroc-redesign-git-bitbucket-maroc-4.jpg "Unik creation site maroc")


Finally this is only a snapshot of the processes and technology we have used, a more detailed explanation will come later.
