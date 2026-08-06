# FreelanceGIG Ecosystem Analysis

## Leveraging Tableau to evaluate operational performance, talent pricing dynamics, and market scalability across a global freelance platform.

Disclaimer ⚠️: All datasets, reports, and visualisations do not contain real proprietary, confidential, or sensitive information from any company, institution, or individual. All data represents dummy/mock transactional logs designed to demonstrate my capabilities in using Tableau Desktop to build advanced business intelligence analytics for the freelance and gig economy sector.

## INTRODUCTION 

This project leverages data analytics and transactional history to evaluate operational health and profitability drivers for FreelanceGIG. By analyzing a global dataset encompassing 273,000 completed jobs, I built an interactive analytical suite to map out how a $450,000 marketing investment successfully converted into $10,000,000 in total platform revenue while maintaining an overall 4.00/5.00 client satisfaction rating.

Through Tableau Desktop, this project transforms complex transactional data into actionable strategic insights, identifying the exact talent tiers, service categories, and marketplace platforms that drive user retention and revenue scaling.

## PROBLEM STATEMENT

The global freelance marketplace is highly dynamic and sensitive to fluctuating talent rates, varying service quality, and platform-specific conversion success. Traditional high-level reporting often fails to capture the subtle trade-offs between volume, price, and client satisfaction.

The core challenge lies in pinpointing:

- Which service categories drive raw revenue versus those that deliver peak quality.
- How talent experience levels directly impact market pricing and client demand.
- Which hosting platforms yield the highest completion reliability and user retention.

## AIM OF THE PROJECT

The primary objectives of this analytical audit are to:

- Analyze transactional performance logs to uncover underlying revenue patterns and client satisfaction trends.
- Develop an interactive executive dashboard in Tableau with dynamic filtering capabilities for Region and Experience Level.
- Evaluate the relationship between hourly rates, freelancer experience tiers, and market demand.
- Assess platform reliability across key competitors including Upwork, Fiverr, Toptal, Freelancer, and PeoplePerHour.
- Provide data-driven strategic recommendations to optimize platform marketing spend and client retention.

## SKILLS & CONCEPTS DEMONSTRATED

- Business Intelligence: Executive-level KPI tracking, ROI evaluation, and market performance benchmarking.
- Data Architecture & Preparation: Primary key joins, field standardization, and missing value filtering.
- Advanced Tableau Development: Custom dual-axis donut charts, lollipop visualisations, targeted Top-5 bar charts, and container-based dashboard formatting.
- Strategic Communication: Translating complex transactional metrics into clear executive briefings.

.................

### Project Objectives & Problem Statement
The goal of this project was to identify the drivers of profitability and quality within the global freelance market. I set out to answer three critical business questions:

1. Which service categories generate the highest revenue vs. those that provide the highest client satisfaction?
2. How does freelancer experience level impact market value and hourly rates?
3. Which platforms offer the highest success rates and job volumes for scaling operations?

### Data Methodology
To ensure a robust analysis, I performed the following technical steps:

- Data Integration: I performed a primary join between Table 1 (Freelancer Details) and Table 2 (Job & Earnings Data) using Freelancer ID as the common key.
- Data Cleaning: I addressed null values in the rating columns and standardized the naming conventions for platforms and job categories to ensure consistency across all visualisations.
- Calculation Development: I created calculated fields for Market ROI and Average Success Rates to move beyond raw data into strategic metrics.
- Visualisation Strategy: I utilised a Dual-Axis approach to create custom Lollipop and providing a more sophisticated user experience than standard bar graphs.

## Interactive Dashboard Preview
![dashboard](visauls/dashbooard.png)
### Figure 1: Global Executive Performance Summary

Note: I have designed this dashboard to allow for real-time filtering by Experience Level and Client Region, providing an interactive experience for stakeholders.

#### The Revenue Drivers
According to my analysis of the Top 5 Earning By Category chart, Graphic Design is the dominant financial driver, generating ($1,34) in revenue. This is closely followed by App Development ($1.27M) and Customer Support ($1.24M).

#### The Quality Benchmark
While Graphic Design leads in volume, I utilised a Lollipop Chart to track service quality. I found that Web Development represents the platform's quality benchmark, holding the highest average client rating of 4.08.

#### Strategic Insight
I identified that the majority of service categories, including Digital Marketing and Content Writing, maintain a consistent 4.01 rating. This indicates that my analysis found a high level of vetting and service standardisation across diverse skill sets globally.

## Talent & Platform Dynamics
### Experience-Based Earning Power
Utilising a pie Chart to analyse compensation tiers, I uncovered a significant market trend regarding value distribution. My analysis reveals that compensation does not strictly follow traditional seniority:

- The Intermediate Advantage: I identified that Intermediate freelancers command the highest market value with an average hourly rate of $53.46.
- Expert vs. Beginner: Surprisingly, Experts follow at $51.65/hr, while Beginners maintain a strong competitive average of $49.97/hr.
- Strategic Takeaway: This suggests that the market currently places a premium on "agile" mid-career talent.

### Platform Success & Volume
To understand operational reliability, I compared success rates against total job volume:

- Reliability Leader: I found that Freelancer is the most reliable platform in the ecosystem, achieving a 75.88% success rate.
- Market Scale: I visualised the sheer scale of the landscape. Upwork (57K jobs) and Fiverr (56K jobs) lead in transaction volume, proving they are the primary engines for high-frequency tasks.
- Customer Loyalty: My analysis of the Rehire Rate bar chart identified Customer Support as the hero for retention, with a 45.93% rehire rate.

## Strategic Recommendations & Technical Appendix
### Strategic Recommendations
Based on the data-driven insights from my 2026 analysis, I propose the following strategic roadmap for the platform:

1. Capitalise on Intermediate Talent: Since my analysis identified Intermediate freelancers as the highest hourly earners ($53.46/hr), marketing efforts should be weighted toward this tier to maximise platform service fees.
2. Double-Down on Graphic Design & Web Excellence: I recommend leveraging Graphic Design as the primary revenue engine ($1.34M) while using Web Development (4.08 rating) as the core case study for platform quality in promotional materials.
3. Incentivise Retention in Customer Support: Because I identified Customer Support as the leader in recurring business (45.93% rehire rate), the platform should introduce loyalty structures for this category to secure long-term, stable revenue streams.

### Technical Skills & Tools Used
- Data Visualization: Tableau Desktop (Dual-Axis Charts, Lollipop Charts, Bar Charts).
- Data Modeling: Primary Key Joins, Calculated Fields, Data Blending.
- Analysis: ROI Calculation, Retention Analysis, Trend Identification.
- Documentation: Technical Report Writing, GitHub Version Control.

Dashboard Link : https://public.tableau.com/views/FreelanceGIGDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link




