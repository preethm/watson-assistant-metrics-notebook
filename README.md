# watson-assistant-metrics-notebook
This Jupyter notebook was developed for analyzing Watson Assistant logs. It will retrieve and format logs, extract key metrics, and export the data to CSV for use in Watson Studio's Cognos Dashboard. **Note** that this is not a supported product.

## Prerequisites
1. Watson Assistant credentials
2. Watson Studio instance and project

## Instructions
1. Download the notebook `Watson Assistant Metrics Notebook.ipynb` locally.
2. Log into watson studio (https://dataplatform.cloud.ibm.com/) and open up (or create) the customer's project.
3. Click `Add to project +`
4. Click `notebook`
5. Click `From file`
6. Enter a name for the notebook, e.g. `Watson Assistant Metrics Notebook (Client_Name)`
7. Drag and drop downloaded file. 
8. Select runtime (default Python 3.6 XS is OK)
9. Click `create`
10. The first notebook (in the Housekeeping section) requires project id and token in order to save the CSV files to data assets. Follow these instructions: https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/token.html
11. Follow the remaining instructions of the notebook. Keep an eye out for `Action required` notes in Section 2.

Happy Analyzing!
