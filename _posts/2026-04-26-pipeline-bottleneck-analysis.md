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
