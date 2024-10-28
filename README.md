# Categorising-Employees-on-Mental-Health-in-Technology-related-Jobs

This project analyzes mental health trends among employees in technology-related jobs to assist the HR department in creating targeted mental health support programs. Using clustering techniques, the analysis categorizes employees into distinct groups based on survey responses, providing insights for HR to design customized interventions.

## Project Structure

1. **Data Source and Preprocessing**
   - Loads and cleans survey data on mental health in the tech industry.
   - Handles missing values, standardizes text entries, and prepares data for analysis.

2. **Clustering and Dimensionality Reduction**
   - Applies K-Prototypes clustering to group employees based on mental health needs and attitudes.
   - Uses the elbow method to determine the optimal number of clusters.
   - Reduces data dimensionality using Cramér's V for easier visualization and interpretation.

3. **Analysis of Clusters**
   - Describes characteristics of each identified cluster, highlighting unique demographics and mental health attitudes.
   - Provides actionable insights for each cluster to inform HR’s approach to mental health support.

4. **Visualizations**
   - Includes bar plots, count plots, and heatmaps to depict insights, such as resource awareness, comfort levels in discussing mental health, and diagnosis/treatment history.

5. **Recommendations for HR**
   - Suggests targeted interventions for each employee cluster, including enhanced communication, privacy assurance, supervisor training, and wellness check-ins.

## Running the Code
1. **Load Data:** Ensure the dataset is available in the specified directory or adjust the file path in the code.
2. **Preprocess Data:** Run the data cleaning and feature engineering steps to prepare data for clustering.
3. **Cluster and Analyze:** Execute clustering, and generate insights for each cluster.
4. **Generate Visuals:** The code includes visualizations to aid in understanding cluster characteristics and to provide HR with a summary of findings.

## Repository Structure
1. **Main.ipynb:** Jupyter Notebook containing the full analysis, from preprocessing to clustering and visualization.
2. **requirements.txt:** List of all Python libraries needed to run the project.

## Requirements

To run this project, install the required dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
