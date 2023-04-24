# Project "Depression disorder: worldwide distribution, treatment aspects and modern method of diagnostics"

Authors:
1. [Sergey Orlov](https://www.linkedin.com/in/orlovtsu/)
2. [Shrivarshini Balaji](https://www.linkedin.com/in/shrivarshini-balaji-999551188/)
3. [Niloofar Mirzadzare](https://www.linkedin.com/in/niloofar-mirzadzare-280211271/)


## Introduction 

Mental health, which affects behavior and coping abilities, is crucial, and depression is a prevalent mental illness worldwide [1]. Depression's symptoms include persistent sadness, loss of interest, and other complex causes like genetics, lifestyle choices, and major life events, and it can result in functional disabilities and suicidal behavior. Due to modern society's chronic stress, substance abuse, and unhealthy lifestyles, depression rates are on the rise, necessitating an examination of diagnostic and treatment options [2].

First of all we will compare the prevalence of depression Worldwide and how can be calculated the burden of depression on society and economics.
We also discuss how can different countries work with the depression rate and how the decrease the burden of this mental disorder.

## Methodology 

For this project, we aim to use SQL to extract data and create visualizations in python. We will first connect our datasets to SQL. Subsequently, we will write SQL queries (requests) to extract data needed for visualizations and perform any necessary data cleaning/wrangling (i.e. removing missing values, merging tables, etc.). Finally, we will fetch our data from the SQL databases into pandas data frames and will create relevant visualizations using libraries such as matplotlib, seaborn or plotly.

## Datasets 

People all around the world experience mental health issues, and different countries address these problems in different ways for various reasons. In the first question, we examine the distribution of people with depression worldwide, based on 3 datasets. 

The "Global Trends in Mental Health Disorder" dataset is sourced from Kaggle [3] and is available for use with citations of the dataset author [4]. It contains informative data from countries worldwide, covering the prevalence of mental health disorders such as schizophrenia, bipolar disorder, eating disorders, anxiety disorders, drug use disorders, depression, and alcohol use disorders from 1990 to 2017. We utilize data from the final year of the dataset to determine the percentage of people suffering from depression in each country.

To measure the impact of depression within each society, the parameter of disability-adjusted life year (DALY) per 100,000 people is utilized. The DALY parameter is employed to gauge the total burden of depression. To compare countries using this parameter, the dataset "DALY” estimates WHO Member States by country. This dataset is sourced from the official World Health Organization website (http://who.int) and may be utilized for research purposes, with proper citation [5]. The dataset includes DALY parameters for each country in the WHO for every monitored disorder, segregated by gender and age, spanning the years from 2000 to 2019. For our project, we will be utilizing the data for depression disorder from this dataset to compare countries based on the DALY parameter.

The dataset about expenditures for the healthcare system worldwide is taken from The World Bank website [6]. This dataset contains health expenditures in percentage to GDP, expenditures in U.S. dollars, and expenditures in U.S. dollars per capita for 2019 by countries. This data is used in combination with the dataset "Government expenditures on mental health as a percentage of total government expenditures on health (%)" from the World Health Organization website [7]. By combining these data, we can analyze spending on mental health worldwide by country and the efficiency of money spent on diagnostics and treatment in each healthcare system.

## Jupyter Notebook 

The project jupyter notebook with Python Code and SQL queries is provided in file: 
The database credentials are not provided because of safety, but anyone who want to reuse this code can use it with own database. I used MySQL database on AWS instance. 

## Gratitudes 

I would like to special thank [Dr. Tamer Jarada](https://www.linkedin.com/in/tamerjarada/) for the very useful feedback and great insights I received from his course and my project partners [Shrivarshini Balaji](https://www.linkedin.com/in/shrivarshini-balaji-999551188/) and [Niloofar Mirzadzare](https://www.linkedin.com/in/niloofar-mirzadzare-280211271/) for productive cooperation, responsibility and excellent communication.


## References  

[1] World Health Organization. (2021). Depression. Retrieved from:  https://www.who.int/news-room/fact-sheets/detail/depression 

[2] Hidaka, B., H. (2012). Depression as a disease of modernity: explanations for increasing prevalence. Affect Disord. 140(3):205-14. doi: 10.1016/j.jad.2011.12.036. 

[3] TheDevastator. (2022). Uncover global trends in mental health disorder. Kaggle. Retrieved from: https://www.kaggle.com/datasets/thedevastator/uncover-global-trends-in-mental-health-disorder

[4] Amit's datasets. data.world. (2022). Retrieved from: https://data.world/amitd  

[5] World Health Organization. (2023). Global Health Estimates. World Health Organization. Retrieved from https://www.who.int/data/global-health-estimates 

[6] World development indicators: The World Bank. World Development Indicators | The World Bank. (2017). Retrieved from: http://wdi.worldbank.org/table/2.12# 

[7] World Health Organization. (2023). Government expenditures on mental health as a percentage of total government expenditures on Health (%). World Health Organization. Retrieved from: https://www.who.int/data/gho/data/indicators/indicator-details/GHO/government-expenditures-on-mental-health-as-a-percentage-of-total-government-expenditures-on-health-(-)

[8] Oberlander TF, Miller AR (2011). Antidepressant use in children and adolescents: Practice touch points to guide paediatricians. Paediatr Child Health.9:549-53. doi: 10.1093/pch/16.9.549. PMID: 23115493; PMCID: PMC3223889.

[9] Devastator, T. (2023). Antidepressant use in Scandinavia. Kaggle. Retrieved from:  https://www.kaggle.com/datasets/thedevastator/antidepressant-use-in-scandinavia

[10] Liu, B., Chang, H., Peng, K., & Wang, X. (2022). An end-to-end depression recognition method based on EEGNet. Frontiers in Psychiatry, 13. https://doi.org/10.3389/fpsyt.2022.864393 

[11] Allen JJ, Reznik SJ. (2015). Frontal EEG Asymmetry as a Promising Marker of Depression Vulnerability: Summary and Methodological Considerations. Curr Opin Psychol. 4:93-97. doi: 10.1016/j.copsyc.2014.12.017. Epub 2015 Jan 2. PMID: 26462291; PMCID: PMC4599354.

[12] Tiwari, S. (2022). Eeg Psychiatric Disorders Dataset. Kaggle. Retrieved from: https://www.kaggle.com/datasets/shashwatwork/eeg-psychiatric-disorders-dataset 

[13] Lazygene. (2022). Visualising pre-processed EEG Data. Kaggle. Retrieved from https://www.kaggle.com/code/lazygene/visualising-pre-processed-eeg-data 

[14] Čukić M, Stokić M, Simić S, Pokrajac D. (2020). The successful discrimination of depression from EEG could be attributed to proper feature extraction and not to a particular classification method. Cogn Neurodyn, 14(4):443-455. doi: 10.1007/s11571-020-09581-x. Epub 2020 Mar 25. PMID: 32655709; PMCID: PMC7334335.

[15] Lesbian, gay, bisexual, transgender and Queer/questioning. Psychiatry.org - Lesbian, Gay, Bisexual, Transgender and Queer/Questioning. (2023). Retrieved from https://www.psychiatry.org/psychiatrists/diversity/education/lgbtq-patients 
