# Open Science Game Slides

These are the slides for the PSU Libraries Research Symposium, March 16, 2017, 1-4pm.

The slides are viewable as GitHub pages at https://olendorf.github.io/open_science_game/.

The slides were created using [Slidify](http://slidify.org/) in the R programming language using [RStudio](https://www.rstudio.com/).

## Reuse

The project is licensed under the Apache 2.0 license so feel free to clone and reuse. 

### Dependencies

You will need to install and load [Slidify](http://slidify.org/) from GitHub.

```r
  # Allows you to create embedded R code in markdown, html latex etc.
  install('knitr')
  library(knitr)
  
  ## Allows you to install from github.
  install('devtools')   # Should already be installed so skip if necessary
  library(devtools)
  
  install_github('ramnathv/slidify')
  install_github('ramnathv/slidifyLibraries')
  library(slidify)
  library(slidifyLibraries)
```

The other packages need to create the slides should install and load automatically but if 
they don't then install and load these packages manaually.

```r
  # Working with images.
  install('png')
  library(png)
  install('grid')
  library(grid)
  
  # Advanced charting and graphs
  install('ggplot2')
  library(ggplot2)
  
  # Creating ternary plots
  install('ggtern')
  library(ggtern)
```

Make any changes you like then run Knitr. You can use the Knitr button in RStudio or on the console

```r
  knit('index.Rmd')
```

For more on editing Slidify files use the [Slidify](http://slidify.org/) documentation. See [Knitr]([Slidify](http://slidify.org/)) for more on this topic.




