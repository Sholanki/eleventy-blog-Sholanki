---
layout: post-layout.njk 
title: How to deploy 11ty site on Netlify
date: 2021-03-02
tags: ['post']
---
## How to deploy 11ty site on Netlify
1. ### Add Netlify.toml outside root folder
  It has all the dependencies covered. Ensure that root folder and publish directory is mentioned here
  
2. ### Modify .eleventy.js 
    Modify it to include input and output folder
    
3. ### In Netlify, have a account
4. ### Connect To GitHub
      I am doing it from GitHub. From there, you can basically do continuous deployment and then use the folowing commands in settings:
      build: eleventy
      publish: _site
   
5. ### There is no need to commit site folder in GitHub

That's all for now folks. Keep on the lookout
