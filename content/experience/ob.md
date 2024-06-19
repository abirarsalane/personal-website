---
title: "Data Scientist Intern"
description: "Orange Business"
dateString: Feb 2024 - Present
draft: false
tags: ["Python", "Data Science", "Data Viz", "SQL", "ML", "Automation", "PostgreSQL", "PowerBI", "GenAI", "LLM", "RAG", "GPT", "Azure OpenAI", "Machine Learning"]
showToc: false
weight: 301
--- 

# Description

**Data Scientist in the Innovation Stream of 'Data and AI' at Orange Business**

During my time at Orange Business, I had the opportunity to work on two significant projects: "Orange Business Forecasting and Transformation: Dynamic Forecasting" and "Cybersecurity Operations with AI-Driven Threat Hunting." These projects allowed me to leverage my Data Science, Machine Learning and Generative Artificial Intelligence skills to drive innovation and improve operational efficiency. 

---

# Project 1: Orange Business Forecasting and Transformation: Dynamic Forecasting

**Objective:** Study the transformation of Orange Business clients, forecast future needs, discover patterns, and adapt strategies accordingly.

## Experience Overview

As a Data Scientist in the Innovation Stream at Orange Business, I was integral to the "Orange Business Forecasting and Transformation: Dynamic Forecasting" project. My role focused on studying the transformation of Orange Business clients, forecasting future needs, discovering patterns, and adapting strategies accordingly. This project allowed me to leverage my technical and analytical skills to drive innovation, optimize operations, and deliver strategic insights, significantly contributing to the organization's data and AI capabilities.

## Key Responsibilities and Achievements:

**Data Collection and Pre-processing:**

1. **Data Gathering:**
   - Collaborated with various departments, including financial and marketing teams, to gather comprehensive datasets.
   - Extracted data from PostgreSQL using pgAdmin, performing complex queries to retrieve and integrate data from multiple sources.

2. **Data Pre-processing:**
   - Conducted extensive data pre-processing to handle various data quality issues such as formatting inconsistencies, null values, and missing values.
   - Standardized different namings for the same products or clients across departments using a mapping dataset, ensuring data consistency and accuracy.
   - Employed SQL for data retrieval from databases, managing both batch and real-time data ingestion to ensure data completeness and relevance.

**Data Engineering and Pipeline Development:**

3. **Pipeline Development:**
   - Built and maintained data pipelines using tools like GitLab, Jupyter, and Python, ensuring efficient data processing and transformation.
   - Created robust ETL processes to handle data ingestion, transformation, and loading, ensuring data consistency and integrity.

4. **Data Manipulation:**
   - Utilized Pandas for efficient data manipulation, particularly for time series forecasting, with features like Series objects, date-time indexes, and data transformations such as offset, delay, and padding.
   - Leveraged Scipy's squareform function to convert shape-vector distance matrices into square distance matrices for better data visualization and manipulation.

**Machine Learning and Model Development:**

5. **Model Implementation:**
   - Developed models using Python libraries such as Scipy, Sklearn, and Pandas for data manipulation, similarity calculations, and time series forecasting.
   - Implemented various forecasting models using R libraries, including:
     - **Forecast Library:** Used for modeling and forecasting time series with algorithms like ETS, ThetaF, and NNetAR.
     - **Metrics Library:** Applied for evaluating model performance using error measures such as RMSE, MAE, and MSE.
     - **Tidyverse Library:** Employed for data manipulation, including dplyr for data manipulation and ggplot2 for data visualization.
     - **Purrr Library:** Utilized for functional programming in R, manipulating functions and vectors.
     - **PMCMRplus Library:** Conducted post-hoc multiple comparison tests like the Friedman test to identify significant differences between models.

6. **Model Evaluation:**
   - Conducted a detailed comparison of RMSE distributions for different models, applying statistical tests like the Friedman test to rank models.
   - Implemented revenue prediction using various models:
     - **Naive Model:** Noted for its greater variability in prediction errors.
     - **ETS and Theta Models:** Exhibited less dispersed RMSE distributions, indicating greater accuracy.
     - **NNetAR Model:** Showed some points with significantly higher RMSE, suggesting the presence of outlier errors.

**Visualization and Reporting:**

7. **Dashboard Creation:**
   - Designed and developed interactive dashboards using Power BI to visualize key metrics and trends, including:
     - **Customer Comparison Dashboard:** Provided an overall view of developments by client.
     - **Revenue Evolution Dashboards:** Showcased the temporal evolution of revenue per customer, by category, and by product.
     - **Customer Typology Dashboards:** Created typologies using Jaccard distances and visualized these with squareforms, dendrograms, and point clouds representing distances between groups.

8. **Report Generation:**
   - Produced comprehensive reports summarizing clustering characteristics and forecasting results, aiding strategic decision-making.
   - Included bar charts grouped by customer, treemaps of DGC_categories, relative gain tables, and absolute value difference tables for in-depth revenue analysis.

**Operational Efficiency and Collaboration:**

9. **Automation and Testing:**
   - Automated end-to-end testing using PyTest, significantly reducing manual testing time and improving development efficiency.
   - Built CI pipelines with GitHub Actions to streamline the building and testing of container images, ensuring consistent and reliable deployments.

10. **Collaboration Tools:**
    - Utilized Microsoft Teams and Confluence for effective team communication and documentation, facilitating seamless collaboration across departments.

**Strategic Infrastructure Optimization:**

11. **Deployment and Scalability:**
    - Deployed solutions in a Dev/UAT environment, with plans to create an automated application in the Enterprise Data Hub (EDH) for real-time data injection and live interaction.
    - The EDH platform, based on HortonWorks products, offers big data services, security, and tools for data ingestion, enrichment, and management.

## Technical Tools and Technologies Used:

- **Programming Languages:**
  - Python (for data manipulation, modeling, and automation)
  - R (for advanced statistical analysis and forecasting)
- **Libraries and Frameworks:**
  - Scipy, Sklearn, Pandas (for data processing and machine learning in Python)
  - Forecast, Metrics, Tidyverse, Purrr, PMCMRplus (for time series forecasting and data analysis in R)
- **Data Visualization:**
  - Power BI (for creating interactive dashboards)
- **Version Control and Collaboration:**
  - GitLab (for version control)
  - Microsoft Teams, Confluence (for team collaboration and documentation)
- **Databases:**
  - PostgreSQL, pgAdmin (for data extraction and management)
- **Cloud and Infrastructure:**
  - Enterprise Data Hub (EDH) (for big data services and security)

## Impact and Learning Outcomes:

- **Enhanced Forecasting Accuracy:**
  - Improved forecasting models, leading to more accurate predictions of client needs and revenue trends.
- **Operational Efficiency:**
  - Achieved significant reductions in manual testing time and cloud infrastructure costs through automation and optimization.
- **Strategic Insights:**
  - Provided actionable insights through comprehensive dashboards and reports, supporting data-driven decision-making.
- **Collaboration and Communication:**
  - Fostered effective collaboration across departments, enhancing overall project outcomes and stakeholder satisfaction.



---

# Project 2: Cybersecurity Operations with AI-Driven Threat Hunting


**Objective:** Develop an AI-driven solution for automated threat hunting and response in cybersecurity, leveraging large language models (LLMs).

## Experience Overview

As a Data Scientist in the Innovation Stream at Orange Business, I was integral to the "Cybersecurity Operations with AI-Driven Threat Hunting" project. By leveraging advanced AI techniques, RAG with private data, and cloud technologies, I successfully developed and implemented a solution that significantly enhanced threat detection and response capabilities, improved operational efficiency, and strengthened the overall cybersecurity posture of the organization.

## Key Responsibilities and Achievements:

**Solution Development and Implementation:**

1. **Automated Playbooks:**
   - Utilized GPT-4 APIs and Azure OpenAI to develop automated playbooks for threat hunting and response.
   - Implemented Retrieval-Augmented Generation (RAG) with private data (e.g., logs) to generate tailored playbooks for various attack scenarios including malware propagation, data exfiltration, and insider threats.
   - Designed playbooks that include comprehensive steps for threat detection and mitigation, integrating Indicators of Compromise (IOCs), Tactics, Techniques, and Procedures (TTPs), queries, and response actions.

2. **Threat Identification and Prioritization:**
   - Developed machine learning models to analyze and identify threats from log data and network traffic.
   - Prioritized threats based on severity and potential impact, using AI to enhance decision-making processes.
   - Incorporated insights from technological trends and market developments to refine threat models and improve detection accuracy.

3. **Proactive Threat Hunting:**
   - Leveraged AI to proactively hunt for early signs of compromise by analyzing patterns and anomalies in security data.
   - Provided security teams with real-time intelligence to preemptively address potential threats.

**Operational Efficiency and Resource Optimization:**

4. **Resource Optimization:**
   - Automated routine security tasks such as log analysis and threat classification, using machine learning to reduce manual workload.
   - Ensured rapid updates to detection and response guidance by continuously training models with new threat data.

5. **Enhanced Cybersecurity Posture:**
   - Deployed AI-driven solutions to continuously monitor and respond to security threats, enhancing the organization’s overall cybersecurity posture.
   - Improved the efficiency of security operations by automating detection and response processes, allowing teams to focus on complex threats.

**Technical Implementation:**

6. **Technology Stack:**
   - Developed the solution using Python and its libraries, including Scikit-learn for machine learning, Pandas for data manipulation, and TensorFlow for deep learning models.
   - Utilized GPT-4 APIs for natural language processing tasks and Azure OpenAI for model deployment and scalability.
   - Implemented RAG techniques to integrate private data (logs) with AI models, improving the relevance and accuracy of generated playbooks.

7. **Development and Deployment:**
   - Designed a multi-stage AI pipeline to process and analyze security data, including data preprocessing, feature extraction, model training, and deployment.
   - Deployed the solution using Kubernetes for container orchestration, ensuring scalability and high availability.
   - Packaged the solution as a Helm chart for easy deployment, distribution, and versioning.

8. **Monitoring and Optimization:**
   - Established robust monitoring and logging systems using Grafana Agent and Grafana Cloud to track the performance and effectiveness of AI models.
   - Employed continuous integration/continuous deployment (CI/CD) pipelines with GitHub Actions to automate the building and testing of container images.
   - Continuously optimized AI algorithms to improve threat detection accuracy and reduce false positives.

**Impact and Learning Outcomes:**

- **Improved Threat Detection:**
  - Achieved faster and more accurate threat detection, significantly reducing the mean time to identify and respond to security incidents.
  - Enhanced the capability to detect and mitigate sophisticated attack scenarios, providing better protection for the organization.

- **Increased Efficiency:**
  - Streamlined security operations by automating routine tasks, freeing up security analysts to focus on strategic initiatives and complex threat analysis.
  - Enabled security teams to prioritize and address high-priority threats more effectively, improving overall operational efficiency.

- **Scalable and Robust Solution:**
  - Delivered a scalable and robust AI-driven cybersecurity solution that can adapt to evolving threats and organizational requirements.
  - Ensured the solution’s resilience and reliability through continuous monitoring, logging, and optimization.



## Summary

Through these projects, I developed a comprehensive skill set in data science, machine learning, cloud computing, and cybersecurity. My ability to apply these skills to real-world challenges demonstrates my technical mastery and commitment to delivering high-impact solutions.

![](/experience/OB/ob.jpg#center)