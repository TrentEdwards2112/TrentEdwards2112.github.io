---
layout: post
title: Mortgage Loan Approval Analysis
image: "/img/posts/mortgage_approval_dashboard.png"
tags: [SQL, Tableau, Data Analytics, Mortgage]
excerpt: "Analyzes mortgage data to uncover key drivers of approval outcomes and borrower risk segmentation."
---

<img src="/img/posts/mortgage_approval_hero.png"
     style="width:100%; height:auto; display:block; margin:20px auto 30px auto; border-radius:6px;">

Analyzes mortgage loan data to uncover key drivers of approval outcomes, identifying how borrower characteristics and loan size influence lending decisions.

## Business Problem

Lenders must evaluate large volumes of loan applications while balancing risk and approval rates. Without clear visibility into what drives approvals and denials, decision-making becomes inconsistent and harder to optimize.

## What This Analysis Answers

- How do approval rates vary by income level?
- What relationship exists between loan size and approval likelihood?
- How do approval rates differ across regions and states?
- What borrower characteristics influence approval outcomes?

## Key Insight

Higher income borrowers show significantly higher approval rates, while larger loan sizes are associated with increased denial rates—highlighting clear segmentation in lending risk. Approval rates range from ~72% for high-income borrowers to ~32% for low-income borrowers, demonstrating a meaningful disparity in approval likelihood.

This analysis provides a practical framework for understanding borrower risk profiles and supports more consistent, data-driven lending decisions.

## Tools Used

- SQL (MySQL): data cleaning, transformation, and feature creation  
- Tableau: dashboard development and visualization  

## Approach

- Cleaned and standardized raw loan data using SQL (MySQL) 
- Created derived fields including income bands and loan size categories  
- Calculated approval rates across multiple dimensions (income, loan size, region)  
- Designed Tableau visualizations to highlight trends and relationships in approval outcomes  

## Dashboard Overview

The dashboard provides a clear view of approval trends across borrower segments, enabling comparison of approval rates by income, loan size, and geographic distribution.

![Dashboard](/img/posts/Mortgage_approval_full_dashboard.png)

## Live Dashboard

<div style="width:100%; height:850px;">
  <iframe 
    src="https://public.tableau.com/views/MortgageLoanApprovalAnalysis_17756756057450/Dashboard1?:embed=y&:showVizHome=no&:display_count=n"
    width="100%" 
    height="100%" 
    frameborder="0">
  </iframe>
</div>

[View Full Screen on Tableau Public](https://public.tableau.com/views/MortgageLoanApprovalAnalysis_17756756057450/Dashboard1)

## GitHub Repository

[View this project on GitHub](https://github.com/TrentEdwards2112/mortgage-loan-approval-analysis)
