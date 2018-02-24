# Installation
a. Copy `tamu.css` & `tamu-fonts.css` to your local slide-composition directory  
b. Refer the example `yaml` like this:  
``` yaml
title: "Presentation Ninja"
subtitle: "⚔<br/>with xaringan"
author: "Yihui Xie"
date: "2016/12/12"
output:
  xaringan::moon_reader: 
    css: ["default", "tamu", "tamu-fonts"] 
    lib_dir: libs
    nature:
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
```