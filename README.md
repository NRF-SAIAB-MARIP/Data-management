<a name="readme-top"></a>

![Mar-RIP](/assets/img/marip.png)

<!-- <a href="https://aimeos.org/">
    <img src="/assets/img/nrf_saiab_cover.jpeg" alt="Logo" title="SAIAB" align="left" height="75" />
</a>

 <h1 align="left">Marine Remote Imagery Platform (MARIP) </h1>

The Marine Remote Imagery Platform (MARIP) provides scientists the opportunity to conduct ecological research on benthic biota across the continental shelf of South Africa, from the shallow subtidal to depths of 250 m.

![Mar-RIP no text](/assets/img/Mar-RIP_no_text.png)

-->

<div align="center">
<a href="https://nrf-saiab-marip.github.io/">Home</a> - 
<a href="https://nrf-saiab-marip.github.io/Data-management/">Data management</a> - 
<a href="https://nrf-saiab-marip.github.io/Data-management/">Data storage</a> - 
<a href="https://nrf-saiab-marip.github.io/Data-management/">Data analysis</a> - 
<a href="https://github.com/NRF-SAIAB-MARIP/NRF-SAIAB-MARIP.github.io/blob/8e2926f930f74cb2c400718b65b3329b13eaf4e5/README.md/">Github</a>
</div>

## Data management

Before we go into the field, a field data manager is assigned to ensure the integrity of the data and that the data gets handed over to the quality control technician after the field trip. The field data manager are usually senior students like 2nd or 3rd year PhD students or post-docs. Someone that has been in the field before. The field data manager ensures that before they go into the field that the template folder system is downloaded from the network attached storage at saiab and that all the videos and associated metadata are saved and renamed in the correct folder. Very important is that they also know the field trip code and the system of creating unique identifier codes for each sample collected. This ensure that the samples are correctly named from sample collection until we have completed the biodiversity data extraction is complete. Our system for creating a sample code starts with the field trip code which includes the date and location. In this example the field trip code is for samples collected as part of the long-term monitoring at Tsitsikamma National Park in February 2021, written as 2021-02_TNP.

![bruvs](/assets/img/bruvs_infographic.png)

## Navigation
1. [Create a sample in the field](https://nrf-saiab-marip.github.io/Data-management/#1-create-a-sample-in-the-field)
2. [Raw data captured in Template Folder System](https://nrf-saiab-marip.github.io/Data-management/#2-raw-data-captured-in-template-folder-system-tfs)
3. [TFS uploaded to the Network Attached Storage (NAS)](https://nrf-saiab-marip.github.io/Data-management/#3-tfs-uploaded-to-the-network-attached-storage-nas)
4. [Raw data final checks before processing & archiving](https://nrf-saiab-marip.github.io/Data-management/#4-raw-data-final-checks-before-processing--archiving)
5. [Initial metadata archived](https://nrf-saiab-marip.github.io/Data-management/#5-initial-metadata-archived)
6. [Cleaned Template Folder System downloaded for biodiversity extraction](https://nrf-saiab-marip.github.io/Data-management/#6-cleaned-template-folder-system-downloaded-for-biodiversity-extraction)
7. [Biodiversity & metadata archived on GlobalArchive](https://nrf-saiab-marip.github.io/Data-management/#7-biodiversity--metadata-archived-on-globalarchive)
8. [Biodiversity & metadata imported into Access database]

***

## 1. Create a sample in the field

Designated field data manager and can be senior students (2nd and 3rd year PhD or post-docs) who are on the trip.

The designated field trip data manager ensures that:
- they know the agreed upon field trip code
- the Template Folder System (TFS) is copied onto hard drives before departing for the field trip
- there are printed metadata sheets.
- the correct protocols are followed in the field.
- the videos are copied, renamed according to the unique identifier codes and saved in the right folder in the TFS.
- the field metadata are copied into the metadata template.
- any additional environmental data downloaded and saved in the TFS.
- hand over to QA/QC technician for upload onto the NAS.

## 2. Raw data captured in Template Folder System (TFS)

![Step_2](https://github.com/NRF-SAIAB-MARIP/Data-management/assets/155557651/709a4e58-3da9-4619-837a-72840c8e5f03)

## 3. TFS uploaded to the Network Attached Storage (NAS)

## 4. Raw data final checks before processing & archiving

The QA/QC technician or data manager checks that:
- Videos correctly named (by opening a few random videos and waiting for when the opcode is recorded in the field). If needed, the video pair can be formatted (concatenated and converted). 
- Extract thumbnails for habitat and field-of-view analyses.
- Calculates the temperature data and enters it in the metadata sheet. Enters any other environmental or ancillary data associated with each sample. 
- Cleaned metadata imported into Access database

## 5. Initial metadata archived

- Metadata imported into Access database
- Metadata uploaded onto GlobalArchive (if this function still exists)

![step_6](https://github.com/NRF-SAIAB-MARIP/Data-management/assets/155557651/5fdf4ad3-c33b-496d-b322-e0b63a9b76b0)


## 6. Cleaned Template Folder System downloaded for biodiversity extraction

Video analysts download a copy of the cleaned and checked TFS from the NAS
- Fish and size data extracted using EventMeasure software.
- Biophysical attributes of the seafloor extracted using TransectMeasure or Coral Point Count (CPCe)
- Ongoing QA/QC
  - Analysts checks their EMObs ~10 samples using CheckEM
  - Analysts also send these fixed EMObs to the QA/QC technician or data manager for added quality control


## 7. Biodiversity & metadata archived on GlobalArchive

- Final EMObs and metadata to data manager
- Final checks in CheckEM
- Uploaded onto GlobalArchive for archiving
- Publish to:
  - OBIS (Ocean Biodiversity Information System)
  - GBIF (Global Biodiversity Information Facility)
  - ODIS (Ocean Data and Information System)

 ## 8. Biodiversity & metadata imported into Access database
 
- Data extracted from EMObs and imported into Access database
- Updated metadata replaces the baseline metadata
- Data extracted using queries and linked pivot tables

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<img src="/assets/img/Footer.png" alt="Footer" title="footer" align="center"/>

