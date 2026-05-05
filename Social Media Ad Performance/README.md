# Social Media Ad Performance Analysis

## Intro and Data Source

This analysis is aimed to examine how advertisements on social media perform, and identify the patterns if there's any. We wanted to apply funnel analysis on users based on their activities, and analyze campaign performances based on CTR (Click-Through Rate), CVR (Conversion Rate) and other metrics. 

This dataset is sourced from Kaggle: *Social Media Advertisement Performance* by Alperen Atik.  (https://www.kaggle.com/datasets/alperenmyung/social-media-advertisement-performance) The dataset is sourced from a SQLite file, which is not included in this repository due to file size limitations. It can be downloaded from the link provided here. For convenience, the data is also available in CSV format in this folder.
## Insights

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

