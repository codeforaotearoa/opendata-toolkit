---
sectionid: preparing-datasets
sectionclass: h3
parent-id: publishing-data
title: Preparing the Datasets
number: 4220
---

In order to prepare data sets to maximise their usefulness, it's important to acknowledge the different types of formats available as well as the limitations that they may present:

|| **Tabular**                ||
| File Type   | Openness | Notes |
| ----------- | :------: | :---: |
| CSV         | High     | The best format for opening structured data (eg. As spreadsheets) |
| XLS or XLSX | Low      | Limits machine reading and use on non-Microsoft systems |
|| **Spatial**                ||
| File Type   | Openness | Notes |
| ----------- | :------: | :---: |
| KML         | High     | An open standard developed for Google Earth. May not translate to other systems. KMZ is also available as a packaged set of KML files. |
| WMS         | High     | Standardised format for georeferenced map images |
| WFS         | High     | Standardised format for geographical features |
|| **Text**                   ||
| File Type   | Openness | Notes |
| ----------- | :------: | :---: |
| TXT         | High     | Simple text format readable on most operating systems. No formatting is available |
| RTF         | High     | Simple text format readable on most operating systems which retains some formatting |
| ODT         | Medium   | Limits machine reading |
| DOC or DOCX | Low      | Limits machine reading and use on non-Microsoft systems
| PDF         | Low      | Useful for document exchange to preserve formatting, but has limitations for machine reading, character recognition and remixing. |

Any **tabular** data should also be cleansed. This means that files should be:

  - raw - Presented in the simplest possible format with a single header row and
  - clean - Using uniform data formatting (eg; Numerical dates, postcodes in every field) with no missing entries, no embedded non-text information, data in every field and as few mistakes as possible

**Examples of raw, clean data**

| Date       | Age | Gender | Postcode |
| ---------- | --- | ------ | -------- |
| 20/10/2013 | 12  | M      | 2580     |
| 10/01/2013 | -   | F      | 1462     |
| 02/11/2011 | 22  | M      | -        |
| 12/05/2012 | 45  | F      | 1464     |
| 19/01/2010 | 75  | F      | 1800     |

**Examples of data that is not raw or clean**

|| Copyright of Dept. X ||
| Date       | Age     | Gender | Postcode |
| ---------- | ------- | ------ | -------- |
| 01/20/2013 | Fifteen | Female | Barton   |
| 10th Dec 11| 15      | Fem    | -        |
| 02/11/2011 | xx*     | Male   | 3652     |
| 12/05/2012 | 45      | F      | 1464     |
| * Footnote Information                |||
