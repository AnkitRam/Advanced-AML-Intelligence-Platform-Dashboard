Advanced AML Intelligence Platform Dashboard

Strategic Overview
In high-volume banking environments, the ability to distinguish between routine activity and financial crime is critical. Advanced AML Intelligence Platform Dashboard is an end-to-end analytics engine designed to optimize Anti-Money Laundering (AML) workflows.

Developed with a "Command-Center" philosophy, this platform moves beyond basic reporting to provide senior leadership and Money Laundering Reporting Officers (MLROs) with real-time visibility into alert lifecycles, regulatory compliance, and investigator performance.

<img width="1422" height="801" alt="image" src="https://github.com/user-attachments/assets/85f03364-e70c-4adf-9487-46ca0e63a050" />
<img width="1422" height="800" alt="image" src="https://github.com/user-attachments/assets/7a388927-fb77-43b7-bac4-9d1c840efb07" />
<img width="1423" height="797" alt="image" src="https://github.com/user-attachments/assets/ff0f29e5-249e-4cb2-9f5b-49445dfbb3f2" />
<img width="1425" height="798" alt="image" src="https://github.com/user-attachments/assets/d0d7c2e4-21d2-48a1-9294-11a0dfc319e8" />
<img width="1423" height="798" alt="image" src="https://github.com/user-attachments/assets/aba03a42-02b8-46b6-858b-77e50c708c59" />

**Project Showcase**
**1. Executive & Operations Intelligence**
Executive Summary: High-level tracking of the False Positive Ratio (FPR) and STR Conversion rates to measure detection accuracy.

Alert Operations: A tactical view of alert sources and risk distribution.

Risk Analysis: A specialized scatter plot analyzing the correlation between Risk Scores and Days-to-Close to identify investigative friction.

Global Executive Overview and Operational Trends.
<img width="1422" height="801" alt="image" src="https://github.com/user-attachments/assets/85f03364-e70c-4adf-9487-46ca0e63a050" />


**2. Team Productivity & Resource Management**
Banking compliance relies on human expertise. This page provides a granular view of team efficiency:

Quota Tracking: Real-time monitoring of Cases Closed vs. Monthly Targets.

Performance Matrix: Comparative analysis of analysts across multiple performance dimensions.

Attainment Trends: Quarterly growth metrics categorized by seniority levels (Senior, L3, L2, L1).

Investigator Productivity and Target Attainment Matrix.
<img width="1422" height="800" alt="image" src="https://github.com/user-attachments/assets/7a388927-fb77-43b7-bac4-9d1c840efb07" />
Caption: Investigator Productivity and Target Attainment Matrix.

**3. Geographic Intelligence & Mule Detection**
Leveraging spatial data to identify criminal clusters:

Hotspot Mapping: Interactive bubble maps identifying cities with high concentrations of "Mule Accounts."

Income Band Analysis: Correlating suspicious activity with customer income levels to detect anomalies.

Regional Distribution: A 5-region breakdown (North, South, East, West, Central) of alert typologies.

Geographic Risk Hotspots and Customer Demographics.
<img width="1423" height="797" alt="image" src="https://github.com/user-attachments/assets/ff0f29e5-249e-4cb2-9f5b-49445dfbb3f2" />
<img width="1423" height="798" alt="image" src="https://github.com/user-attachments/assets/aba03a42-02b8-46b6-858b-77e50c708c59" />

**4 and 5 Regulatory Safety (SLA & Aging)**
The "Safety Net" of the platform, ensuring zero regulatory breaches:

SLA Compliance Gauge: Visualizing the bank's 90% compliance target.

Aging Buckets: Categorizing alerts by time-spent, with automated flagging for "30+ Days CRITICAL" cases.

Breach Analysis: Identifying which typologies (e.g., PEP-related) are most prone to regulatory delays.

SLA Compliance and Critical Alert Aging.
<img width="1425" height="798" alt="image" src="https://github.com/user-attachments/assets/d0d7c2e4-21d2-48a1-9294-11a0dfc319e8" />


**Technical Stack**
Data Modeling: Implemented a Star Schema to handle 12,000+ transaction records efficiently.

Advanced DAX: Engineered complex measures for dynamic status labeling, weighted averages, and sorting logic for non-alphabetical fields (e.g., Income Ranges and Months).

UI/UX Design: Built a bespoke "Dark Mode" interface featuring:

Button Slicers: Custom navigation pills for a web-app feel.

Sync Slicers: Ensuring consistent filtering across all 5 intelligence layers.

Conditional Formatting: Red/Green status badges for immediate risk recognition.

Power Query (M): Extensive ETL processes to clean, trim, and transform raw banking data into structured dimensions.

**Key Business Insights**
Efficiency: Identified that Dormant Account Reactivation alerts have the highest False Positive Ratio (86.3%), suggesting a need for rule-tuning.

Compliance: Visualized a clear path to improving SLA Compliance, currently sitting at 68.6% against a 90% target.

Risk: Identified Nagpur and Mumbai as primary geographic hotspots for mule account activity.

**How to Use This Dashboard**
Requirement: You will need Power BI Desktop (latest version) installed.

Interaction: Use the Global Filter Bar at the top to toggle between years (2022–2024) and regions.

Cross-Filtering: Click on any bar or pie segment to filter the entire page by that specific typology or region.
