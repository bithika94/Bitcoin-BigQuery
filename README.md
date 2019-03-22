# Bitcoin-BigQuery
The goal of this project is to provide an easy introduction to Bitcoin Transactions and to analyze the data from BigQuery using Python. In this project, I will uncover a couple of interesting trends in how this volatile market behaves, and how they are evolving. Google BigQuery is an enterprise data warehouse technology that enables super fast SQL queries on big data. I have used the dataset from:
https://bigquery.cloud.google.com/dataset/bigquery-public-data:bitcoin_blockchain

Step 1 - Setup Your Data Laboratory

STEP-1.1 Install Anaconda

Install Anaconda using the official website-  https://www.continuum.io/downloads

Step 1.2 - Start An Interative Jupyter Notebook

Create a new Python Notebook

Step 1.3 - Import the Dependencies At The Top of The Notebook

Import dependencies - Pandas, Scikit, Numpy, matplotlib, seaborn, scipy

Step 2 - Retrieve Bitcoin Pricing Data

Step 2.1 - Installing the client library

I used this command for setting up Python Developement Environment
pip install --upgrade google-cloud-bigquery

Step 2.2 - Setting up authentication

1. In the GCP Console, go to the Create service account key page.
2. From the Service account list, select New service account.
3. In the Service account name field, enter a name.
4. From the Role list, select Project > Owner.
5. Click Create. A JSON file that contains your key downloads to your computer.
6. Provide authentication credentials to your application code by setting the environment variable GOOGLE_APPLICATION_CREDENTIALS
With command prompt:
set GOOGLE_APPLICATION_CREDENTIALS=[PATH]

Step 2.3 - Using the client library
	I have used the client library to connect Bigquery with Python
	
	
	# from google.com import bigquery
	# client = bigquery.Client()
