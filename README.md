# Project Background
#### The company is a mid-sized retail bank offering everyday financial products such as current accounts, savings accounts, credit cards, and personal loans to consumers across multiple countries. As part of its routine customer management processes, the bank collects detailed information on customer demographics, financial behavior, product usage, credit characteristics, and whether a customer eventually closes their account.
#### This project analyzes that customer-level data to understand the patterns and drivers behind customer churn (account closure) and builds evidence-based insights to help the bank reduce attrition. The analysis will focus on identifying key risk segments, diagnosing the underlying reasons customers leave, and generating targeted recommendations to improve customer retention.
#### The insights and recommendations will center on three key areas:
#### - Customer Engagement — identifying inactive or low-interaction customers who may require proactive outreach.
#### - High-Risk Segments — pinpointing demographic or geographic groups with disproportionate churn rates to guide targeted retention programs.
#### - Financial & Product Behavior — understanding how factors like balance levels, number of products, and credit activity relate to churn to inform cross-sell and loyalty strategies.

## Overview of Findings
#### Analysis of the bank’s customer churn dataset reveals several clear behavioral, demographic, and geographic patterns that explain why certain customers leave more frequently than others. These patterns highlight both risk segments and strategic opportunities for targeted retention efforts.

### 1. Churn rate is uneven and concentrated among specific customer segments
#### The dataset shows a churn rate near 20%, which aligns with typical retail-bank churn levels but still represents a significant financial risk. Although only a minority of customers leave, their potential lifetime value — especially high-balance customers — makes churn a critical focus area.

### 2. Age is one of the strongest churn drivers
#### The relationship between age and churn forms a distinctive pattern:
#### - Highest churn: 40-60 years old
#### - Lowest churn: under 30 and over 60
#### This middle-age bracket often includes high-earning, high-balance customers with multiple product needs. They also have higher expectations for digital services and competitive offerings, making them more likely to switch providers if dissatisfied.

![Churn Heatmap] (https://github.com/wingkeewinniekwok-max/Project-1/blob/main/ImageAge)

### 3. Geography is a major structural predictor
#### Geography shows one of the strongest effects in the entire dataset:
#### - Germany: highest churn
#### - France & Spain: significantly lower
#### This suggests competitive dynamics, product fit, or customer experience challenges specific to the German market. This region presents a clear and immediate opportunity for targeted intervention.

### 4. Product holding reveals a “sweet spot”
#### The number of products held has a non-linear effect:
#### - Customers with 1 product churn more → weak engagement
#### - Customers with 2 products churn least → optimal engagement
#### - Customers with 3–4 products churn increases again → possible overselling
#### This suggests that thoughtful cross-selling improves retention, but aggressive upselling may damage customer satisfaction.

## Executive Summary
#### The analysis shows that customer churn is concentrated within specific high-risk segments rather than spread evenly across the bank’s portfolio, answering the central question of which customers are most likely to leave and why. Churn is highest among customers in Germany, inactive members, mid-aged individuals (40–60), high-balance clients, and those holding only one product—groups that are both financially valuable and operationally strategic. Gender, salary, and credit score play minimal roles, while tenure reveals that new and very long-tenure customers require additional attention. These findings indicate that the bank can meaningfully reduce churn by focusing on targeted engagement for inactive customers, improving onboarding and long-term relationship management, and addressing competitive or service-related factors in high-churn regions, particularly Germany.

## Recommendations
#### 1. Re-engage inactive customers through targeted activation campaigns (app reminders, personalized offers, loyalty incentives), as inactivity is one of the strongest churn drivers.
#### 2. Prioritize high-balance and mid-aged customers (40–60) with proactive outreach and tailored financial solutions, since these high-value clients churn at disproportionately higher rates.
#### 3. Investigate and address issues in the German market, where churn is significantly higher, by analyzing competitive pressures, service gaps, or product fit unique to that region.
