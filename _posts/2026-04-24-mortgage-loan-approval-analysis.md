---
layout: post
title: Mortgage Loan Approval Analysis
image: "/img/posts/Mortgage_approval_full_dashboard.png"
tags: [SQL, Tableau, Data Analytics, Mortgage]
---

<img src="/img/posts/Mortgage_approval__full_dashboard.png" 
     style="width:100%; height:auto; display:block; margin:20px auto 30px auto; border-radius:6px;">

This project analyzes mortgage loan application data to identify trends in approval outcomes and understand the factors influencing loan decisions.

## Business Problem

Lenders must evaluate large volumes of loan applications while balancing risk and approval rates. Without clear insight into approval patterns and contributing factors, it becomes difficult to identify trends and make data-informed decisions.

## What This Analysis Answers

- How do approval rates vary by income level?
- What relationship exists between loan size and approval likelihood?
- How do approval rates differ across regions and states?
- What borrower characteristics influence approval outcomes?

## Key Insight

Higher income levels and smaller loan sizes are associated with increased approval rates, while larger loan amounts show a declining approval trend—highlighting risk sensitivity in lending decisions.

## Tools Used

- SQL (MySQL): data cleaning, transformation, and aggregation  
- Tableau Public: dashboard development and data visualization  

## Approach

- Cleaned and standardized raw loan data using SQL  
- Created derived fields including income bands and loan size categories  
- Calculated approval rates across multiple dimensions (income, loan size, region)  
- Designed Tableau visualizations to highlight trends and relationships in approval outcomes  

## Dashboard Overview

The dashboard provides a clear view of approval trends across borrower segments, enabling comparison of approval rates by income, loan size, and geographic distribution.

![Dashboard](/img/posts/mortgage_approval_dashboard.png)

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
