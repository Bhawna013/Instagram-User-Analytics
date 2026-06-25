# Instagram User Analytics – SQL Project

## Project Overview

Social media platforms generate millions of user interactions every day through account registrations, posts, likes, comments, and hashtags. Analyzing this data helps product, marketing, and trust & safety teams understand user behavior, optimize engagement strategies, and maintain platform quality.

In this project, SQL was used to analyze an Instagram user dataset to answer real-world business questions related to user engagement, content performance, campaign planning, and suspicious user activity. Rather than simply querying data, the objective was to translate raw data into actionable business insights that support strategic decision-making.

-----

## Business Objective

This analysis focuses on solving business problems across multiple teams within a social media company.

**Marketing**
- Identify trending hashtags for better campaign reach.
- Determine the best time to launch marketing campaigns.
- Recognize highly engaged users for loyalty and influencer initiatives.

**Product**
- Measure user engagement and content creation behavior.
- Evaluate user activation after registration.
-  Understand platform growth patterns.

**Trust & Safety**
- Detect suspicious user behavior.
- Identify potential fake or automated accounts that may distort engagement metrics.

------

## Dataset 

The dataset contains information about:

- Users
- Photos
- Likes
- Comments
- Hashtags
- Photo Tags

These relational tables were analyzed using SQL joins, aggregate functions, window functions, filtering, grouping, and ranking techniques to answer business questions


--------

## Business Questions and Analysis

1. **Identifying Loyal Users**

**Business Question**
- Who are Instagram's earliest users?

**Why this analysis?**
- Long-term users often represent the platform's most loyal customer base. Recognizing these    users helps marketing teams design loyalty programs, exclusive rewards, and community engagement initiatives.

**SQL Approach**
- Sorted users by account creation date and selected the earliest registered accounts.

**Insight**
- The five oldest registered users were identified as the platform's earliest adopters.

**Business Impact**
- Strengthen customer retention.
- Reward loyal users.
- Build stronger community engagement.

---
2. **Identifying Inactive Users**

**Business Question**
- Which registered users have never uploaded a photo?

**Why this analysis?**
- Inactive users may indicate poor onboarding experiences or product friction. Measuring activation helps product teams evaluate whether users successfully adopt the platform after registration.

**SQL Approach**
- Performed a LEFT JOIN between the Users and Photos tables to identify users without uploaded content.

**Insight**
- No users were found with zero posts, indicating successful user activation across the dataset.

**Business Impact**
- Demonstrates effective onboarding.
- Suggests users actively participate after registration.
- Indicates a healthy level of platform engagement.

---
3. **Finding the Most Engaging Content**

**Business Question**
- Which post received the highest number of likes?

**Why this analysis?**
- Highly engaged content provides valuable insights into audience preferences and helps identify creators capable of driving user interaction.

**SQL Approach**
- Counted likes for each photo and ranked posts by total engagement.

**Insight**
- The post created by Zack_Kemmer93 received the highest number of likes.

**Business Impact**
- Identify potential influencers.
- Understand characteristics of high-performing content.
- Support creator partnership programs.

---
4. **Analyzing Hashtag Trends**

**Business Question**
- Which hashtags are used most frequently?

**Why this analysis?**
- Hashtags increase content discoverability and organic reach. Understanding trending hashtags allows marketing teams to improve campaign visibility.

**SQL Approach**
Joined hashtag-related tables and counted hashtag usage frequency.

**Insight**
The most frequently used hashtags included:
- Sunset
- Sunrise
- Style
- Stunning
- Smile

**Business Impact**
- Improve campaign reach.
- Optimize hashtag strategy.
- Increase content visibility.

---
5.**Understanding User Registration Patterns**

**Business Question**
- On which day do users register most frequently?

**Why this analysis?**
- Knowing when users are most likely to join the platform helps marketing and product teams schedule launches, promotions, and advertising campaigns.

**SQL Approach**
- Grouped user registrations by weekday and calculated registration counts.

**Insight**
- Friday recorded the highest number of user registrations.

**Business Impact**
- Launch campaigns during peak acquisition periods.
- Schedule product releases strategically.
- Improve advertising efficiency.

---
6.**Measuring User Engagement**

**Business Question**
- How actively do users contribute content?

**Why this analysis?**
- Posting frequency is an important engagement metric that reflects overall platform activity.

**SQL Approach**
- Calculated the average number of photos uploaded per user.

**Insight**
- Users uploaded an average of 2.57 photos per user.

**Business Impact**
- Establishes a baseline engagement KPI.
- Enables future comparison after product improvements.
- Supports long-term engagement tracking.

---

7. **Detecting Fake or Bot Accounts**

**Business Question**
- Can abnormal engagement patterns reveal fake accounts?

**Why this analysis?**
- Bots artificially inflate engagement metrics, reduce recommendation quality, and negatively affect platform trust.

**SQL Approach**
- Identified users who liked every available photo, an activity pattern considered highly unlikely for genuine users.

**Insight**
- More than 13 accounts displayed suspicious engagement behavior.

**Business Impact**
- Improve platform integrity.
- Enhance recommendation quality.
- Support fraud detection and account verification processes.

---

 ## Key Business Insights

- Friday is the strongest day for new user registrations, making it an ideal time for campaign launches.
- Trending hashtags reveal popular content themes that can improve marketing reach.
- Users actively upload content after registration, indicating successful user activation.
- Average posting behavior establishes a measurable engagement benchmark.
- Highly engaged creators can be targeted for influencer collaborations and loyalty programs.
- Suspicious engagement patterns help identify potential bot accounts, improving platform trust and data quality.

------

## Business Value

This project demonstrates how SQL can be applied to solve practical business problems rather than simply querying data. The analysis connects technical SQL skills with business decision-making across marketing, product analytics, and trust & safety.

The project highlights the ability to:
- Translate business requirements into SQL queries.
- Analyze user behavior using relational data.
- Generate actionable insights for business stakeholders.
- Present findings that support data-driven decision-making.

---
## Key Learnings
1. Applied SQL to answer real-world product and marketing questions.
2. Strengthened understanding of user engagement metrics.
3. Improved proficiency in relational database querying and aggregation.
4. Practiced translating technical analysis into business recommendations.
5. Developed experience in data storytelling by connecting analytical findings with business outcomes.





