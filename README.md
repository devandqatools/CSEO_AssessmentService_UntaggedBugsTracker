# Project Title
CSEO Assessment Service Untagged Bugs Tracker

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

Download the Excel: https://msit.powerbi.com/groups/3bb1acb0-9ece-4448-bcf1-98eb7bb5c561/reports/afc15ddd-e25d-4d5a-8a4c-b506adc32eb4/ReportSection592ccccc846b317de99c

Note: Before downloading the report make sure verify the last refresh date.

```
* Start Visual Studio 2017 or Update  version and select File > Open > Project/Solution.
* Go to the directory to which you unzipped file. Then go to the subdirectory named for the sample and double-click the Visual Studio 2012 Update 2 Solution (.sln) file.
* Follow the steps:
    * To Clean the project solution:
         1. Select main root folder ScorecardComparsion-Report in Solution Explorer.
         2. Click Clean.
* To build the project solution:
    * Select AIRT Email Reports in Solution Explorer.
    * Press Ctrl+Shift+B or use Build > Build Solution.
    * Or configure jenkins with github for automated build process
```
```html
<!--Update below path for Excel Path in Config file-->

<add key="ExcelLocPath" 
     value="D:\Development\AutoMailer_Untagged\AutoMailer_Untagged_ExcelTrack\CSEO_Untagged_ExcelRetrival-master\ScorecardComparison-Report\UntaggedBugsExcelReport\AllBugsData.xlsx"/>
``
