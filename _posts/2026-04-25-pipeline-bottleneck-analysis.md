---
layout: post
title: Pipeline Bottleneck Analysis
image: "/img/posts/pipeline_bottleneck_thumb.png"
tags: [SQL, Tableau, Data Analytics, Mortgage]
excerpt: "Extension analysis focused on identifying operational bottlenecks and aging patterns within the mortgage underwriting pipeline."
---

<img src="/img/posts/pipeline_bottleneck_hero.png"
     style="width:100%; height:auto; display:block; margin:20px auto 30px auto; border-radius:6px;">

Analyzes workflow aging and priority-tier distribution to determine where operational bottlenecks are forming within the underwriting pipeline.

## Business Problem

Mortgage pipelines often contain high volumes of aging loans, but not all aging represents the same operational risk. Teams need visibility into where bottlenecks are forming and whether medium-priority loans are creating hidden workflow slowdowns.

## What This Analysis Answers

- Which priority tier has the highest average loan age?
- Are Medium-priority loans functioning as operational bottlenecks?
- Which stages contribute most to workflow delays?
- What operational drivers are associated with aging loans?

## Key Insight

Medium-priority loans represented the largest concentration of aging pipeline volume, suggesting that operational bottlenecks may be forming in later-stage workflow processing rather than only within urgent queues.

This extension analysis demonstrates how operational reporting can move beyond prioritization alone to identify structural workflow inefficiencies and pipeline slowdowns.

## Tools Used

- SQL (MySQL): aggregation, workflow analysis, bottleneck identification
- Tableau: dashboard visualization and operational reporting

## Approach

- Aggregated loan aging across priority tiers
- Identified average and maximum aging patterns by stage
- Analyzed workflow concentration across underwriting stages
- Visualized bottleneck trends using Tableau dashboards

---

## Dashboard Overview

<img src="/img/posts/pipeline-bottleneck-analysis-thumbnail.png"
     style="width:100%; height:auto; display:block; margin:20px auto 30px auto; border-radius:6px;">

---

## Live Dashboard

Explore the interactive Tableau dashboard used in this operational bottleneck extension analysis.

<a href="https://public.tableau.com/views/PipelineBottleneckAnalysisExtensionStudy/PipelineBottleneckAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link"
   target="_blank"
   style="display:inline-block;
          background:#00bfa5;
          color:#111;
          padding:12px 20px;
          border-radius:6px;
          text-decoration:none;
          font-weight:bold;
          margin-top:10px;">
View Full Dashboard on Tableau Public
</a>

---

## GitHub Repository

<a href="https://github.com/TrentEdwards2112"
   target="_blank"
   style="display:inline-block;
          background:#222;
          color:#fff;
          padding:12px 20px;
          border-radius:6px;
          text-decoration:none;
          border:1px solid #00bfa5;
          margin-top:10px;">
View GitHub Repository
</a>
