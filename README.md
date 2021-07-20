# README

This repository contains notes and worked exercises for [Practical Statistics for Data Scientists](https://www.oreilly.com/library/view/practical-statistics-for/9781491952955/) as part of the R4DS bookclub starting on May 10, 2021.  The material covered in each bookclub session can be found [here](https://r4ds.github.io/bookclub-ps4ds/estimates-of-location.html).

## Downloading Data

To download the datasets used in each chapter, install the `googledrive` and `curl` and run the following line of code:

```
curl_download("https://github.com/andrewgbruce/statistics-for-data-scientists/tree/master/src/download_data.r", "download_data.R")
```

The command downloads the `download_data.r` script from the author's GitHub repository and will download the files needed for each chapter from the GoogleDrive site.  All of the files used in the textbook and in the analysis notebooks described below can be found in the `data` directory.

## Repository Structure

The `rmarkdown_notebooks` and `html_notebooks` directories contain the raw R markdown and HTML notebooks, respectively.  If you want to view the rendered HTML files with all text, code chunks, tables, and embedded figures, navigate to the `html_notebooks` directory, download the file, save the web page, and open it in any web browser. 


