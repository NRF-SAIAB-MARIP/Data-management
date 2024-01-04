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

Before we go into the field, a field data manager is assigned to ensure the integrity of the data and that the data gets handed over to the quality control technician after the field trip. The field data manager are usually senior students like 2nd or 3rd year PhD students or post-docs. Someone that has been in the field before. The field data manager ensures that before they go into the field that the template folder system is downloaded from the network attached storage at saiab and that all the videos and associated metadata are saved and renamed in the correct folder. Very important is that they also know the field trip code and the system of creating unique identifier codes for each sample collected. This ensure that the samples are correctly named from sample collection until we have completed the biodiversity data extraction is complete. Our system for creating a sample code starts with the field trip code which includes the date and location. In this example the field trip code is for samples collected as part of the long-term monitoring at Tsitsikamma National Park in February 2021, written as 2021-02_TNP. To create unique identifier codes, we include equipment description (this is a more recent addition to the sample or opcode, but it avoids confusion when more than one type of sampling gear is used on the same fieldtrip. For instance, if we collecting stereo-BRUVs and lander samples during the same fieldtrip, but samples are not being deployed concurrently, then sample codes can be duplicated etc.) and finally we add the sample number. So, in this example, the first sample collected during the February 2021 long term monitoring field trip at TNP would be 2021-02_TNP_sBRUVs_001 and so forth. The logic behind this is that we can easily sort all our samples from different years, locations and instantly know when and where they were collected, what sort of imaging methods was used and its unique code. I would say that this unique identifier is essential for good data management and can be taken further to create a sample code species, where we combine the sample code with the species identified thereby giving that occurrence a unique identifier. So 2021-01_TNP_sBRUVs_001Chrysoblephys laticeps
After collecting the sample in the field, the raw data (which includes the video pair, fieldtrip metadata, temperature data and any other ancillary data) are copied into the template folder system in their allocated folders. I will show you an example of the template folder system later. During the copying process, the field data manager renames all the videos according to their unique identifier codes in the correct folder.
When the field trip is complete, the field data manager hands over the hard drives to the quality control and quality assurance technician. The person responsible for quality assurance and quality control (QA/QC) can be MARIP technicians, the data manager, or post-docs.
The technician uploads the template folder system onto SAIABs network attached storage (find out what this is)
From here the quality control technician verifies that all the data were correctly transferred (we use software called Teracopy) and prepares the raw data for video processing and archiving. 
The technician checks the videos (that they are not corrupted), that they copied correctly, that the unique identifier codes match the samples collected (can be done by randomly opening the video and waiting until they show the field metadata sheet recorded in the field) and in instances where videos require concatenation and conversion, the technician is also responsible for this.
They also extract images of the seafloor (to use for benthos and field of view analyses)
And they ensure that all the metadata is updated and complete before handing over to the data manager that checks that the coordinates is correct.
The data manager then formats the metadata sheet so that it can be imported into the access database and uploaded onto GlobalArchive for archiving. There is a question mark here since we are not sure if this functionality will still be available in the updated GlobalArchive. But we like this function as there are times that the extraction of biodiversity data only occurs much later. Showing the international BRUVs community what we have even though it might not be fully analysed, allows for them to at least enquire about the data and its availability.
When the raw data has been verified and prepared for processing, a video analyst downloads a copy of the TFS and start analysing the videos using EventMeasure following the SOPs. Ongoing quality control happens, and after about 10 videos, the analyst checks the EMObs in CheckEM, corrects any issues and sends the cleaned EMObs to the quality controller to check. Ant went into detail about this earlier.
When the analyst has completed their data extraction and checked their final EMObs in CheckEM and with the technician, they send the final EMObs and metadata to the data manager who prepares these for upload onto GA and import into SAIABs access database. Archiving onto GA allows us to publish to data sharing platforms such as Global biodiversity information facility, Ocean biodiversity information systems and Ocean data and information systems. 
Saving it in our Access database access the data through queries and linked pivot tables. For now, this is how we manage our data, but in the future when GA is fully functional, we might only use their platform to store and access our final data. 
This workflow shows new footage analysed. Older sample where quality control was done on the extracted data (so not in the EMObs). The modified data can also be archived on Global archive. 

![image](https://github.com/NRF-SAIAB-MARIP/Data-management/assets/155557651/321c811d-24ce-4dca-b6ed-5413d5d089d8)

![bruvs](/assets/img/bruvs_infographic.png)

## Navigation
1. [Socio-economic implications](https://nrf-saiab-marip.github.io/#socio-economic-implications)
2. [Functionality](https://nrf-saiab-marip.github.io/#functionality)
3. [Transformation & Capacity Development](https://nrf-saiab-marip.github.io/#transformation--capacity-development)
4. [Users](https://nrf-saiab-marip.github.io/#users)
5. [Useful code](https://nrf-saiab-marip.github.io/#useful-code)
6. [Future](https://nrf-saiab-marip.github.io/#future)
7. [Funders](https://nrf-saiab-marip.github.io/#funders)

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

<p align="right">(<a href="#readme-top">back to top</a>)</p>

