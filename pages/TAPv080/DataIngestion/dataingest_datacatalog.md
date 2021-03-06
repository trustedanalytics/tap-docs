---
title: Data Ingestion
keywords: TAP data ingestion
last_updated: 'October, 2016'
tags:
  - Data Ingestion
summary: Insert the summary paragraph here.  To edit the summary you must edit the meta data for this post. 
sidebar: TAPv080_sidebar
permalink: /DataIngestion/dataingest_datacatalog.html
folder: TAPv080/DataIngestion/
published: true
---

## Importing Data to TAP Using the Data Catalog
1.  From the TAP Console, select **Data Catalog** from the main menu then select the tab **Submit Transfer**.
![Ingesting Data Screen 1](/images/dataingest_datacatingest_screen1.jpg)
1.	Choose **Link** to input a URL to a data set _or_ **Local Path** to activate a “Choose File” file browse button, which opens your local file directory browser.  _The upload button will not be active until a file has been chosen or a URL provided._
![Ingesting Data Screen 2](/images/dataingest_datacatingest_screen2.jpg)
1.	Enter a title in the form field labeled “title” _The upload button will not be active until a title has been provided._ 
1.	Select a category to help others find your data easily. (**Other** is the default.)
1.	Select the **Upload button**.
It may take 30 seconds to a couple of minutes, depending on the size of the data file you are ingesting. Your data set will now be listed in the **Data Catalog>Data sets** tab.
![Ingesting Data Screen 3](/images/dataingest_datacatingest_screen3.jpg)

##Importing Options
TAP provides multiple options for data ingestion including the [Import from Amazon S3](Data_Catalog_Downld_S3.md), [DAS (Data Acquisition Service)](Data_Acquisition.md), [SQL Import Scheduler](dataingest_sqlimport_scheduler.md), and streaming data [using Gearpump](dataingest_streamgearpump.md).  Please visit our [community site](http://community.trustedanalytics.org) for added insights into using TAP and for asking questions.

