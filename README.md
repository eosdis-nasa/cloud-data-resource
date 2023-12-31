# EOSDIS Cloud Data Resource

Welcome to the EOSDIS Cloud Data Resource page! This document serves to act as a guide and resource to users working in the cloud. 
This page is meant to serve as an amalgamation of NASA's resources for using data from and in the cloud. This includes sources from NASA, NASA partners and other affiliates. 

### Why Use the Cloud?

NASA EOSDIS is evolving to use a commercial cloud to ingest, archive, process, distribute, and manage the anticipated large volumes of new mission data. Placing the EOSDIS archive collectively in the cloud will, for the first time, place NASA Earth Observing data “close to compute” and improve management and accessibility of these data while also expediting science discovery for data users. Having EOSDIS data in the cloud will not change the existing user experience of interacting with these data, but it will offer new methods of access not otherwise possible with on-premises platforms.



### Earthdata Cloud Primer for Amazon Web Services

The [Cloud Primer](https://www.earthdata.nasa.gov/learn/webinars-and-tutorials/cloud-primer-amazon-web-services)* is a series of tutorial PDFs to help walk a user through the steps needed to do analysis in the cloud. The Primer focuses on doing so through AWS (via [EC2](https://aws.amazon.com/ec2/) and [S3](https://aws.amazon.com/s3/)) as our data archives are stored in AWS. Users can take best advantage of data speeds and compute resources by using these Amazon services which "sit" directly next to the data. 

The tutorial is broken up into 9 parts: 

[01 — Why Use the Cloud?](https://www.earthdata.nasa.gov/sites/default/files/imported/01_Why_Use_the_Cloud.pdf)\
[02 — Understanding and Managing Costs in the AWS Cloud](https://www.earthdata.nasa.gov/sites/default/files/imported/02_Understanding_and_Managing_Costs_in_the_AWS_Cloud.pdf)\
[03 — Create a Basic Elastic Cloud Computer (EC2) Instance](https://www.earthdata.nasa.gov/sites/default/files/imported/03_Create_a_Basic_Elastic_Cloud_Compute__EC2__Instance.pdf)\
[04 — Connect to an AWS EC2 Instance - Windows and PuTTY](https://www.earthdata.nasa.gov/sites/default/files/imported/04_Connect_to_an_AWS_EC2_Instance_-_Windows_and_PuTTY.pdf)\
[05 — Connect to an AWS EC2 Instance - Mac OS X](https://www.earthdata.nasa.gov/sites/default/files/imported/05_Connect_to_an_AWS_EC2_Instance_-_Mac_OS_X.pdf)\
[06 — Create Cloud Storage Using AWS Single Storage Service (S3) Buckets](https://www.earthdata.nasa.gov/sites/default/files/imported/06_Create_Cloud_Storage_Using_AWS_Single_Storage_Service__S3__Buckets.pdf)\
[07 — Access AWS-hosted S3 Earthdata](https://www.earthdata.nasa.gov/sites/default/files/imported/07_Access_AWS-hosted_S3_Earthdata.pdf)\
[08 — Bring Your Own Script to the Cloud](https://www.earthdata.nasa.gov/sites/default/files/imported/08_Bring_Your_Own_Script_to_the_Cloud.pdf)\
[09 — Glossary and Acronyms Explained](https://www.earthdata.nasa.gov/sites/default/files/imported/09_Glossary_and_Acronyms_Explained.pdf)\

*Note: The Cloud Primer is currently in the process of being updated. If you have questions, comments or concerns, please feel free to [open an issue](https://github.com/eosdis-nasa/cloud-data-resource/issues). 


### Openscapes

[Openscapes](https://openscapes.org/) started in 2018 as a Mozilla fellowship to "help other environmental science teams harness the power of collaborative coding and foster a scientific culture that is more welcoming, open, and efficient". It is now a NASA [ROSES](https://science.nasa.gov/researchers/sara/grant-solicitations) funded program meant to support researchers migrating workflows to the cloud by working with mentors from the EOSDIS ([NASA's Earth Observing System Data and Information System](https://www.earthdata.nasa.gov/eosdis)) DAACs ([Distributed Active Archive Centers](https://www.earthdata.nasa.gov/eosdis/daacs)) to help support the specific needs of the NASA community. 

Five EOSDIS DAACs are participating in the first cohort: Atmospheric Science Data Center ([ASDC](https://asdc.larc.nasa.gov/)), Goddard Earth Sciences Data and Information Services Center ([GES DISC](https://disc.gsfc.nasa.gov/)), Land Processes DAAC ([LP DAAC](https://lpdaac.usgs.gov/)), National Snow and Ice Data Center DAAC ([NSIDC](https://nsidc.org/home)), and Physical Oceanography DAAC ([PO.DAAC](https://podaac.jpl.nasa.gov/)). Each DAAC selected up to three mentors, who are already helping researchers utilize the Earthdata Cloud.

The Openscapes [Github page](https://nasa-openscapes.github.io/) has phenomenal resources for connecting with mentors, presentations, and the [NASA Earthdata Cloud Cookbook](https://nasa-openscapes.github.io/earthdata-cloud-cookbook/) which is a great resource to answer questions about if cloud analysis is for you and how to and several how-to's for those less software-inclined. They also have a workshop at AGU 2023: [Enabling Analysis in the Cloud Using NASA Earth Science Data](https://agu.confex.com/agu/fm23/meetingapp.cgi/Session/193427)!

### DAAC Specific Resources

Several DAACs have guides on how they have migrated to the cloud and how you as a user can take advantage of their cloud data. Although these resources are largely specific to that particular DAAC, much of the information is useful in any context. 

##### NASA Earthdata Cloud Data Access Guide

The [NASA Earthdata Cloud Data Access Guide](https://nsidc.org/data/user-resources/help-center/nasa-earthdata-cloud-data-access-guide) from the [National Snow and Ice Data Center (NSIDC)](https://nsidc.org) is a step-by-step guide for accessing ICESat products in the cloud. It walks through finding the data via [Earthdata Search](https://search.earthdata.nasa.gov), saving the generated S3 links for cloud use, creating temporary AWS S3 credentials, and using the data from an S3 bucket in an EC2 instance. 

##### LAADS DAAC in the Cloud

The [LAADS DAAC in the Cloud](https://ladsweb.modaps.eosdis.nasa.gov/cloud/) from the [Level-1 and Atmospheric Archive & Distribution System DAAC (LAADS)](https://ladsweb.modaps.eosdis.nasa.gov) includes benefits for moving into the cloud, a video instruction course for using S3 direct access and Earthdata Search in the cloud, some frequently asked questions and a migration to the cloud timeline. 

##### PO.DAAC Cloud Data Resources
[PO.DAAC](https://podaac.jpl.nasa.gov) has two cloud data resources - a [written slideshow guide](https://podaac.jpl.nasa.gov/cloud-datasets/about) detailing how to access data and utilize it in the cloud, as well as a [recorded webinar](https://www.earthdata.nasa.gov/learn/webinars-and-tutorials/webinar-cloud-computing-PO.DAAC) detailing a step-by-step walkthrough of using PO.DAAC data hosted in Earthdata Cloud that assumes zero knowledge of both AWS services and Earthdata Cloud. 


### Questions? Comments?

If you have any questions or comments regarding using NASA Earthdata in the cloud, or want to request any resources, please feel free to [open a Github issue](https://github.com/eosdis-nasa/cloud-data-resource/issues). If you don't have a Github account or are unsure of how to open an issue, you can always email me at nicholas.l.doty@nasa.gov. 

  [![Hits](https://hits.sh/github.com/eosdis-nasa/cloud-data-resource.svg)](https://hits.sh/github.com/eosdis-nasa/cloud-data-resource)
