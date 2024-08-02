# Blackspot Prediction in Victoria Project Overview

#### Executive Summary
This project addresses the critical issue of road accident blackspots in Victoria by leveraging data-driven insights to develop effective interventions, education campaigns, and legislative reforms. Utilizing a comprehensive dataset, the initiative aims to enhance road safety by identifying risk factors and patterns associated with blackspots. The analysis provides actionable insights for stakeholders, including the Victorian Department of Transport (DOT), local authorities, and the general public, to make informed decisions that lead to safer roads and reduced accidents.

#### Business Understanding
The primary objective is to reduce road accidents by identifying blackspots—areas with high accident rates. The project employs the Business Analysis Core Concept Model (BACCM) to guide the process, emphasizing the need for targeted measures, stakeholder involvement, and practical value. Key stakeholders include:
- **Victorian Department of Transport (DOT)**: Seeks actionable insights to enhance road safety.
- **General Public**: Ultimate beneficiaries who will experience safer roads.
- **Local Authorities**: Collaborators in implementing education campaigns, legislative reforms, and interventions.

#### Data Understanding and Cleansing
The dataset integrates crash data from the DOT and demographic data from the Australian Bureau of Statistics (ABS), comprising 5326 records across 36 attributes. Key steps in data cleansing included:
- Dropping irrelevant columns.
- Handling missing values by replacing them with the median.
- Converting categorical data to numerical formats.
- Setting consistent formatting for floating numbers.

#### Data Visualization and Insights
- **Primary Schools**: Proximity to primary schools significantly increases the likelihood of blackspots.
- **Traffic Signals**: Areas with traffic signals show a higher percentage of blackspots.
- **Household Car Ownership**: Higher blackspot rates are associated with areas where households have no cars.

#### Machine Learning Model Implementation
A logistic regression model was employed due to its suitability for binary classification. The model's performance metrics included:
- **Confusion Matrix**: High precision and recall for non-blackspots, but lower recall for blackspots.
- **Classification Report**: Overall accuracy of 0.91, with high precision (0.92) and recall (0.98) for non-blackspots, and lower precision (0.73) and recall (0.36) for blackspots.
- **ROC Curve and AUC**: The ROC curve indicated good model performance, with an AUC of 0.87.

#### Pros and Cons
**Pros**:
- High precision and recall for non-blackspots.
- Reasonable overall accuracy.
- Interpretability of coefficients.
- High AUC indicating strong classification ability.

**Cons**:
- Low precision and recall for blackspots.
- Class imbalance impacting model performance.

#### Solutions and Recommendations
**Solutions**:
- **Data-Driven Interventions**: Utilize the logistic regression model to identify high-risk blackspots and prioritize interventions.
- **Education Campaigns**: Tailor campaigns to address specific risk factors like primary schools and traffic signals.
- **Legislative Reforms**: Present evidence-based findings to support proposed legislative changes.
- **Real-Time Monitoring**: Implement a system to continuously assess and update risk predictions based on new data.

**Recommendations**:
- **Additional Data Collection**: Incorporate weather, traffic flow, and road design data to enhance model accuracy.
- **Model Refinement**: Regularly update and retrain the model to reflect new data and changing conditions.
- **Stakeholder Collaboration**: Work closely with local authorities and the DOT to implement and measure the impact of interventions.

In conclusion, this project provides actionable insights to tackle road safety concerns and drive positive change, ensuring safer roads and reduced accidents in Victoria.
