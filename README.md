# Advanced Topics in Database Systems – Term Project (ECE NTUA, 9th Semester)

This repository contains the term project for the **Advanced Topics in Database Systems** course, completed as part of the **9th semester (2024-2025)** curriculum at the **School of Electrical and Computer Engineering (ECE), National Technical University of Athens (NTUA)**. 

## Collaborators
- **Charidimos Papadakis** ([el20022@mail.ntua.gr](mailto:el20022@mail.ntua.gr))  
- **Konstantinos Katsikopoulos** ([el20103@mail.ntua.gr](mailto:el20103@mail.ntua.gr))  

## Project Description

The project focuses on the analysis of large datasets using distributed computing frameworks, namely **Apache Spark** and **Apache Hadoop**. The aim is to develop data processing pipelines, perform data analysis tasks, and evaluate the performance of different configurations and techniques in a cloud-based environment.

The datasets span topics like crime statistics, population demographics, income distribution, and police station locations in Los Angeles, enabling practical exploration of database and big data concepts.

This project is complemented by a **thorough report**, which provides in-depth insights into the methodology, results, and observations made throughout the process.

---

## Objectives

1. **Familiarization with Distributed Systems**  
   Students gain hands-on experience in managing and utilizing distributed systems such as Apache Spark and Hadoop.
   
2. **Application of Data Science Techniques**  
   Leveraging Spark's APIs to process, analyze, and derive insights from large datasets.

3. **Evaluation of Performance**  
   Understanding the trade-offs of different Spark join strategies and configurations, while utilizing cloud-based resources effectively.

---

## Infrastructure

The project was executed on **AWS cloud resources**, specifically configured to allow experimentation with Spark and Hadoop clusters under varying conditions. Configurations included different combinations of executors, cores, and memory allocations to assess performance across tasks.

---

## Queries Addressed

The project implements and answers five advanced analytical queries:

1. **Victim Age Group Analysis:**  
   Sorting age groups of crime victims involved in aggravated assaults based on incident counts.

2. **Top Performing Police Divisions:**  
   Identifying the three police divisions with the highest case resolution rates for each year.

3. **Income and Crime Correlation:**  
   Calculating the average annual income per person and the crime ratio per capita for Los Angeles communities.

4. **Victim Demographics by Income Levels:**  
   Analyzing racial and ethnic profiles of victims in areas with the highest and lowest income levels.

5. **Nearest Police Station Analysis:**  
   Determining the number of crimes closest to each police station and the average distance of these crimes.

---

## Repository Structure

- `notebooks/`: Contains individual Jupyter notebooks for each query, structured to include:
  - Query description.
  - Data preprocessing steps.
  - Implementation of analysis using Spark (DataFrame and/or SQL APIs).
  - Performance results and visualizations.
- `results/`: Outputs of the analyses, saved in CSV format.
- `report/`: The comprehensive report detailing the methodology, experiments, and observations for the project.

---
