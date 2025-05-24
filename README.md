# Data_Exploratory_Analysis_Hypthesis_Testing_Insurance_claim_data
Exploratory Data Analysis and Hypothesis Testing on Insurance Claims
This project involves performing an in-depth Exploratory Data Analysis (EDA) and Hypothesis Testing on insurance claims data to derive actionable business insights. By integrating customer and claim data, we aim to create a 360-degree view of customer behavior and claims patterns to support better decision-making in the insurance domain.
### Key Objectives
#### 1.Data Cleaning and Preparation

Audit data types and resolve inconsistencies.

Convert monetary fields (e.g., claim_amount) to numeric formats.

Identify and flag injury claims not reported to the police.

De-duplicate records based on customer ID, keeping the most recent claim.

Impute missing values using suitable statistical methods (mean/mode).

#### 2.Feature Engineering

Calculate customer age and classify into age categories:

Children (<18)

Youth (18–30)

Adult (30–60)

Senior (>60)

#### 3.Descriptive and Diagnostic Analysis

Compute average claim amount across customer segments.

Aggregate total claim amount by incident cause (claims ≥ 20 days before Oct 1, 2018).

Analyze driver-related claims from specific states (TX, DE, AK).

Visualize gender and segment-based claim amounts using pie charts.

Identify which gender and age group had more driver-related and fraudulent claims.

Analyze monthly trends in total claim amount.

#### 4.Advanced Visualization

Bar charts, facetted bar charts, and chronological line charts to uncover hidden patterns in data.

#### 5.Hypothesis Testing

Are claim amounts significantly different between males and females?

Is there a statistical relationship between age category and customer segment?

Has the average claim amount increased compared to the 2016–17 fiscal average ($10,000)?

Is there a significant difference in claim amounts across age groups?

Does the total number of claims correlate with the claim amount?

Each hypothesis is tested using appropriate statistical techniques (t-tests, ANOVA, Chi-square, etc.), with a clear explanation of:

Null and alternative hypotheses

Chosen significance level

Test results and p-values

Business interpretation and implications

