# About

This is the TAMU theme for R [xaringan](https://github.com/yihui/xaringan) package. It is based on [Texas A&M University University Brand Guide](https://brandguide.tamu.edu/).

- To use this template just clone this repo. You only need to put your slide file (`*.Rmd`) and the template css (`tamu.css`, `tamu-fonts.css`) in the same folder.

- Set the YAML metadata in `Rmd` file, e.g.:

```yaml
---
title: "TAMU Presentation"
output:
  xaringan::moon_reader:
    css: ["default", "tamu.css", "tamu-fonts.css"]
    nature:
          highlightLines: true
---
```

- Then, use `xaringan:::inf_mr()` or `knit` the file to check output.

## Reference link
[1] [Xaringan](https://github.com/yihui/xaringan)  
[2] [Rladies template](https://alison.rbind.io/slides/rladies-demo-slides.html)  
[3] [Duke color template](https://github.com/libjohn/slide-template-dukeu)  
[4] [Metropolis template](https://github.com/pat-s/xaringan-metropolis)  
