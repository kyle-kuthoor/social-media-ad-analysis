# Social Media Advertising Performance Analysis

## Overview
An exploratory data analysis of 255,000 social media ad campaigns 
across Instagram, Facebook, Twitter, and Pinterest. The analysis 
examines ROI, conversion rates, and engagement across platforms, 
campaign goals, and customer segments to identify what actually 
drives advertising performance.

## Tools Used
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Key Findings
- Instagram delivers the highest average ROI (4.01) while Pinterest 
  consistently underperforms at 77.5% below the campaign average
- Conversion rates are virtually identical across all four campaign 
  goals (within 0.0003 of each other), suggesting creative quality 
  and audience targeting matter more than campaign objective
- Engagement scores are uniform across all customer segments, 
  meaning broad targeting may be as effective as highly segmented campaigns
- Pinterest underperforms across every goal and every segment — 
  making it the clearest candidate for budget reallocation

## Context
This analysis was motivated by hands-on experience in digital marketing 
analytics, tracking campaign performance across Google Analytics and 
Meta Ads Manager for multiple clients.

## Dataset
Social Media Advertising Dataset via Kaggle (300,000 rows, 16 columns)
Covers campaigns from January to December 2022.

## Files
- `social-media-ad-analysis.ipynb` — full analysis notebook
- `roi_by_platform.png` — ROI comparison across platforms
- `conversion_by_goal.png` — conversion rates by campaign goal
- `engagement_by_segment.png` — engagement by customer segment
- `roi_heatmap.png` — ROI heatmap across platform and campaign goal
