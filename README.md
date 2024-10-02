# VisuArc
An arc diagram is graphical representation of a selected part of the VisuNet network.

## Arguments
- net - an output network from the VisuNet
- df - a data frame containing network connection in columns
- discrete - an integer that defines which column from df shall be taken
- dec - a character indciating decision class to be presented
- mainTitle - a character indciating title for the arch diagram

## Output
An arc diagram presenting hub and all its connections dervied from rules

## About
Function is supported with a package "arcdiagram".
(Sanchez, Gaston. "Introduction to the R package arcdiagram", 2016)

## Usage
```r
library(VisuNet)
library(arcdiagram)

visuArc(vNet, df, 1, "cancer", "sample arc diagram")
```

