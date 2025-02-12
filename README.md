title: Sydni Liotta
logo: images/Sydni%20liotta%20w%20jacket%20Thumbnail.png
description: Registered dietitian and data analyst with 5+ years of experience in analyzing complex data to drive insights and improve patient outcomes. 
             Skilled in SQL, Power BI, and Tableau, with expertise in healthcare data visualization, trend analysis, and process optimization. 
theme: jekyll-theme-minimal

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


<style>
    .button {
        display: inline-block;
        padding: 12px 24px;
        font-size: 18px;
        font-weight: bold;
        color: white;
        background-color: #007bff;
        text-decoration: none;
        border-radius: 5px;
        transition: background-color 0.3s, transform 0.3s, box-shadow 0.3s;
        box-shadow: 0px 4px 6px rgba(0, 123, 255, 0.2);
        margin: 20px 0;
    }

    .button:hover {
        background-color: #0056b3;
        transform: translateY(-3px);
        box-shadow: 0px 6px 10px rgba(0, 123, 255, 0.3);
    }

    .button:active {
        background-color: #003366;
        transform: translateY(0);
        box-shadow: 0px 4px 6px rgba(0, 123, 255, 0.2);
    }
</style>

<a href="https://sydniliotta.github.io/portfolio/resume/" class="button">View My Projects</a>

<a href="https://sydniliotta.github.io/portfolio/projects/" class="button">View My Projects</a>



## Projects
### Analyzing Cause of Death Data - Worldwide
#### Question: What are the primary causes of death that contribute the most to overall mortality, and how can this insight guide public health priorities?"
![Cleaning Data](/images/cause%20of%20death%20data%20cleaning.png)
[Tableua Dashboard](https://public.tableau.com/views/TopCausesofDeath-Pareto/TopCausesofDeath-Pareto?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

Process:
1. Data Preparation:
  - Imported the dataset and filtered it to only include 2015–2019 data for the U.S.
  - Pivoted the death columns for easier analysis.
  - Cleaned and standardized the Causes of Death field using: REPLACE(REPLACE([Reason for Death],'Deaths -',''),'- Sex: Both - Age: All Ages (Number)','')
  - ![Cleaning Data](/images/cause%20of%20death%20data%20cleaning.png)

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
