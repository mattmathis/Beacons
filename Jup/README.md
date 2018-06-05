# Jupyter Notebooks

- BeaconsMasterAnnotations.ipynb - Build master annotations DB.
- etc

## Setup

* Install [Jupyter](http://jupyter.org/install)
* Install [gcloud SDK](https://cloud.google.com/sdk/downloads)
* Install the google-cloud-bigquery package:

 + `pip install --upgrade google-cloud-bigquery`
 
* Accessing M-Lab's data in BigQuery. See [MLab BQ quickstart](https://www.measurementlab.net/data/docs/bq/quickstart/):

 + Join: `discussion@measurement-lab.net` (Required)
 + Authenticate: `gcloud auth application-default login`
 + Set your default project: `gcloud config set project mlab-sandbox`
 
* Start Jupyter

 + `jupyter notebook`

## Notebooks

* BeaconsMasterAnnotations.ipynb - Identify and label Beacons.
* BeaconPopulationStatistics.ipynb - Population Statistics of the Beacons Themselves
* IndividualBeaconsTimeSeries.ipynb - Individual Beacon's performance TimeSeries
* PerformanceBucketTimeSeries.ipynb - Daily timeseries of continental scale performance statistics
* RTTtimeSeries.ipynb - Daily timeseries of continental scale RTT statistics
* MiscSmallQueries.ipynb - Summary statistics of the entire data set.

## References

* [Matplotlib](https://matplotlib.org/contents.html)
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/api.html)
* [BigQuery](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators)

