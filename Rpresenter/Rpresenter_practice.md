R Presenter Practice
========================================================
author: Catherine Durso
date: Sat Dec 19 15:49:31 2015
transition: rotate

First Slide
=== 


For more details on authoring R presentations click the
**Help** button on the toolbar.

- Bullet 1 $x^1$
- Bullet 2 $x^2$
- Bullet 3 $x^2$


Slide With Code
=======================================================



```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Plot
========================================================

![plot of chunk unnamed-chunk-2](Rpresenter_practice-figure/unnamed-chunk-2-1.png) 

Visuals
===
transition: linear

- R Studio has made it easy to get some cool html5 effects, like cube transitions
with simple options in YAML-like code after the first slide such as
`transition: rotate`
- You can specify it in a slide-by-slide basis

Here's the option "linear"
===
transition: linear

- Just put `transition: linear` right after the slide creation (three equal signs or more in a row)
- Tansition options 
    - http://www.rstudio.com/ide/docs/presentations/slide_transitions_and_navigation
    
Hierarchical organization
===
transition: linear
type: section
- If you want a hierarchical organization structure, just add a `type: typename` option after the slide
- This changes the default appearance
    - http://www.rstudio.com/ide/docs/presentations/slide_transitions_and_navigation
- This is of type `section`

Here's a subsection
===
transition: linear
type: subsection

Two columns
===
- Do whatever for column one
- Then put `***` on a line by itself with blank lines before and after

***

- Then do whatever for column two

Changing the slide font
==========================================================
font-import: http://fonts.googleapis.com/css?family=Risque
font-family: 'Risque'

- Add a `font-family: fontname` option after the slide
    - http://www.rstudio.com/ide/docs/presentations/customizing_fonts_and_appearance
- Specified in the same way as css font families
    - http://www.w3schools.com/cssref/css_websafe_fonts.asp
- Use `font-import: url` to import fonts
- Important caveats
    - Fonts must be present on the system that you're presenting on, or it will go to a fallback font
    - You have to be connected to the internet to use an imported font (so don't rely on this for offline presentations)
- This is the `Risque` 
    - http://fonts.googleapis.com/css?family=Risque
    
