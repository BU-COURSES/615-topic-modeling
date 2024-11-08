# Mapping -- quarto slides in powerpoint

The qmd files in this class will produce the slides that you saw in class. At the end of the presentation, you saw that the final map, an interactive map made with the tmap package, would not run in powerpoint. To see it run, alter the YAML heading in either of the qmd files (I used test222.qmd). replace

```         
  format: 
  pptx:
    reference-doc: Presentation1.pptx
    slide-level: 1
```

with

```         
  format: html
```

and render the file in quarto again.
