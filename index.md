---
title: Home
sidebar:
  entries:
  - title: Welcome
    url: "#welcome"
    is_primary: true
  - title: Blog
    url: "#blog"
    is_primary: false
  - title: About
    url: "#about"
    is_primary: false
sections:
- type: intro
  template: intro
  title: Welcome to TesterTech
  subtitle: 
  section_id: welcome
  background_style: style1
  home_img_path: images/pic01.jpg
  actions: []
  component: welcome.html
- type: pages
  template: posts
  title: Blog
  subtitle: Collection of (video) blogs about software testing related topics
  section_id: blog
  home_img_path: images/pic01.jpg
  background_style: style2
  actions: []
  component: posts.html
- type: contact
  template: about
  title: About
  subtitle: 
  section_id: about
  home_img_path: images/pic01.jpg
  background_style: style3
  actions: []
  component: about.html
layout: home
collections:
  vlogs:
    output: true
menu:
  main:
    weight: 1

---
