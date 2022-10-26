# datareviewer-bvm-js

## Features

Batch Validation Manager (BVM) is a JavaScript web application to manage the validation of data using services provided by ArcGIS Data Reviewer for Server. The application can be configured to run Data Reviewer Batch Jobs either on a recurring basis—daily, weekly, monthly, or yearly—or once at a future date. A scheduled job identifies the data to be validated, the extent of the validation—the full database or a spatial extent—and whether validation should be run on all features or only changed features for enterprise workspaces.

![App](datareviewer-bvm-js.png)

## Setup
  * Download and unzip the .zip file or clone the repository.
  * Edit the settings.js file and update restReviewerMapServer and drsSoeUrl parameters to point to ArcGIS for Server machine name
  * Web-enable the directory.
  * Access the index.html page.
  
## Requirements
  * ArcGIS DataReviewer for Server 10.3.1 or later.
  * Experience with the ArcGIS API for JavaScript is helpful.

##Resources
- [Deploy data quality services lesson](http://server.arcgis.com/en/data-reviewer/latest/help/lesson-1-deploy-data-quality-services.htm)

##Issues
Find a bug or want to request a new feature? Please let us know by submitting an issue. 

##Contributing
Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](CONTRIBUTING.md).

## Licensing

A copy of the license is available in the repository's [LICENSE.txt](LICENSE.txt) file.

[](Esri Tags: Data Reviewer Batch Validation Manager BVM Batch Jobs Quality Control QC Scheduling)
[](Esri Language: JavaScript)
