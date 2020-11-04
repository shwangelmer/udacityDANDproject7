# PISA Data Exploration
## by Simon Hwang


## Dataset

> The Programme for International Student Assessment (PISA) is a means of measuring 15-year-old student ability in reading, mathematics, and science. PISA was created by the Organisation for Economic Co-operation and Development (OECD), which is headquartered in France and was founded in 1961 to promote global economic growth and world trade. The assessments are conducted every 3 years since 2000, and usually garner participation from about 80 countries. Countries are asked to sample at least 5000 students, but may test more if they wish to acquire more regional and subregional information. The samples are chosen in a two stages - random school selection, and then random students selection. Due to this two-stage sampling, and the variable sample sizes, the OECD recommends weighting each student's data, using replicates to compute error, and provides plausible values for the test scores (see note below for more information). This dataset was based on the student questionnaire of the 2012 PISA, the full report of which can be viewed [here](http://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf).

The dataset was accessed via this link: <https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000>

>> Note: As mentioned above, the OECD, in the [PISA Data Analysis Manual (2nd Edition)](https://catalog.data.gov/dataset/pisa-data-analysis-manual-spss-second-edition/resource/4621631e-7044-4fca-9ab7-17f525be20a1), recommends using three methods for appropriately wrangling the raw PISA data: weights, replicates, and plausible values. Unfortunately, these methods are not covered in the Udacity Data Analyst Nanodegree and are not warranted for the completion of this project. I will not be using them in my exploration or presentation of results, so any conclusions or relationships are subject to significant error and should be seen as demonstrative of the Udacity program's core proficiencies, rather than true results.	

## Summary of Findings

> Through univariate exploration, I was able to confirm the methodology describe by OECD in their [2012 PISA report](http://www.oecd.org/pisa/pisaproducts/PISA-2012-technical-report-final.pdf). All OECD countries (except Iceland, which has special exemption due to its low population) were very close to or exceeded the 5,000 student minimum sample size recommended by the OECD. The two-stage sampling was able to yield almost equal sex sizes (female 50.18%, male 49.82%). Then, the distributions of the socioeconomic index (ESCS) and the averages of the reading, math, and science scores made evident the relativistic nature of the scoring. Those four values are nearly perfect normal distributions.


## Key Insights for Presentation

> Select one or two main threads from your exploration to polish up for your presentation. Note any changes in design from your exploration step here.