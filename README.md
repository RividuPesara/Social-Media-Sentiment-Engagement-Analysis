# Social Media Sentiment & Engagement Analysis

This is a small learning project I completed to practice data cleaning in Python and build my first Power BI dashboard

## Project Overview

- **Data Source:** Synthetic social media dataset with posts, likes, retweets, and platform details.
- **Tools Used:** 
  - Python (Jupyter Notebook)
  - Power BI
- **Main Goals:**
  - Clean and prepare social media text data
  - Analyze sentiment trends and engagement
  - Visualize global and platform-specific activity patterns

## Project Workflow

### Phase 1: Data Preparation in Python
- Loaded raw data (CSV)
- Cleaned text columns (lowercase, removed punctuation, etc.)
- Extracted hashtags
- Added time based columns (Year, Month, Hour, Day)
- Created **Engagement Score:** `Likes + 2 * Retweets`
- Labeled sentiments as **Positive / Neutral / Negative**
- Exported cleaned data 


###  Phase 2: Power BI Dashboard

**Basic Visuals:**
- Sentiment Distribution Pie Chart 
- Posts Over Time  Line Chart
- Country Map Filled Map showing posts in each country
- Top Platforms  Donut Chart
- Heatmap of activity by Hour and Day


## How to Use
1. Clone this repository
2. Run the Jupyter Notebook to generate the cleaned data
3. Import `cleanedSentimentDataset.csv` into Power BI Desktop
4. Build your own visuals using the prepared fields
