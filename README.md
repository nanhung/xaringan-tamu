This is the r [xaringan](https://github.com/yihui/xaringan) theme. The color of this is based on [Texas A&M University Brand Color](https://brandguide.tamu.edu/colors.html).

# Installation
a. To use this template, you just need to put your slide file (`*.Rmd`) and the template css (`tamu.css`, `tamu-fonts.css`) in the same folder.
b. Define the `yaml` in your `Rmd` file. Here is the example:  

``` yaml
title: "Presentation Ninja"
subtitle: "⚔<br/>with xaringan"
author: "Yihui Xie"
date: "2016/12/12"
output:
  xaringan::moon_reader: 
    css: ["tamu.css", "tamu-fonts.css"] 
    lib_dir: libs
    nature:
      highlightStyle: github
      highlightLines: true
      countIncrementalSlides: false
```
c. Type `xaringan:::inf_mr()` in consloe to see your masterpiece

## Other template repo
Duke: https://github.com/libjohn/slide-template-dukeu
Metropolis: https://github.com/pat-s/xaringan-metropolis
