# Jupyter Notebooks

The notebooks and other resource here were used to produce the figures in the paper:
Mathis, M. "Measurement Lab Beacons" [Submitted to IMC 2018].

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

* 180601BeaconsMasterAnnotations.ipynb - Identify and label beacons.
* 180602BeaconPopulationStatistics.ipynb - Population statistics of the beacons themselves.
* 180603IndividualBeaconsTimeSeries.ipynb - Data rate timeSeries for selected individual beacons.
* 180604PerformanceBucketTimeSeries.ipynb - Daily timeseries of continental scale rate statistics.
* 180605RTTtimeSeries.ipynb - Daily timeseries of continental scale RTT statistics.

## References

* [Matplotlib](https://matplotlib.org/contents.html)
* [Pandas](https://pandas.pydata.org/pandas-docs/stable/api.html)
* [BigQuery](https://cloud.google.com/bigquery/docs/reference/standard-sql/functions-and-operators)

