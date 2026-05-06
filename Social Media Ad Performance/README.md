# Social Media Ad Performance Analysis

## Intro

### Background 

As e-commerce becomes increasingly competitive, businesses are investing more heavily in social media advertising to attract user attention and drive engagement. Users exposed to these ads may interact through clicks, likes, comments, and shares, with the ultimate goal of converting into purchases. Given this context, it is important to evaluate the effectiveness of different campaigns, identify high-performing ones, and understand the key factors driving their success.

### Objective

We aimed to evaluate ad campaign performance and identify key drivers of conversion and ROI. We wanted to apply funnel analysis on users based on their activities, and analyze campaign performances based on CTR (Click-Through Rate), CVR (Conversion Rate), ROI (Return On Investment) and other metrics. 

## Data Overview

This dataset is sourced from Kaggle: *Social Media Advertisement Performance* by Alperen Atik. 
(https://www.kaggle.com/datasets/alperenmyung/social-media-advertisement-performance)

The data is synthetic, and the core of this dataset is a relational database modeled around four key entities:

- **Users**: Detailed individual profiles, including age, gender, country, location, and interests, allowing for granular demographic analysis and segmentation.
- **Campaigns**: High-level campaign data, including budget, duration, and start/end dates, providing the strategic context for all ad-related activities.
- **Ads**: Specific creative assets tied to campaigns, complete with targeting parameters for age, gender, and interests.
- **Ad Events**: The central transactional log, capturing every user interaction from a simple impression to a final purchase — the key to understanding the full conversion funnel.

## Key Insights

This analysis examined social media ad performance across four dimensions: conversion funnel, campaign metrics, user demographics, and temporal patterns. Key findings are as follows:

**1. Conversion funnel highlights a critical drop-off at the click-to-purchase stage.**
The overall impression-to-purchase conversion rate is 0.6%, which falls within a typical range. However, only 5% of users who clicked went on to purchase, suggesting that landing page experience and post-click conversion are the primary areas for improvement.

**2. Campaign performance varies most in CVR and ROI, not CTR.**
CTR is relatively consistent across all campaigns, while CVR and ROI show more meaningful variation. Campaign 42 stands out with an exceptionally high ROI, and Campaign 27 leads in CVR, converting approximately 8 out of every 100 clicks into purchases.

**3. No strong patterns found in top campaign features.**
Top-performing campaigns are distributed across platforms, ad types, target genders, and age groups, with no single feature consistently associated with better performance. Budget size also shows no clear relationship with campaign success. Q3 campaigns show a slightly higher representation among top performers, but this requires further statistical validation.

**4. Platform and demographic differences are largely insignificant.**
Facebook and Instagram show comparable CTR and CVR. Gender and age group also show no meaningful difference in performance. A notable exception is Japan and Mexico, where CVR is higher than average, suggesting these markets may warrant closer attention.

**5. Thursday and Friday are the most active days for high-intent actions.** 
Day-of-week patterns show more variation than time-of-day patterns. Purchases and clicks peak on Thursdays and Fridays, making these the optimal days for ad delivery. Morning tends to see the highest purchase activity within a day, though the overall time-of-day variation is relatively small.

**Limitations**: This dataset is entirely synthetic, which means the patterns observed may not reflect real-world advertising dynamics. Statistical tests (e.g., t-tests, chi-square) were not conducted, so findings should be treated as exploratory rather than conclusive.

## Recommendations

- The relatively low conversion rate from click to purchase suggests that the landing page and post-click experience require further optimization. Efforts should focus on improving user journey, clarity, and purchase friction.

- Platform and demographic factors do not appear to be primary drivers of performance. However, certain markets—such as Japan and Mexico—show relatively higher CVR, indicating potential opportunities for targeted investment and localized strategies.

- User behavior suggests stronger engagement and conversion later in the week. Campaigns should be strategically scheduled on Thursdays and Fridays, when users are more likely to click and convert.
