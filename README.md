# Social Media Content Performance & Growth Analysis

## Project Overview
This project analyzes Instagram post performance data to identify key drivers of **engagement, reach, and audience growth**.  
The objective is to deliver **data-driven insights and actionable recommendations** to optimize content strategy and posting behavior.

The analysis answers the following business questions:
- What types of content perform best?
- When is the best time to post?
- How do captions, hashtags, and traffic sources impact performance?
- What differentiates viral posts from low-performing posts?

## Dataset Description
The dataset contains **29,999 Instagram posts** with structured information including:

- Engagement metrics: likes, comments, shares, saves
- Exposure metrics: reach, impressions
- Content metadata: media type, content category
- Posting time details
- Traffic sources
- Performance labels (Low, Medium, High, Viral)

A cleaned and feature-engineered dataset was used for analysis and dashboard development.

## Tools & Technologies
- **Python**
- **Pandas, NumPy**
- **Matplotlib, Seaborn**
- **Power BI**
- **GitHub**

## Analysis Workflow
The project follows a structured analytics workflow:

1. **Data Understanding & Cleaning**
   - Verified data completeness and quality
   - Converted datetime fields
   - Validated engagement metrics

2. **Feature Engineering**
   - Created time-based features (posting hour, day of week, weekend flag)
   - Engineered total engagement and engagement rate metrics

3. **Exploratory Data Analysis (EDA)**
   - Engagement and reach distributions
   - Content type and category analysis
   - Posting time analysis
   - Caption and hashtag impact
   - Traffic source comparison

4. **Performance Segmentation**
   - Compared Low, Medium, High, and Viral posts
   - Identified key characteristics of viral content

5. **Business Insights & Recommendations**
   - Translated analytical findings into actionable strategies

## Key Insights
- Engagement is **similar across images, carousels, and reels**, indicating content quality matters more than format.
- **Food, Photography, and Fashion** content shows higher viral potential.
- Engagement peaks during **early morning (3–5 AM)** and **evening (6–8 PM)** hours.
- Posting performance is fairly consistent across weekdays, with **Sunday performing slightly better**.
- Caption length shows **no strong linear relationship** with engagement.
- Posts with **5–10 relevant hashtags** achieve higher reach.
- Traffic source has **limited impact** compared to content quality.
- Viral posts generate significantly higher engagement and reach due to strong audience interaction.

## Strategic Recommendations
- Focus on **high-quality, relevant content** rather than a single media format.
- Post during **early morning and evening peak hours**.
- Use **clear and concise captions** that deliver value quickly.
- Apply **5–10 targeted hashtags** to maximize reach.
- Encourage **saves and shares** through educational or value-driven content.
- Regularly analyze viral posts to replicate successful patterns.

## Power BI Dashboard
An interactive Power BI dashboard was developed with the following pages:

- Performance Overview  
- Content Type Analysis  
- Best Posting Time  
- Traffic Source Impact  

**Dashboard file:**  
`dashboard/instagram_content_dashboard.pbix`

## Author
**Umindu Nimsara**  
Aspiring Data Analyst