---
title: Home
sidebar:
  entries:
  - title: Welcome
    url: "#intro"
    is_primary: true
  - title: Who we are
    url: "#one"
    is_primary: false
  - title: What we do
    url: "#two"
    is_primary: false
  - title: Get in touch
    url: "#three"
    is_primary: false
sections:
- type: intro
  template: intro
  title: Hyperspace
  subtitle: "Cras aliquam amet adipiscing nibh faucibus suscipit ut Parturient  \ncol
    accumsan est arcu donec sed Eleifend Integer."
  section_id: intro
  background_style: style1
  actions:
  - label: Learn more
    url: "#one"
    is_scrolly: true
    is_primary: false
  component: intro.html
- type: spotlights
  template: spotlights
  title: Spotlights Section
  section_id: one
  background_style: style2
  component: spotlights.html
layout: home
menu:
  main:
    weight: 1

---
