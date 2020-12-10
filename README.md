# airflow-azure-data-factory-tutorial
This repo contains an Astronomer project with an example DAG showing how to use Airflow to orchestrate an Azure Data Factory pipeline. A guide discussing the DAG and concepts in depth will be published soon.

## Requirements
In addition to the Astronomer CLI, to follow this tutorial you will need an Azure account with the following resources:

 - An Azure Data Factory pipeline
 - An Azure Blob Storage account
 - The ability to create a registered application and add role assignments to the above resources


## Getting Started
The easiest way to run these example DAGs is to use the Astronomer CLI to get an Airflow instance up and running locally:

 1. [Install the Astronomer CLI](https://www.astronomer.io/docs/cloud/stable/develop/cli-quickstart)
 2. Clone this repo somewhere locally and navigate to it in your terminal
 3. Initialize an Astronomer project by running `astro dev init`
 4. Start Airflow locally by running `astro dev start`
 5. Navigate to localhost:8080 in your browser and you should see the tutorial DAGs there
