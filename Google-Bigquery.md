# Connecting to MIMIC using Google BigQuery

Step 1: Request access to physionet databases 
- Create a physionet account and link it with the google email address you will use to access BigQuery
- (Profile -> Cloud -> Google Cloud Platform). If necessary, add your google email address under `Emails`.
- Navigate to your data source (e.g., [MIMIC-III demo](https://physionet.org/content/mimiciii-demo/1.4/))
- Scroll down to `Files`, click `Request access using Google BigQuery`.
- [reference](https://mimic.mit.edu/docs/gettingstarted/cloud/link/)

Step 2: Set up BigQuery and add Physionet-Data
- Set up a BigQuery sandbox project (billing information required and it may post a temporary charge for verification. It will not be linked with your project)
- Under `Explorer`, click `+Add Data`
- Scroll down to `Star a project by name`, enter `physionet-data`
- physionet-data should appear in the explorer menu, containing the datasets requested using step 1.
- See the following [guide](https://mimic.mit.edu/docs/gettingstarted/cloud/bigquery/)
