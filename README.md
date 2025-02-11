# Data Analytics

## Education	        		
Bachelor of Sciences in Dietetics, Minor in Business Administration
  University of Florida (_May 2020_)

### Key Skills
- **Data Analysis and Visualization:** SQL, Power BI, Excel, Tableau, Power Platform
- **Process Improvement:** Root-Cause Analysis, Workflow Optimization, Automation
- **Healthcare Analytics:** EHR Systems, HIPAA Compliance, Patient Outcome Analysis, SharePoint
- **Project Management:** Cross-Functional Collaboration, Large-Scale Project Implementation

### Certifications and Training
- Lean Six Sigma Yellow Belt Certification (_October 2024_)
- SQL Training, VHA Learning (_January 2024_)
- Power Automate Training, LinkedIn Learning (_October 2023_)
- Introduction to Healthcare Data Analytics Certification, VHA Learning (_August 2023_)
- Power BI Foundations Course, VHA Learning (_March 2023_)
- Registered Dietitian Nutritionist (_August 2021_)

## Work Experience
**Health Informatics Program Analyst  @ Veteran’s Health Administration (_August 2023- Pres_)**
- Designed and maintained SQL queries to improve electronic health record (EHR) functionality,  standardize processes, and enhance clinical decision-making.
- Streamlined operations by leveraging Power Automate to standardize processes and automate data workflows, resulting in improved efficiency and reduced manual effort.

**Informatics Dietitian  @ Veteran’s Health Administration (_July 2022 – August 2023_)**
- Analyzed KPI data for 100 VHA  nutrition departments, identifying trends using Power BI and Excel.
- Integrated two datasets with differing outputs into a centralized pipeline using PowerQuery, then delivered monthly Power BI presentations to leadership, providing valuable insights to support decision-making.

**Clinical Dietitian and Internship   @ Veteran’s Health Administration (_May 2021 – June 2022_)**
- Conducted statistical analysis using SPSS to compare the efficacy of virtual vs. in-person nutrition appointments, presenting findings to improve patient care strategies.
- Developed dynamic Excel dashboards to provide detailed macro- and micronutrient analyses for inpatient diets, used by leadership to audit and enhance processes.

## Projects
### Analyzing Cause of Death Data - Worldwide
#### Question: What are the primary causes of death that contribute the most to overall mortality, and how can this insight guide public health priorities?"
![Bike Study](/assets/img/bike_study.jpeg)
[Tableua Dashboard](https://public.tableau.com/views/TopCausesofDeath-Pareto/TopCausesofDeath-Pareto?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Process:
1. Data Preparation:
- Imported the dataset and filtered it to only include 2015–2019 data for the U.S.
- Pivoted the death columns for easier analysis.
- Cleaned and standardized the Causes of Death field using: REPLACE(REPLACE([Reason for Death],'Deaths -',''),'- Sex: Both - Age: All Ages (Number)','')

2. Building the Pareto Chart:
- Duplicated the Deaths measure to create a dual-axis visualization.
- Converted the second axis into a running total to calculate the cumulative percentage of deaths.
- Changed the cumulative axis to a line graph and formatted it as a percentage of total deaths.
- Applied a secondary calculation (percent of total) to visualize cumulative impact.

  3.Applying the 80/20 Rule:
- Created a parameter (80%) to dynamically adjust the threshold.
- Developed a calculated field to filter only the causes contributing to ≤ 80% of total deaths
- Filtered the view to only display the top 80% of causes, making the visualization more focused and impactful.

**Insights:** This visualization highlights the few leading causes of death that account for the majority of mortality, helping public health officials prioritize interventions. The dynamic parameter allows for adjusting the percentage threshold, demonstrating how different cutoffs impact the analysis.
By applying the Pareto principle, we can target resources where they will have the greatest impact on reducing mortality. If we aim to reduce deaths most effectively, this is where we should start.

### SQL Encounter Data 
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)

Developed objective strategy for discovering optimal EEG bands based on signal power spectra using **Python**. This data-driven approach led to better characterization of the underlying power spectrum by identifying bands that outperformed the more commonly used band boundaries by a factor of two. The proposed method provides a fully automated and flexible approach to capturing key signal components and possibly discovering new indices of brain activity.

![EEG Band Discovery](/assets/img/eeg_band_discovery.jpeg)

### Decoding Physical and Cognitive Impacts of Particulate Matter Concentrations at Ultra-Fine Scales
[Publication](https://www.mdpi.com/1424-8220/22/11/4240)

Used **Matlab** to train over 100 machine learning models which estimated particulate matter concentrations based on a suite of over 300 biometric variables. We found biometric variables can be used to accurately estimate particulate matter concentrations at ultra-fine spatial scales with high fidelity (r2 = 0.91) and that smaller particles are better estimated than larger ones. Inferring environmental conditions solely from biometric measurements allows us to disentangle key interactions between the environment and the body.

![Bike Study](/assets/img/bike_study.jpeg)
