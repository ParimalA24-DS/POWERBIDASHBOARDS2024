# LinkedIn Profile Analytics Dashboard
![LinkedIn Profile Dashboard](https://github.com/ParimalA24-DS/POWERBIDASHBOARDS2024/blob/main/6.LinkedinProfileANlaytics/LinkedinDAAug24imp.PNG)

## Overview
This Power BI project delivers a comprehensive analysis of LinkedIn profile data, providing actionable insights to enhance personal and professional networking. The dashboard is designed to monitor engagement metrics, track connection growth, and identify key influencers within your network.

## Problem Statement
As a data professional, the challenge is to extract, clean, and analyze LinkedIn data to generate actionable insights for improving networking strategies. The project focuses on:
- Understanding engagement metrics (likes, shares, reactions).
- Monitoring connection growth over time.
- Identifying top influencers and companies in your network.

## Learning Outcomes
- **Data Extraction**: Techniques for importing LinkedIn data into Power BI.
- **Data Transformation**: Methods for cleaning and transforming data for accuracy.
- **Measure Creation**: Creating custom measures to track endorsements, shares, and reactions.
- **Calendar Table Creation**: Building a calendar table to enable time-based analysis.

## Key Performance Indicators (KPIs)
1. **Total Connections by Month**: Measures monthly growth in LinkedIn connections.
2. **Top 10 Companies by Connections**: Identifies companies with the highest connection counts.
3. **Top 5 Positions Held by Connections**: Highlights common job roles within your network.
4. **Engagement Metrics (Likes, Shares, Reactions)**: Assesses post effectiveness through interactions.
5. **Endorsements**: Total endorsements.
6. **Follower Growth**: Monitors LinkedIn follower increases over time.
7. **Invitation and Messages**: Counts incoming and outgoing  connection requests.

## Data Preparation
- **Data Cleaning**: Removing duplicates, handling missing values, and ensuring data consistency.
- **Data Transformation**: Filtering, merging tables, and creating new columns or measures for analysis.
### Data Modeling Overview
![Data Modeling Overview](https://github.com/ParimalA24-DS/POWERBIDASHBOARDS2024/blob/main/6.LinkedinProfileANlaytics/LINKEDIN_DATAMODELING.PNG)

## Key Measures and DAX Formulas
- **Calendar Table**:
  Contact me for all DAX functions
  ```dax
- Messages Sent = CALCULATE(COUNTA(messages[FROM]), FILTER(messages,messages[FROM] = "PARIMAL AUTADE"))

- Messages Received = CALCULATE(COUNT(messages[FROM]), NOT(messages[FROM] IN {"PARIMAL AUTADE"}))
  ---
## Contact Information
For dataset and detailed DAX expressions, feel free to reach out to me:
- **Email**: parimalautade23@gmail.com
- **LinkedIn**: [Parimal Autade](https://www.linkedin.com/in/parimalautade/)
