# Description

This workflow enriches an IDR alert by performing a lookup on all domains in the investigation with Recorded Future.

# Key Features

* Perform a domain lookup automatically from any IDR alert

# Requirements

API and account credentials for Recorded Future

# Documentation

## Setup

* Download the workflow or clone the repository `git clone https://github.com/rapid7/insightconnet-workflows.git`
* Login to InsightConnect, and “Import” the .icon file into the workflow builder
* Configure the connections for the Cb Response plugin
* Activate your workflow
* Navigate to IDR's alert triggers page at #/automation/alerts
* Click Create Alert Trigger
* Select Look Up Domains with Recorded Future
* While Selecting Alerts, check any alerts you would like to automatically enrich

## Technical Details

Plugins utilized by workflow:

|Plugin|Version|Count|
|----|----|--------|
|Recorded Future|1.5.2|1|

## Troubleshooting

_There is no troubleshooting information at this time_

# Version History

* 1.0.0 - Initial workflow

# Links

## References

* [Recorded Future API Documentation](https://support.recordedfuture.com/hc/en-us/categories/115000803507-Raw-API)