# Overview
This repo contains code and data for report,"The Usage of Biased Smapling Causing Underestimation of Infected Population and Weak Policies". It was created by Tianxiao Ma. The purpose is to create a report that aims to show how does current COVID actual infected cases are substantially underestimated by distorted data and biased sampling with the help of Monte Carlo Model. Details about how to get data are obtained in the report below. Three sections contained in this repo: Support dataset, R code, and output. Some resource data related to this report readers may be interested are included below the explanation of the paper folder in the overview. Please refer to References and Appendix sections in biased-sampling.pdf/biased sampling.Rmd under paper/R code folder for more details about reference literatures in the report.

Support dataset folder contains all the dataset used in the paper. 
- contacttracing.csv The document contains data of daily newly added cases in Ontario. It is adapted from Public Health Ontario Weekly epidemiologic summary: COVID-19 in Ontario – focus on December 6, 2020 to December 12, 2020. URL attatched: https://files.ontario.ca/moh-covid-19-weekly-epi-report-en-2020-12-12.pdf

- covid19data.csv
The document contains total number of confirmed COVID-19 cases in Canada and Italy from January 26 until April 10,recorded every 3 days.It is adapted from European Centre for Disease Prevention and Control(ECDC) URL attatched: https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide

- r0.on.wa.csv The document contains reproduction number in Ontario, Canada (CCM, 2020) and Washington, U.S.(The COVID Tracking Project, 2020) at four time stages. Reproduction number for Ontario, Canada can be found at: https://covid-19.ontario.ca/data#where_numbers Reproduction number for Washington, U.S.can be found at: https://rt.live/us/WA

R code folder contains all the code needed for building the report:
- biased sampling.Rmd contains code build for the report paper,paper can be found in the repo locates at /Paper/Bidengo.pdf.

Paper folder contains the pdf report using . Corresponding code script can be found in R code folder.
- biased-sampling.pdf

Notes: Reproduction number and weekly reported cases for Ontario, Canada can be found at: 
Public Health Ontario (2020). "COVID-19: Epidemiologic Summaries from Public Health Ontario.” Retrived from: covid-19.ontario.ca/covid-19-epidemiologic-summaries-public-health-ontario. or through government Ontario's website(they derive data directly from Public Health Ontario): https://covid-19.ontario.ca/data#where_numbers

Reproduction number for Washington, U.S.can be found at: 
Rt.live.(2020), Retrived from: https://rt.live/us/WA

Canadian Contact tracing data can be found at:
Statistics Canada (2020). Statistics Canada and contact tracing. Retrieved from https://www.statcan.gc.ca/eng/transparency-accountability/contact-tracing
