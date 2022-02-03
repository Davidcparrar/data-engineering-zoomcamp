## Question 1: Start date for the Yellow taxi data (1 point)

You'll need to parametrize the DAG for processing the yellow taxi data that
we created in the videos. 

What should be the start date for this dag?

* **2019-01-01**
* 2020-01-01
* 2021-01-01
* days_ago(1)


## Question 2: Frequency for the Yellow taxi data (1 point)

How often do we need to run this DAG?

* Daily
* **Monthly**
* Yearly
* Once

![Airflow Yellow](../../Figs/FHV_pipeline.PNG?raw=true 'Yellow trips Pipeline')

## Question 3: DAG for FHV Data (2 points)

Now create another DAG - for uploading the FHV data. 

We will need three steps: 

* Download the data
* Parquetize it 
* Upload to GCS

If you don't have a GCP account, for local ingestion you'll need two steps:

* Download the data
* Ingest to Postgres

Use the same frequency and the start date as for the yellow taxi dataset

Question: how many DAG runs are green for data in 2019 after finishing everything? 

** R / 12**

![Airflow Zones](../../Figs/FHV_pipeline.PNG?raw=true 'For Hire Pipeline')

## Question 4: DAG for Zones (2 points)

How often does it need to run?

* Daily
* Monthly
* Yearly
* **Once**

![Airflow Zones](../../Figs/Zones_pipeline.PNG?raw=true 'Zones Pipeline')


### Files uploaded

![GCS](../../Figs/Uploaded_Files.PNG?raw=true 'Files GCS')