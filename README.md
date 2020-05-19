# watson-assistant-metrics-notebook
This Jupyter notebook was developed for analyzing the data exhaust for Watson Assistant (and Voice Interaction) solutions. It will retrieve and format logs, extract key metrics, and export the data to CSV for use in Watson Studio's Cognos Dashboard.

KPIs include coverage, containment, escalation, and other key metrics vital to reporting on the performance of a Watson Assistant solution. 

**Note** that this is not a supported product.

## Prerequisites
1. Watson Assistant credentials
2. Watson Studio instance and project

## Instructions
1. Download the notebook `Watson Assistant Metrics Notebook.ipynb` locally.
2. Log into Watson Studio (https://dataplatform.cloud.ibm.com/) and open up (or create) the customer's project.
3. Click `Add to project +`
4. Click `Notebook`
5. Click `From file`
6. Enter a name for the notebook, e.g. `Watson Assistant Metrics Notebook (Client_Name)`
7. Drag and drop downloaded file. 
8. Select runtime (default Python 3.6 XS is OK)
9. Click `create`
10. The first cell (in the Housekeeping section) requires project id and token in order to save the CSV files to data assets. Follow these instructions: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/token.html
11. Follow the remaining instructions of the notebook. Keep an eye out for `Action required` notes in Section 2. Section 3 allows you to perform blind testing and is optional. 
12. Upon completion of notebook, CSV files will be saved to your project's data assets. It is highly recommended to build a Cognos dashboard in Watson Studio in order to share metrics and insights with your account/client stakeholders. To build visualizations, a tutorial can be found: https://developer.ibm.com/tutorials/create-interactive-dashboards-on-watson-studio/

Happy Analyzing!
