# Description

This workflow removes a sensor isolation in Carbon Black Response from an event in InsightIDR.

# Key Features

* Remove isolated asset from containment

# Requirements

* Admin access to Rapid7 InsightIDR
* API and account credentials for Carbon Black Response

# Documentation

## Setup

* Configure the connections for Cb Response plugin in Rapid7 InsightConnect
* Navigate to Rapid7 InsightIDR's automation page at #/automation/workflows
* Click Create Workflow from Template
* Select Containment Workflow in the Action Category
* Select Unisolate Sensor in Cb Response for the Workflow or Template
* Name the workflow
* Select the connection you setup in the beginning
* Finish by creating the workflow

## Technical Details

Plugins utilized by workflow:

|Plugin|Version|Count|
|----|----|--------|
|carbon_black_response|3.1.7|2|

## Troubleshooting

_There is no troubleshooting information at this time_

# Version History

* 1.0.0 - Initial workflow

# Links

## References

* [Carbon Black Response API Documentation](https://developer.carbonblack.com/reference/enterprise-response/6.1/rest-api/)