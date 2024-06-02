# Heart Health Insight: Predictive Modeling and Trend Analysis of Heart Disease and Medicare Claims
This project combines predictive modeling and time series analysis to provide comprehensive insights into heart disease risk factors and trends in Medicare claims related to heart disease and stroke prevention. By leveraging two distinct datasets, we aim to identify key predictors of heart disease, analyze historical trends in healthcare claims, and forecast future claims to support effective healthcare planning and intervention strategies.

## Dataset
**1st Dataset**
Heart Disease Dataset

***About Dataset***

*Context*

This data set dates from 1988 and consists of four databases: Cleveland, Hungary, Switzerland, and Long Beach V. It contains 76 attributes, including the predicted attribute, but all published experiments refer to using a subset of 14 of them. The "target" field refers to the presence of heart disease in the patient. It is integer valued 0 = no disease and 1 = disease.

***Content***

*Attribute Information:*

1. age
2. sex
3. chest pain type (4 values)
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

The names and social security numbers of the patients were recently removed from the database, replaced with dummy values.

***Dataset Link:*** [Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

**2nd Dataset**
Medicare Heart Disease and Stroke Prevention Claims Data

***About Dataset***

*Context*

This dataset consists of Medicare Heart Disease and Stroke Prevention Claims Data, compiled by the Center for Medicare & Medicaid Services (CMS). It includes claims data for Medicare and Medicaid patients from 2004 onward, covering a variety of categories such as inpatient and outpatient claims, Master Beneficiary Summary Files, and more.

***Columns and Their Descriptions:***

1. **year**:
   - **Type**: year
   - **Description**: The year in which the data was collected.

2. **state_abbreviation**:
   - **Type**: string
   - **Description**: The abbreviation of the state where the data was collected.

3. **state**:
   - **Type**: string
   - **Description**: The full name of the state where the data was collected.

4. **disease_topic**:
   - **Type**: string
   - **Description**: The specific topic related to heart disease or stroke covered by the data.

5. **disease_indicator**:
   - **Type**: string
   - **Description**: An indicator of the specific type of heart disease or stroke.

6. **data_value_unit**:
   - **Type**: string
   - **Description**: The unit of measurement for the data value (e.g., percentage, rate).

7. **data_value**:
   - **Type**: decimal
   - **Description**: The actual value of the data point.

8. **confidence_limit_low**:
   - **Type**: decimal
   - **Description**: The lower bound of the confidence interval for the data value.

9. **confidence_limit_high**:
   - **Type**: decimal
   - **Description**: The upper bound of the confidence interval for the data value.

10. **breakout_category**:
    - **Type**: string
    - **Description**: The category for which the data is broken out (e.g., age group, gender).

11. **breakout_variables**:
    - **Type**: string
    - **Description**: Specific variables within the breakout category.

12. **topic_id**:
    - **Type**: string
    - **Description**: An identifier for the topic.

13. **indicator_id**:
    - **Type**: string
    - **Description**: An identifier for the disease indicator.

14. **breakout_category_id**:
    - **Type**: string
    - **Description**: An identifier for the breakout category.

15. **breakout_id**:
    - **Type**: string
    - **Description**: An identifier for the breakout variables.

16. **location_id**:
    - **Type**: integer
    - **Description**: An identifier for the location where the data was collected.

*COMMERCIAL LICENSE*

For subscribing to a commercial license for John Snow Labs Data Library which includes all datasets curated and maintained by John Snow Labs please visit https://www.johnsnowlabs.com/marketplace.

***Dataset Link:*** [Medicare Heart Disease and Stroke Prevention Claims Data](https://data.world/johnsnowlabs/medicare-heart-disease-and-stroke-prevention-claims-data)
