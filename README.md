# Bumblebee Guide
Created: 08.04.2025

## Overview
This guide explains how to push edits and deploy on the website Bumblebee

## Dependencies
The dependencies listed here is only required to change the front page map.

### R packages
The R software and packages are only required for the map example.

```r
install.packages("leaflet")
install.packages("knitr")
install.packages("rmarkdown")
```

## Deploying to web
Be sure to render a final time and committing the changes before publishing:

```shell
quarto render

quarto publish gh-pages
```

## Background
The quarto deployment were set up with publish command from the [quarto docs](https://quarto.org/docs/publishing/github-pages.html#publish-command).
