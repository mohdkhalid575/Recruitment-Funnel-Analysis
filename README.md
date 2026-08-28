# Recruitment-Funnel-Analysis
Interactive Power BI dashboard analyzing the end-to-end recruitment funnel — from sourcing to hiring. Tracks 100 candidates across various roles, visualizing conversion rates at each stage, time-to-hire, offer acceptance rate, and source effectiveness (Direct vs. Referral) to help identify bottlenecks and improve overall hiring efficiency and speed

# Recruitment Funnel Analysis Dashboard

Interactive Power BI dashboard analyzing the end-to-end recruitment funnel — from sourcing to hiring. Tracks 100 candidates across various roles, visualizing conversion rates at each stage, time-to-hire, offer acceptance rate, and source effectiveness (Direct vs. Referral) to help identify bottlenecks and improve overall hiring efficiency and speed.

# Objective

Recruitment teams often struggle to identify where candidates drop off in the hiring pipeline and which sourcing channels deliver the best results. This dashboard was built to:

Track the complete recruitment funnel from application to hire
Measure recruitment efficiency through key HR metrics
Compare sourcing channel performance (Direct vs. Referral)
Analyze hiring trends by role, team, and time period
Identify bottlenecks causing delays in time-to-hire
 
# Key Metrics (KPIs)
Metric	Value	Description
Total Candidates	100	Total candidates who entered the pipeline
Offers Made	38	Number of offers extended
Total Hires	32	Candidates who successfully joined
Average Time to Hire	148.63 days	Average days taken to close a position
Selection %	38.0%	Percentage of candidates selected
Offer Acceptance Rate	84.2%	Percentage of offers accepted

# Dashboard Components
1. Count of Joined (Trend Line)

Tracks daily candidate joining trends over time, highlighting peaks and dips in onboarding activity.

2. Total Hires vs. Offers Made (by Role)

Horizontal bar chart comparing offers made against actual hires across roles:

Senior Software Engineer
Software Manager
Software Architect
3. Hiring Mix (Donut Chart — by Source)
Direct: 66%
Referral: 34%
4. Job Roles (Pie Chart)
Software Architect: 35%
Software Manager: 34%
Senior Software: 31%
5. Recruitment Funnel (Funnel Chart)

Visualizes candidate drop-off at each stage:

Stage	Count	% of Total
Total Candidates	100	100%
Hiring Manager Review	80	80%
R1 Selected	43	43%
Total Offers Made	38	38%
Total Offers Accepted	32	32%
6. Candidate Detail Table

Record-level data including Candidate Name, Role, Source, Team, Time to Hire, and Quarter — fully filterable.

# Key Insights
Only 32% of candidates who entered the funnel were ultimately hired, showing a significant filter at the Hiring Manager and R1 review stages.
Direct sourcing (66%) significantly outperforms referrals (34%) as a hiring channel.
84.2% offer acceptance rate indicates strong offer competitiveness once candidates reach the final stage.
Average Time to Hire (~149 days) is high, suggesting bottlenecks between review and selection stages that may need process improvement.
 
# Tools & Technologies
Power BI — Data modeling, DAX measures, interactive visuals
Visuals Used: Funnel Chart, Donut Chart, Pie Chart, Line Chart, Bar Chart, KPI Cards, Table

Dataset

The dataset includes candidate-level recruitment records with the following fields:

Candidate Name
Role
Source (Direct / Referral)
Team
Time to Hire (days)
Quarter
Joining Date

# How to Use
Clone this repository
Open the .pbix file in Power BI Desktop
Refresh the data source if connected to a live dataset
Explore the dashboard using slicers/filters (Role, Team, Source, Quarter)

# Contact
For questions or feedback, feel free to reach out or open an issue in this repository.
