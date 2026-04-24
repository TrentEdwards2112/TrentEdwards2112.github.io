---
layout: post
title: Mortgage Loan Pipeline Risk & Prioritization Dashboard
tags: [Tableau, SQL, Data Analytics, Mortgage]
---

<img src="/img/posts/your-new-image.png" 
     style="width:100%; max-width:1100px; display:block; margin: 20px auto 30px auto; border-radius:6px;">

This project analyzes mortgage loan pipeline data to help underwriting teams identify risk, prioritize work, and manage loan flow across stages.

## Business Problem

Underwriting teams must quickly identify high-risk and time-sensitive loans while maintaining steady pipeline throughput. Without clear visibility into risk drivers and bottlenecks, teams can struggle to prioritize effectively and meet critical deadlines.

## What This Dashboard Answers

- Where is risk concentrated across the pipeline?
- What factors are driving loan urgency and delays?
- Which loans should be prioritized first?
- Where are operational bottlenecks forming?

## Key Insight

Aging pipeline loans drive the largest workload, while LE Past Due loans represent the highest immediate operational risk—indicating a need to balance volume management with time-sensitive prioritization.

## Tools Used

- SQL (MySQL) – data preparation and transformation
- Tableau Public – visualization and dashboard design

## Approach

- Cleaned and structured loan-level data using SQL (MySQL)
- Created derived fields to categorize risk, urgency, and pipeline stages
- Designed visualizations in Tableau to highlight risk concentration, drivers of urgency, and operational bottlenecks

## Dashboard Overview

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
