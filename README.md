# Academic Darwanism - Social Media Analytics

## Overview

This repository contains the final project for the Social Media Analytics course (INSY-669-076) by Arham Anwar, Arnav Gupta, Ethan Pirso, Jatin Suri, and Hongyi Zhan. The project, titled "Organic Feedback Mining: What McGill Students Say Behind the Filter," explores the unfiltered experiences of students using social media data from platforms like Reddit. The main objective is to identify core issues affecting student wellness and academic performance through advanced data analytics and network modeling.

## Problem Statement

We address two main issues:
1. **Impeded dissemination of resources**: Inadequate communication strategies within student social networks hinder the dissemination of support resources, affecting academic performance and retention.
2. **Social mobility restrictions**: Information diversity bottlenecks due to students staying in cliques limit the university's potential in terms of projects and extracurricular activities.

## Data Strategy

### Proxy Data Sourcing:
- **Source**: Dataset containing the evolution of a friendship network of 6,000 students over 42 months based on social interactions from VK (Russia's largest social site).
- **Data Description**: Includes academic performance data at several time points and detailed information about friendship networks.

### Data Transformation:
- **ETL Process**: Extract, transform, and load the data for analysis.
- **Network Construction**: Build friendship networks where nodes represent students and edges represent mutual "likes."

## Solution Approach

### 1. Network Construction
- Construct friendship networks for high school and university students.
- Nodes represent students, and edges represent exchanged "likes."
- Friendship links are approximated from "likes" exchanged within a timeframe.

### 2. Homophily Testing
- **Homophily Index & Pearson Coefficient**: Quantify the extent to which students with similar GPAs are more likely to be friends.
- **Hypothesis Testing**: Assess structure sensitivity by permuting node attributes in the graph.
- **Relational Autocorrelation**: Test homophily gain by measuring the increase in autocorrelation over time.

### 3. Regression Analysis
- **Model**: Random Forest Regression to predict GPA based on network attributes.
- **Explainability**: Use SHAP analysis to extract valuable insights from the model.

### 4. Community Detection
- **Greedy Modularity Algorithm**: Identify and analyze community structure within student networks.
- **HITS Algorithm**: Identify core nodes (hubs and authorities) within the communities for targeted interventions.

## Key Findings

- **Homophily Dominance**: Students prefer to reorganize their social networks based on performance levels.
- **Prediction of GPA**: High network centrality correlates with higher GPA.
- **Identification of Communities & Influencers**: Identified core nodes for strategic communication and resource dissemination.

## Business Value and Expected Impact

- Tailored communication strategies to ensure inclusive engagement.
- Targeted support initiatives to improve academic outcomes.
- Amplified outreach efforts through influential nodes, promoting community involvement.

## Technologies Used

- Network analysis algorithms (Greedy Modularity, HITS)
- Random Forest regression
- SHAP analysis for model interpretability
- Data preprocessing and transformation

## Instructions to Replicate the Model

### Prerequisites

- Python 3.x
- Libraries: pandas, numpy, networkx, scikit-learn, shap, matplotlib

### Final Client Presentation
<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide1.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide2.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide3.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide4.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide5.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide6.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide7.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide8.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide9.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide10.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide11.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide12.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide13.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide14.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide15.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide16.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide17.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide18.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide19.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide20.jpeg" >
</p>

<p align="center">
  <img src="https://github.com/arham-anwar/SocialMediaAnalytics_GroupProject/blob/final/02_Powerpoint/powerpoint/Slide21.jpeg" >
</p>
