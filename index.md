---
title: Home
sidebar:
  entries:
  - title: Welcome
    url: "#welcome"
    is_primary: true
  - title: Vlogs
    url: "#vlogs"
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
  actions: []
  component: welcome.html
- type: pages
  template: 
  title: Vlogs
  subtitle: 
  section_id: vlogs
  background_style: style2
  actions: []
  component: vlogs.html
- type: contact
  template: about
  title: About
  subtitle: 
  section_id: about
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
