# Cognitive Declination Differences Between Men and Women

**Authors:**  
Amy Li, Ellie White

---

## Introduction

The dataset analyzed in this study contains clinical assessment data for individuals potentially affected by Alzheimer's disease and related cognitive disorders. This dataset appears to be derived from neuroimaging studies, likely originating from research initiatives such as the Alzheimer's Disease Neuroimaging Initiative (ADNI) or similar longitudinal studies focused on neurodegenerative diseases.
The dataset includes 450 observations with the following key variables: demographic information, education & socioeconomic status, cognitive assessments, neuroimaging metrics, and clinical classification. In this data analysis, we focus on the demographic information (age, gender) and cognitive assessments (Clinical Dementia Rating (CDR)).
The primary question of this study is: how does cognitive decline (as measured by CDR) vary with age, and are there significant gender differences in this relationship? To be more specific, we are also wondering if there are distinct patterns of cognitive decline across different age groups, and how age-related cognitive changes differ between males and females. 
We picked out the variables we want to focus on from this dataset during preprocessing, created 5-year age groups for comparisons, analyzed the CDR scores based on these age groups, distinguished males and females, made a visualization of side-by-side bar graphs to facilitate direct gender comparisons, and came to a conclusion with the interpretation of the visualization. It is known that higher CDR means more severe dementia, and lower CDR means milder dementia.

---

## Research Question

**How does cognitive decline (as measured by CDR) vary with age, and are there significant differences between males and females?**

---

## Methods & Results

### Data Preparation

The dataset was initially examined for missing data, and we found that the dataset contained 27 scattered missing values in the SES (Socioeconomic Status) column, which is expected in clinical datasets. These missing values did not affect the core analysis of Age, Gender, and CDR relationships. All other critical variables for the analysis (Age, Gender, CDR) were complete.
For the variables focused in this study, we found that the age ranges from 61-98 years, with the mean of 76.4 years and standard deviation of 7.2 years. The distribution confirms the dataset focuses on older adults, which is appropriate for Alzheimer's disease research.

### Analysis Methodology

To clean up this data, we first stratified the dataset by gender and age group, and then calculated the mean CDR scores for each gender-age group combination. We found that these patterns can be compared across age groups and between genders with a side-by-side bar graph, which was the visualization in the last step. 

![visualization.png](visualization.png)


### Key Findings

One of the most apparent trends in this visualization is the distribution of data in both genders. The average age appeared in this visualization shows that males are likely to have dementia at a lower average age than females; this could also because males have lower average lifespan than females. In addition, average CDR gradually decreases as age increases, which is expected due to the Alzheimer’s patients being more severely demented as age increases. 

---

## Conclusions

Based on the analysis, we can answer our primary question: How does cognitive decline vary with age, and are there significant gender differences? The visualization reveals a complex, non-linear relationship between age and cognitive decline as measured by CDR. Contrary to expectations, the data shows peak CDR scores in the 65-69 age group for males, followed by a decline in later years, meaning less severe dementia. This could be possible because more severe dementia at an earlier age (60-70) might cause earlier deaths, so the CDR data for higher age are higher, or less severe dementia. 
Gender differences are pronounced and vary by age: males consistently show higher CDR scores than females across all age groups except the oldest (95-99), where only female data is available. A possible explanation is that men have lower lifespan than women, and only data for women are available in the range of 95-99 years in this dataset.

### Limitations

There are several limiting factors in this study: 
  The 95-99 age group contains only 4 females and no males, making conclusions about the oldest age unreliable.
  The age group comparison assumes different individuals represent different stages of progression, which may not hold true.
  Some age groups (90-94) have imbalanced gender representation (12F vs 5M), potentially skewing comparisons.

### Future Work

This dataset can be further analyzed in many other ways. Some immediate research priorities can be analyzing CDR patterns separately for Nondemented, Demented, and Converted categories to understand progression from healthy aging to dementia, controlling education (EDUC), socioeconomic status (SES), and neuroimaging metrics (nWBV, eTIV) to isolate age and gender effects, or investigating whether the decline in CDR after age 85 represents survival bias or true cognitive patterns.

---

## Full Project Materials

 **[View the full project repository](https://moxuanamyli3504.github.io/cognitive-declination/)**  
 **[Open the Colab analysis notebook](https://colab.research.google.com/drive/1jWL4xmI5Fu7I0w_E8uCH6TcxTrIV9iWO?usp=sharing)**
