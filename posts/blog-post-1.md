---
layout: post-layout.njk 
title: How I did my first site on 11ty
date: 2019-05-30
tags: ['post']
---
This is the first website that I created from scratch with help of 11ty. This site is mostly based from this guide [Creating Blog with Eleventy](https://keepinguptodate.com/pages/2019/06/creating-blog-with-eleventy/) and from markdown guides [Markdown Monster Documentation](https://markdownmonster.west-wind.com/docs/_4xs10gaui.htm). This link contains the syntax of using Markdown syntax pretty well. For IDE, I preferably use VS Code Editor.
The learnings that I gathered are:

1. ### How to create package json:
	I used to consider it as a really big challenge of finding out the versions and dependencies that needs to be installed. I gathered that it can be done through code block 'npm init'. It is also good to know what dependencies that I want to use in my blog so that they can be installed using npm command which will be displayed in the package.json file.

2. ### Including Layouts
	Including layouts saves time. It is usually a nunjucks file where the basic skeletal template is created. I learnt and I am still learning the Nunjucks code syntax and it can be grasped if given proper time.
	
3. ### Configuring .eleventy.js file
	This one is a hard one for me. From what I am developing, I figured that it contains all the access pass that it is supposed to give to folders that are to be used. This one seemed pretty important for me to configure because the basic structure and the folders that it will take to the server is, I think is completely dependent on this one.
	
4. ### Creating posts
	Posts are usually created in markdown language. Currently, my knowledge is still pretty basic and might be below it because I have just started using it. As I figure things out, I will keep on adding posts on what I am discoverin about markdown language.
	
5. ### Deploying it to Netlify
	That will be my next step. Currently it is hosted on local server. Check out my next blog on it
