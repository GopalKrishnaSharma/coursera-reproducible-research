coursera-reproducible-research
==============================

As per the assignment description: *This project involves exploring the U.S. 
National Oceanic and Atmospheric Administration's (NOAA) storm database. This
database tracks characteristics of major storms and weather events in the
United States, including when and where they occur, as well as estimates of any
fatalities, injuries, and property damage.*

This is the second project in Coursera's Reproducible Research course.

# Download

```
git clone https://github.com/RaphaelDeLaGhetto/coursera-reproducible-research.git
cd coursera-reproducible-research
```

# knitr

As this is an exercise in literate statistical analysis, this project has to
be processed with `knitr`. First, run `R`:

```
R
```

And then run the following at the interactive prompt:

```
install.packages('knitr')
library(knitr)
knit2html('report.Rmd')
```

The final command will output two files:

1. `report.md`
2. `report.html`

To view the report produced, run the following from the `R` prompt:

```
browseURL('report.html')
```

