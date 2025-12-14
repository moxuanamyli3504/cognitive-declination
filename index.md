# Cognitive Declination Differences Between Men and Women

**Authors:**  
Amy Li, Ellie White

---

## Project Overview

This project investigates how cognitive decline varies with age and gender using clinical assessment data related to Alzheimer’s disease and other neurodegenerative conditions. Cognitive decline is measured using the **Clinical Dementia Rating (CDR)** score, a standard clinical metric where higher values indicate more severe dementia.

Using age-stratified and gender-stratified analysis, we examine whether patterns of cognitive decline differ between men and women across the aging spectrum.

---

## Research Question

**How does cognitive decline (as measured by CDR) vary with age, and are there significant differences between males and females?**

---

## Dataset Summary

- **Number of observations:** 450
- **Age range:** 61–98 years
- **Mean age:** 76.4 years
- **Key variables used:**  
  - Age  
  - Gender  
  - Clinical Dementia Rating (CDR)

The dataset is consistent with large-scale neuroimaging studies such as ADNI and focuses on older adults, making it appropriate for Alzheimer’s disease research.

---

## Methods

- Preprocessed demographic and cognitive variables
- Grouped participants into **5-year age bins**
- Calculated **mean CDR scores** for each age–gender group
- Created **side-by-side visual comparisons** to highlight gender differences across age groups

---

## Key Findings

- Males tend to show **higher average CDR scores** than females across most age groups
- Peak cognitive decline appears earlier in males (ages 65–69)
- Average CDR decreases at higher ages, potentially reflecting **survivorship bias**
- The oldest age group (95–99) contains only female participants
![visualization.png](visualization.png)
---

## Conclusions

The relationship between age and cognitive decline is **non-linear** and differs by gender. While cognitive impairment generally increases with age, the observed decline in CDR at older ages suggests that individuals with severe dementia may be underrepresented in later age groups.

Gender differences are evident across most age ranges, with males consistently showing higher CDR scores, likely influenced by differences in lifespan and survival.

---

## Limitations

- Small sample size in the oldest age group
- Gender imbalance in some age bins
- Cross-sectional analysis assumes different individuals represent disease progression

---

## Full Project Materials

 **[View the full project repository](https://moxuanamyli3504.github.io/cognitive-declination/)**  
 **[Open the Colab analysis notebook](https://colab.research.google.com/drive/1jWL4xmI5Fu7I0w_E8uCH6TcxTrIV9iWO?usp=sharing)**
 
---

## Future Work

Future analyses could:
- Control for education and socioeconomic status
- Examine dementia progression categories separately
- Investigate survival bias using longitudinal data

