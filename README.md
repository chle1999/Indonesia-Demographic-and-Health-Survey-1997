# Indonesia-Demographic-and-Health-Survey-1997

This report aims to analyze the birth interval results by background characteristics derived from the Indonesia Demographic and Health Survey 1997 (IDHS) conducted by the Central Bureau of Statistics and DHS (Demographic and Health Survey), and the disparities in the birth interval by age group, gender, and the survival of a prior birth, as well as by region/residence, education level and work status using R.

The rest of paper is composed of three parts: a data section that provides extensive information about the source data and methodology of the survey; a result section that presents the visualization of the data extracted from the report and analyzes the results; and a discussion section that discusses the limitations and implications.

The results show that shorter intervals of birth are more likely to be found in young females, those with deceased prior children, and those with higher levels of education, whereas work status and gender of prior children are not significant factors. The findings of this study are expected to assist the Indonesian government in assessing the preliminary success of the "mother-friendly movement" program and setting strategic goals for its future.

The final report can be viewed [here](https://github.com/chle1999/Indonesia-Demographic-and-Health-Survey-1997/blob/main/outputs/paper/paper.pdf).

## R Packages

In order to process the data and analysis, the following packages should be installed:

1. janitor()
2. pdftools()
3. purrr()
4. tidyverse() 
5. stringi()
6. kableExtra()
7. here()
8. readr()
9. knitr()
10. tinytex()



## File Structure

The raw data are extracted from the report of IDHS 1998 pdf file downloaded from the DHS website, which is contained in the “input” folder.

The "output" folder contains the original R Markdown file containing the analysis carried out in R, a PDF version of the final paper, and the reference list.

The pictures of the original tables from the report is included in the “image” folder.
