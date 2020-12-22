# Overview
This repo contains code and data for report,"The Usage of Biased Smapling Causing Underestimation of Infected Population and Weak Policies". It was created by TianXiao Ma. The purpose is to create a report that aims to show how does current COVID actual infected cases are substantially underestimated by biased samples with the help of Monte Carlo Model. We detail how to get data obtained in the report below. The sections of this repo are: clean data script and output.

Support dataset folder contains all the dataset used in the paper. -contacttracing.csv The document contains data of daily newly added cases in Ontario. It is adapted from Public Health Ontario Weekly epidemiologic summary: COVID-19 in Ontario – focus on December 6, 2020 to December 12, 2020.URL attatched: https://files.ontario.ca/moh-covid-19-weekly-epi-report-en-2020-12-12.pdf

covid19data.csv The document contains total number of confirmed COVID-19 cases in Canada and Italy from January 26 until April 10,recorded every 3 days.It is adapted from European Centre for Disease Prevention and Control(ECDC) URL attatched: https://www.ecdc.europa.eu/en/publications-data/download-todays-data-geographic-distribution-covid-19-cases-worldwide
r0.on.wa.csv The document contains reproduction number in Ontario, Canada (CCM, 2020) and Washington, U.S.(The COVID Tracking Project, 2020) at four time stages. Reproduction number for Ontario, Canada can be found at: https://covid-19.ontario.ca/data#where_numbers Reproduction number for Washington, U.S.can be found at: https://rt.live/us/WA
R code folder contains all the code needed for building the report:

biased sampling.Rmd contains code build for the report paper,paper can be found in the repo locates at /Paper/Bidengo.pdf.
Paper folder contains the pdf report using . Corresponding code script can be found in R code folder.

biased-sampling.pdf