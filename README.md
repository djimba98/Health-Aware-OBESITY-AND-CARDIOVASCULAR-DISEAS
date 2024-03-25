# Health-Aware-
## OBESITY AND CARDIOVASCULAR DISEASES

## Table Of Contents

- [Project Overview](#project-overview)
- [Data Sources](data-spurces)
- [Reccomendations](reccomendations)


### Project Overview
I have conducted a thorough analysis of the data regarding obesity and its correlation with cardiovascular diseases. Through this analysis, I have gained valuable insights that can greatly contribute to the campaign for promoting healthier lifestyles. By understanding the intricate relationship between obesity and cardiovascular diseases, we can tailor our strategies more effectively to encourage better living practices and prevent the onset of these debilitating conditions.

![image](https://github.com/djimba98/Health-Aware-OBESITY-AND-CARDIOVASCULAR-DISEAS/assets/164912911/e0a6a547-5b95-4c14-9bd3-04801096c745)



### Data Sources 

Sales data: The seconday dataset used for this analysis is the "HGealth data - analysis", containing detailed information about each record  from the survey.

### Tools

- Excel - Data Cleaning - Data analysis - Data charts
- Power BI - Creating Report

### Data Cleaning Preparation

In the initial data preparation phase, I performed the follwing tasks:
1. Data laoding and inspection
2. Handling missing values
3. Data cleaning and formatting

### Exploratory Data Analysis (EDA)

EDA  Involved exploring the data to provide insights such as:

- Which body type appears most frequently in the dataset?
- How does the correlation between weight and height influence body weight?
- Does snacking between meals have an impact on body weight?
- What implications exist between gender and family history of previous health diseases?
- Do individuals who monitor their food consumption understand the implications of smoking? If so, what is the correlation?
- How dispersed is the dataset in terms of its variability and distribution?

### Data Analysis

Include interesting features worked with Excel using Pivot Table/Charts and Slicers

### Results/Findings
 It was discovered that Obesity Type I is the most common body type in the population under investigation. This distribution gives a thorough picture of how common each weight category is in the population.
Through the process of combining the numbers of individuals in each of the three types of obesity (Type I, Type II, and Type III), we are able to determine the total number of people who are obese in the community. This realisation is essential to comprehending the population's health state and could provide the foundation for public health initiatives.

Information on the distribution of overweight people and the severity of overweight in the population may be gleaned from an examination of the numbers of people in the two overweight levels (Overweight Level I and Overweight Level II). 

Studies from The House of Commons Library show that the likelihood of becoming overweight or obese increases with age. In addition, I determined how many people under 40 had either normal or insufficient weight using the COUNTIFS function. The outcome, which includes 547 people, points to a possible future risk of weight issues in this population.

Individuals with a family history of overweight exhibit higher counts across all weight categories compared to those without such a history.
This suggests a significant influence of family history on the likelihood of developing obesity, as evidenced by the higher counts in the "YES" category across all weight classifications.

Among individuals with a family history of overweight the counts are notably higher across the obesity types (Obesity_Type_I, Obesity_Type_II, and Obesity_Type_III) compared to those without such a history.
This indicates that individuals with a family history of overweight are more likely to develop various types of obesity, including severe forms such as Obesity_Type_III.

The Combined Prevalence is the total number of people in each weight category who do not have a family history of overweight (the "NO" group) at 365 and the total number of people who do have a family history of overweight. The notable disparity in counts highlights the noteworthy impact of family history on the general occurrence of obesity and overweight in the community under investigation. 
Implications for Prevention and Intervention:
The information emphasises how crucial it is to take family history into account while attempting to prevent and treat obesity. Those with a family history of obesity may require specialised interventions to manage their increased risk and stop the onset or advancement of obesity-related health problems.

Correlation between Height and Weight: Coeficcient of variation valued at 0.45 which states a moderate correlation between height and weight. The taller an individual is, the more he weights. 
Outliers: No outliers which means no value that contanis figures out the normal.

### Reccomendations

- Health Intervention Programs: Implement targeted health intervention programs aimed at addressing the prevalence of obesity,  focusing on individuals classified under Obesity Type I. These programs could include educational campaigns on healthy eating habits, regular physical activity, and lifestyle modifications.
- Early Intervention for Overweight Individuals: Given the findings regarding the distribution of overweight individuals, consider early intervention strategies targeting those in Overweight Level II, as they may be at higher risk for obesity-related health issues. These interventions could involve personalized diet and exercise plans, as well as access to support groups or counseling services.
- Youth Health Initiatives: Develop initiatives aimed at promoting healthy lifestyles among younger individuals, especially those under the age of 40 identified as potentially at risk for weight disorders. This could involve school-based programs, community events, or digital platforms offering resources and support for maintaining a healthy weight.
Regular Monitoring and Assessment: Establish a system for regular monitoring and assessment of weight-related trends within the population. This could involve conducting periodic surveys or assessments to track changes in obesity prevalence and overweight levels over time, allowing for timely adjustments to intervention strategies.
Policy and Environmental Changes: Advocate for policy and environmental changes that support healthy lifestyles, such as improving access to nutritious food options and sharing benefits of physical activities.

### Limitations

- Implemented data cleaning procedures to rectify discrepancies.
- Standardized height and weight values to maintain uniformity, recording measurements to 5-6 digits after the second decimal point.
- Adjusted age to include only two digits for consistency.
- Addressed inconsistencies in FAVC and CALC by converting '0' to 'NO' and 'No' to 'Never', respectively.
- Consolidated variations in the method of transport into a single category.
- Identified and removed duplicate entries to eliminate redundancy and ensure dataset integrity.
