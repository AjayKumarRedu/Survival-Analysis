## Survival-Analysis
Servival Analysis of Lung Cancer
## What is Cancer
Cancer is a disease in which cells in the body grow out of control. When cancer starts in the lungs, it is called lung cancer.
Lung cancer begins in the lungs and may spread to lymph nodes or other organs in the body, such as the brain. Cancer from other organs also may spread to the lungs. When cancer cells spread from one organ to another, they are called metastases.
Lung cancers usually are grouped into two main types called small cell and non-small cell (including adenocarcinoma and squamous cell carcinoma). These types of lung cancer grow differently and are treated differently. Non-small cell lung cancer is more common than small cell lung cancer.
For more information, visit the National Cancer Institute’s https://www.cancer.gov/types/lung


## DataSet Info
* Variable description
inst: Institution code
time: Survival time in days
status: censoring status 0 = censored, 1 = dead
age: Age in years
sex: Male = 0 Female = 1
ph.ecog: ECOG performance score as rated by the physician. 0 = asymptomatic, 1 = symptomatic but completely ambulatory, 2 = in bed <50% of the day, 3 = in bed > 50% of the day but not bedbound, 4 = bedbound
ph.karno: Karnofsky performance score (bad=0-good=100) rated by physician
pat.karno: Karnofsky performance score as rated by patient
meal.cal = Calories consumed at meals
wt.loss = Weight loss in last six months

## Survival Analysis
Survival Analysis is used to estimate the lifespan of a particular population under study. It is also called ‘Time to Event’ Analysis as the goal is to estimate the time for an individual or a group of individuals to experience an event of interest. This time estimate is the duration between birth and death events[1]. Survival Analysis was originally developed and used by Medical Researchers and Data Analysts to measure the lifetimes of a certain population[1]. But, over the years, it has been used in various other applications such as predicting churning customers/employees, estimation of the lifetime of a Machine, etc. The birth event can be thought of as the time of a customer starts their membership with a company, and the death event can be considered as the customer leaving the company. To know more about Survival Analysis Use this blog
https://towardsdatascience.com/survival-analysis-part-a-70213df21c2e



