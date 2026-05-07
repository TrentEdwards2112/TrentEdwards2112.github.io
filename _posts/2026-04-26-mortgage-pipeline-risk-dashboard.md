---
layout: post
title: Mortgage Pipeline Risk & Prioritization
image: "/img/posts/pipeline_dashboard_thumb.png"
tags: [Tableau, SQL, Data Analytics, Mortgage]
excerpt: "Identifies high-risk loans and prioritization gaps to support time-sensitive and compliance-driven underwriting decisions."
---

<img src="/img/posts/your-new-image.png" 
     style="width:100%; height:auto; display:block; margin:20px auto 30px auto; border-radius:6px;">

Simulates a real-world underwriting environment to identify high-risk loans, surface prioritization gaps, and help teams focus on time-sensitive and compliance-driven work.


## Business Problem

Underwriting teams must identify high-risk and time-sensitive loans while maintaining steady pipeline throughput. Without clear visibility into risk drivers and bottlenecks, teams struggle to prioritize effectively and meet critical deadlines.


## What This Dashboard Answers

- Where is risk concentrated across the pipeline?
- What is driving loan urgency and delays?
- Which loans require immediate prioritization?
- Where are operational bottlenecks forming?


## Key Insight

Aging loans drive the majority of pipeline workload, while LE Past Due loans represent the highest immediate risk—highlighting the need to balance volume management with time-sensitive prioritization.


## Tools Used

- SQL (MySQL): data cleaning, transformation, and feature creation  
- Tableau Public: dashboard development and data visualization  


## Approach

- Cleaned and structured loan-level data using SQL (MySQL) to ensure consistency and usability  
- Created derived fields to classify loan urgency, risk levels, and pipeline stages  
- Designed Tableau visualizations to surface risk concentration, identify urgency drivers, and highlight operational bottlenecks  
- Structured the dashboard to reflect real-world underwriting priorities and decision-making workflows  


## Dashboard Overview

The dashboard provides a centralized view of loan volume, risk distribution, and urgency drivers, enabling teams to assess pipeline health and prioritize actions. This approach mirrors real-world pipeline reporting used to manage risk, optimize workload, and improve operational efficiency.

![Dashboard](/img/posts/pipeline_dashboard.png)


## Live Dashboard

<div style="width:100%; height:850px;">
  <iframe 
    src="https://public.tableau.com/views/MortgageLoanPipelineRiskPrioritizationDashboard/Dashboard1?:embed=y&:showVizHome=no&:display_count=y"
    width="100%" 
    height="100%" 
    frameborder="0">
  </iframe>
</div>

[View Full Screen on Tableau Public](https://public.tableau.com/views/MortgageLoanPipelineRiskPrioritizationDashboard/Dashboard1)

## GitHub Repository

[View this project on GitHub](https://github.com/TrentEdwards2112/mortgage-loan-prioritization-dashboard)
