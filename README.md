# Patient Journey with ChatGPT
This repo will replicate my existing [graph-based patient journey analysis](https://github.com/danb-neo4j/patient_journey), but will incorporate ChatGPT via the Python API. The objective is to demonstrate how ChatGPT (or other LLMs) can enhance exploratory data analysis, graph data model development, graph exploratory data analysis, and the patient journey analysis itself. This will include graph and non-graph elements of the workflow. 

## Notebooks:
**[Tabluar EDA](https://github.com/danb-neo4j/patient_journey_chatGPT/blob/main/patientJourney_tabularEDA_chatGPT.ipynb):** In this notebook I perform a traditional exploratory data analysis on the four data sources include in the Neo4j graph. However, throughout the process I incorporate ChatGPT to identify important features, evaluate statistical distributions, and suggest potential graph data models. 

**[Data Loading](https://github.com/danb-neo4j/patient_journey_chatGPT/blob/main/patientJourney_dataLoad_chatGPT.ipynb):** In this notebook I ask ChatGPT several questions about creating graph data models and generating Cypher code to implement them from the Synthea data. The questions are much more generative in nature than with the tabular EDA notebook and identified challenges with writing prompts for these uses along with ChatGPT's ability to provide usable Cypher. 


*Note: This repo is a work in progress as of May 11, 2023. Additional notebooks will be added as they are completed.*
