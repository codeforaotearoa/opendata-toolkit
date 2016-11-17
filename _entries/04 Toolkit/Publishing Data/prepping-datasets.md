---
sectionid: preparing-datasets
sectionclass: h3
parent-id: publishing-data
title: Preparing the Datasets
number: 4220
---

In order to prepare data sets to maximise their usefulness, it's important to acknowledge the different types of formats available as well as the limitations that they may present:

<table border="1">
  <thead>
    <th colspan="3">Tabular</th>
    <tr>
      <th>File type</th>
      <th>Openness</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>CSV</td>
      <td>High</td>
      <td>The best format for opening structured data (eg. As spreadsheets)</td>
    </tr>
    <tr>
      <td>XLS or XLSX</td>
      <td>Low</td>
      <td>Limits machine reading and use on non-Microsoft systems</td>
  </tbody>
  <thead>
    <th colspan="3">Spatial</th>
    <tr>
      <th>File type</th>
      <th>Openness</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>KML</td>
      <td>High</td>
      <td>An open standard developed for Google Earth. May not translate to other systems. KMZ is also available as a packaged set of KML files.</td>
    </tr>
    <tr>
      <td>WMS</td>
      <td>High</td>
      <td>Standardised format for georeferenced map images</td>
    </tr>
    <tr>
      <td>WFS</td>
      <td>High</td>
      <td>Standardised format for geographical features</td>
    </tr>
  </tbody>
  <thead>
    <th colspan="3">Text</th>
    <tr>
      <th>File type</th>
      <th>Openness</th>
      <th>Notes</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>TXT</td>
      <td>High</td>
      <td>Simple text format readable on most operating systems. No formatting is available</td>
    </tr>
    <tr>
      <td>RTF</td>
      <td>High</td>
      <td>Simple text format readable on most operating systems which retains some formatting</td>
    </tr>
    <tr>
      <td>ODT</td>
      <td>Medium</td>
      <td>Limits machine reading</td>
    </tr>
    <tr>
      <td>DOC or DOCX</td>
      <td>Low</td>
      <td>Limits machine reading and use on non-Microsoft systems</td>
    </tr>
    <tr>
      <td>PDF</td>
      <td>Low</td>
      <td>Useful for document exchange to preserve formatting, but has limitations for machine reading, character recognition and remixing.</td>
  </tbody>
</table>

Any **tabular** data should also be cleansed. This means that files should be:

  - raw - Presented in the simplest possible format with a single header row and
  - clean - Using uniform data formatting (eg; Numerical dates, postcodes in every field) with no missing entries, no embedded non-text information, data in every field and as few mistakes as possible

**Examples of raw, clean data**
<table>
  <thead>
    <tr>
      <th>Date</th>
      <th>Age</th>
      <th>Gender</thSchedule regular updatesupdates>
      <th>Postcode</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>20/10/2013</td>
      <td>12</td>
      <td>M</td>
      <td>2580</td>
    </tr>
    <tr>
      <td>10/01/2013</td>
      <td>-</td>
      <td>F</td>
      <td>1462</td>
    </tr>
    <tr>
      <td>02/11/2011</td>
      <td>22</td>
      <td>M</td>
      <td>-</td>
    </tr>
    <tr>
      <td>12/05/2012</td>
      <td>45</td>
      <td>F</td>
      <td>1464</td>
    </tr>
    <tr>
      <td>19/01/2010</td>
      <td>75</td>
      <td>F</td>
      <td>1800</td>
    </tr>
  </tbody>
</table>

**Examples of data that is not raw or clean**

<table>
  <thead>
    <tr>
      <th colspan="4">Copyright of Dept. X</th>
    </tr>
    <tr>
      <th>Date</th>
      <th>Age</th>
      <th>Gender</th>
      <th>Postcode</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>01/20/2013</td>
      <td>Fifteen</td>
      <td>Female</td>
      <td>Barton</td>
    </tr>
    <tr>
      <td>10th Dec 11</td>
      <td>15</td>
      <td>Fem</td>
      <td>-</td>
    </tr>
    <tr>
      <td>02/11/2011</td>
      <td>xx</td>
      <td>Male</td>
      <td>3652</td>
    </tr>
    <tr>
      <td>12/05/2012</td>
      <td>45*</td>
      <td>F</td>
      <td>1464</td>
    </tr>
    <tr>
      <td>* Footnote Information</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
  </tbody>
</table>
