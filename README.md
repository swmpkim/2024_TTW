# 2024 TTW R Workshop

## What you need to do before the workshop:

-   Get the programs on your laptop: recent versions of R (at least 4.2.0), RTools, and RStudio. Do these installations early, as administrative privileges may be required.

    1.  Download R for your operating system: <https://cran.r-project.org/>

    2.  RTools (only needed on Windows): <https://cran.r-project.org/bin/windows/Rtools/>

    3.  Free version of RStudio desktop; note that R MUST be installed before RStudio: <https://posit.co/download/rstudio-desktop/>

-   Install packages that we'll use. Copy and paste the following code into the Console pane of RStudio, and run it:  

```
install.packages(c('tidyverse', 'here', 'janitor', 'SWMPr', 'SWMPrExtension'))
```

-   Download 3-5 years of data from each of (at least) two SWMP water quality stations through the CDMO's [Advanced Query System Zip Download](https://cdmo.baruch.sc.edu/aqs/zips.cfm) and put it in a place you can find it.  



## Agenda

| Time          | Topic                                       |
|:--------------|:--------------------------------------------|
| 8:30 - 10:00  | Getting oriented in R and RStudio           |
|               | Getting ready to code:                      |
|               | \- vocabulary                               |
|               | \- important operators & keyboard shortcuts |
|               | \- file types                               |
|               | \- projects and working directory           |
|               |                                             |
| 10:00 - 10:15 | Break                                       |
|               |                                             |
| 10:15 - 12:00 | Basic coding & SWMPr:                       |
|               | \- reading in data                          |
|               | \- examining data:                          |
|               | \- summary functions                        |
|               | \- very basic plots                         |
|               | \- QA/QC codes with SWMPr                   |
|               |                                             |
| 12:00 - 12:30 | Lunch                                       |
|               |                                             |
| 12:30 - 1:30  | More coding:                                |
|               | \- subsetting                               |
|               | \- aggregating                              |
|               | \- less-basic plots                         |
|               |                                             |
| 1:30 - 1:45   | Break                                       |
|               |                                             |
| 1:45 - 2:30   | How to move forward                         |
|               | Useful packages & functions, and            |
|               | how to find them                            |
|               |                                             |
