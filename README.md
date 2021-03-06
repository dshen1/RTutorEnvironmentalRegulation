This package constitutes an interactive R problem set based on the RTutor package (https://github.com/skranz/RTutor). 

In the paper "Who Benefits from Environmental Regulation?
Evidence from the Clean Air Act Amendments", written by Antonio Bento, Matthew Freedman and Corey Long (2014), the authors use geographically disaggregated data and exploit an
instrumental variable strategy to explore the distribution of the benefits induced by 1990 Clean Air Act Amendments (CAAA). Thereby they find that, contrary to the conventional opinion, the benefits of CAAA were progressive. In this problem set you will be guided through their main findings. Besides, you will gain knowledge about R and economic methods.

The paper can be downloaded on this link: http://www.mitpressjournals.org/doi/abs/10.1162/REST_a_00493#.V72bRilkiM_

## 1. Installation

RTutor and this package is hosted on Github. To install everything, run the following code in your R console.
```s
if (!require(devtools))
  install.packages("devtools")
source_gist("gist.github.com/skranz/fad6062e5462c9d0efe4")
install.rtutor(update.github=TRUE)
  
install_github("msporer/RTutorEnvironmentalRegulation")
```

## 2. Show and work on the problem set
To start the problem set first create a working directory in which files like the data sets and your solution will be stored. Then adapt and run the following code.
```s
library(RTutorEnvironmentalRegulations)

# Adapt your working directory to an existing folder
setwd("C:/problemsets/RTutorEnvironmentalRegulations")
# Adapt your user name
run.ps(user.name="Jon Doe", package="RTutorEnvironmentalRegulations",
       load.sav=TRUE, sample.solution=FALSE)
```
If everything works fine, a browser window should open, in which you can start exploring the problem set.
