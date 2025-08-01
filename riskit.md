---
layout: default
---

# RiskT - An Automated Lightweight GRC third-party tool
In today’s compliance-driven environment, evaluating the security posture of third-party vendors is no longer optional—it’s essential. Traditional methods like spreadsheets and email threads often lead to delays, inconsistencies, and limited visibility. This tool was developed to streamline the process, improve accuracy, and provide a scalable, repeatable approach to third-party risk assessments

## Project Diagram and Workflow
<img src="/myfolder/riskit.png" alt="">
<img src="/myfolder/workflow" alt="">



## Project Components

**Stored Vendor Responses:**  This section contains vendor responses collected through structured questionnaires. Each response is mapped to relevant controls and requirements from recognized frameworks such as ISO 27001, NIST, and SOC 2. The responses are stored in a centralized database and used to evaluate risk based on both qualitative (likelihood and impact) and quantitative scoring.

<img src="/myfolder/storedvendorresponses.png" alt="">

**Risk Level:** This section represents the calculated risk level for each vendor, derived from their responses. Risk is determined using a logic-based approach that evaluates both the likelihood of a risk occurring and its potential impact. These factors are scored based on predefined criteria and mapped onto a risk matrix, producing a final rating of Low, Medium, or High.

<img src="/myfolder/risklevel.png" alt="">

**Risk Visualization:** This section displays a visual representation of vendor risk levels to support quick assessment and decision-making. It includes bar charts. A prominent feature is the Risk Appetite Gauge, which illustrates where each vendor’s overall risk rating falls in relation to the organization’s defined thresholds (Low, Medium, High). This helps stakeholders immediately identify vendors that exceed acceptable risk limits and require closer review or mitigation.

<img src="/myfolder/riskdashboard.png" alt="">


**Export Reports Summary:** This section allows users to generate and download comprehensive vendor risk reports in commonly used formats such as PDF.

<img src="/myfolder/exportreport.png" alt="">













