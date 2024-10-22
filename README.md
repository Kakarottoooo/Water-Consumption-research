

# **Water Consumption of Students at Dickinson College**

**Authors:** Derek Chibbaro, Maia Vachon, Quang Nguyen, Ziwei Guo  
**Course:** MATH 325  
**Institution:** Dickinson College

---

## **Project Overview**

This project investigates the **water consumption patterns** among first-year students and upperclassmen at Dickinson College. By analyzing water usage data from residential buildings over a period of 10 semesters (Fall 2013 - Spring 2019), we aimed to determine if there is significant evidence that **first-year students consume more water per person** than upperclassmen. This analysis contributes to ongoing efforts to promote **sustainability** on campus.

---

## **Objectives**

The main objectives of this study are:
- To obtain a general understanding of the **difference in water consumption** between first-year students and upperclassmen.
- To assess whether **first-year students consume more water per person** than upperclassmen.

---

## **Introduction**

Water usage is an important indicator for evaluating sustainability in institutions. At Dickinson College, various efforts have been made to reduce water consumption, such as the installation of **water bottle filling stations** and the initiatives led by the **Alliance for Aquatic Resource Monitoring (ALLARM)**. Our research extends this focus by analyzing whether specific student groups (first-years vs. upperclassmen) differ in their water usage, helping guide future resource conservation strategies on campus.

---

## **Data Collection**

The data used in this study was obtained from the Center for Sustainability Education at Dickinson College and consists of monthly water usage, recorded in **centum cubic feet (CCF)** for each building on campus from **June 2011 to June 2021**.  
- **Semesters covered**:  
  - **Spring**: January through May  
  - **Fall**: September through December  
- **Excluded Data**: Spring and Fall 2020 semesters were excluded due to the reduced campus population during the COVID-19 pandemic, which would have skewed results.

Data was further processed to reflect **water consumption per person** by filtering the records based on whether the buildings housed first-year or upperclassmen students, and then averaging the values across semesters. The buildings included:
- **First-Year Buildings**: Adams, Armstrong, Atwater, Longsdorf, Drayer, Baird McClintock, Spradley-Young, Conway
- **Upperclassmen Buildings**: Goodyear, Malcolm, Morgan, McKenney, Kisner-Woodward, Buchanan

---

## **Methods**

The analysis used a two-sample t-test to compare the mean water consumption per person between first-year students (\( \mu_1 \)) and upperclassmen (\( \mu_2 \)) over the 10 semesters, using unequal variances. The null hypothesis (\( H_0 \)) was that there is no difference in water consumption between the two groups, while the alternative hypothesis (\( H_1 \)) stated that first-year students consume more water.

- **Null Hypothesis (\( H_0 \))**: \( \mu_1 - \mu_2 = 0 \)  
- **Alternative Hypothesis (\( H_1 \))**: \( \mu_1 - \mu_2 > 0 \)

**Test Statistic Results**:
- **t-value**: 2.13
- **Degrees of Freedom**: 16
- **p-value**: 0.024521

The **p-value** is less than 0.05, meaning we reject the null hypothesis at a 95% confidence level. This provides moderate evidence that first-year students consume more water per person than upperclassmen.

---

## **Results and Conclusion**

- Based on the statistical analysis, we concluded that **first-year students consume more water per person** than upperclassmen.
- **Reasoning**: Upperclassmen may consume less water due to their increased exposure to Dickinson's sustainability initiatives over time, making them more conscious of their water usage.
- This raises important questions about how to reduce water consumption, particularly among first-year students:
  - Could installing **automatic sensor faucets** in residential buildings help reduce water consumption?
  - Are there significant differences in water usage across different types of facilities (e.g., bathrooms)?

---

## **Figures**
- **Figure 1**: Screenshot of water usage per person, grouped by first-year and upperclassmen buildings for each semester.
- **Figure 2**: Line graph showing water usage per semester for both groups.
- **Figure 3**: Bar graph comparing mean water usage between the two groups.
- **Figure 4**: Normal Q-Q plot indicating a positive, linear relationship in the dataset.
- **Figure 5**: Shapiro-Wilk test results indicating that the water usage data for upperclassmen follows a normal distribution, while that for first-year students does not.

---

## **Further Research Questions**

- How can we **further reduce water consumption** among first-year students?
- Would installing **automatic sensor faucets** reduce water usage significantly?
- Should future studies consider comparing water consumption based on specific building facilities (e.g., bathroom, laundry room)?

---

## **Acknowledgments**

We would like to thank:
- **Center for Sustainability Education** at Dickinson College for providing the water usage data.
- **Residence Life and Housing** for the occupancy data.

---

## **References**
1. Water usage data was provided by the **Center for Sustainability Education** at Dickinson College on April 6, 2023.
2. Occupancy data was provided by **Residence Life and Housing** at Dickinson College on April 25, 2023.


