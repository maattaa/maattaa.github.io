---
title: "Starting a blog using Github Pages and GatsbyJS"
date: "2020-05-23T18:46:00.000Z"
description: "First post. This describes the process of setting up your own blog."
---

I have thought about writing to a blog of Capture The Flag (CTF) walkthroughs, tutorials, hopefully some research and whatever I feel important. I wanted to have minimalistic solution, but something that is modern and nothing that is too tied to the platform with out-of-box solutions. However, I did not have any idea what there should be besides [Githup pages](https://pages.github.com). 

# Technology

I have done some fullstack with React so something with JS and TS would help to maintain my skills, but node-React will be overkill as there is (not yet) no need for a backend. Github Pages' [documentation](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll) recommends [Jekyll](https://jekyllrb.com) as static site generator. It would do the job, but it runs on Ruby. I have not found use for ruby besides configuring Vagrant, so these skills might not be that useful in the future. On the other hand [GatsbyJS](https://www.gatsbyjs.com) uses JavaScript as you might have figured out, so I wanted to look into it.

[Hugo](https://gohugo.io) is also one option. I want to mention it here, as it uses Golang, making it's builds faster than Jekyll's or Gatsbys. Golang is also interesting as it has low-level abilities but is readable and modern, something that C doesn't full under to. Hugo also has standalone HTTP server, which is most likely enough for smaller sites, but as stated, there is no need for server when using Github Pages. Hugo is also stated as depencency free, which 