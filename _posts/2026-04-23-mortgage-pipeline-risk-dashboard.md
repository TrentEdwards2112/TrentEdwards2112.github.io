---
layout: post
title: Mortgage Loan Pipeline Risk & Prioritization Dashboard
image: "/posts/pipeline_dashboard.png"
tags: [Tableau, SQL, Data Analytics, Mortgage]
---

This project provides an operational view of a mortgage loan pipeline, helping underwriting teams identify risk, prioritize work, and manage loan flow across stages.

## Business Problem

Underwriting teams need to quickly identify which loans require immediate attention while still managing overall pipeline volume efficiently.

## What This Dashboard Answers

- Where is loan volume concentrated across the pipeline?
- Which factors are driving urgency?
- Which loans should be prioritized first?
- Where are bottlenecks forming by stage and priority tier?

## Key Insight

Aging Pipeline drives the largest workload, while LE Past Due loans represent the highest immediate operational risk.

## Tools Used

- SQL (MySQL)
- Tableau Public

## Live Dashboard

<iframe seamless frameborder="0" src="<div class='tableauPlaceholder' id='viz1777054726550' style='position: relative'><noscript><a href='#'><img alt='Dashboard 1 ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MortgageLoanPipelineRiskPrioritizationDashboard&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MortgageLoanPipelineRiskPrioritizationDashboard&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Mo&#47;MortgageLoanPipelineRiskPrioritizationDashboard&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1777054726550');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1200px';vizElement.style.height='927px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1200px';vizElement.style.height='927px';} else { vizElement.style.width='100%';vizElement.style.height='1277px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>" width="100%" height="800"></iframe>

[View Full Screen on Tableau Public](https://public.tableau.com/views/MortgageLoanPipelineRiskPrioritizationDashboard/Dashboard1)

## GitHub Repository

[View this project on GitHub](https://github.com/TrentEdwards2112/mortgage-loan-prioritization-dashboard)
