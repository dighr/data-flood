---
layout: page
title: Global Nutrition Dashboard
description: Global Nutrition Dashboard
sitemap:
    priority: 0.7
    lastmod: 2018-11-22
    changefreq: weekly
---
# Global Nutrition Dashboard

### Challenge presented by Action contre La Faim (Action Against Hunger)  

### Problem

Lack of timely and easy access to completed and validated nutrition sub-national survey results. 

Most countries lack a systematic way of centrally storing, accessing and visualizing validated nutrition surveys conducted at sub-national level. This data is crucial for identification of humanitarian needs, proper planning of targeted nutrition programs and responses, as well as effective resource management and allocation. Access to nutrition survey reports (PDF format) and summaries of survey results (Excel format – template provided in the Information Management (IM) toolkit) is usually granted through direct email request from the stakeholder undertaking the survey or the national nutrition cluster/sector. Currently, there is no aggregator/ dashboard that allows for consolidation and dissemination of key nutrition indicators derived from validated sub-national surveys. This gap in accessibility leads to an underutilization of data at sub-national, national, regional and global level. 

### What is the proposed solution to this challenge?

Timely collation of validated nutrition survey results through a central aggregator and online dashboard for enhanced analysis, visualization, and wider dissemination of data. 
- The aggregator combines raw data from all SMART surveys. It is a global repository of raw datasets synchronized from mobile data collection systems pending stakeholder consent. 
- The dashboard analyzes data and visualizes survey results. It uses deep analysis and derivative learning to display a summary of key results processed **either directly from the aggregator’s raw datasets or indirectly from summaries of survey results (using the IM toolkit template).** It will be managed through an established system such as the Global Nutrition Cluster (GNC).

### What has been done so far?

The GNC has attempted to collect results through manually filling out standardized excel-based templates (the IM toolkit), which is populated with sub-national survey results and hosted by the nutrition cluster at country-level. The IM toolkit will be revised to improve on content and user experience prior to its integration into the dashboard.

UNICEF uses NutriDash, an internal data platform to collect and share data on nutrition programs from 110 countries (upload restricted to UNICEF staff). Building on experiences from NutriDash, it is possible to develop a similar system for the collection of sub-national survey data.

The National Information Platforms for Nutrition (NIPN) has designed and nearly completed the development of an aggregator for survey data. The source code may be used as a base for the development of the proposed survey aggregator. 

### Who are the key players?

The GNC (technical guidance, cluster/sector partners mobilization, dashboard hosting), UNICEF (technical guidance based on experience with NutriDash), Action Against Hunger Canada-SMART (technical guidance and administrative support in designing and developing the solution), World Food Programme (coordination and management of data), and York University-Information Retrieval and Knowledge Management Research Lab (development of solution).

### What hurdles will a solution have to overcome?

Prior to development, a deep needs assessment will be required to inform the development of the solution. An analysis of available codes and required resources, softwares, languages will be conducted in order to produce a detailed blueprint of the solution. Additionally, the IM tools need to be simplified (succinct and easy to use) and made compatible with the dashboard in order to reduce the time spent in compiling and collating data from different sources. This step will require multiple consultations with the technical teams involved and with experienced IM officers and cluster coordinators at country-level. 

During development, the engineers will need to build an Application Program Interface (API) to allow the aggregator to sync data from available platforms and to the dashboard. They will also need to be sensitized on the types of trend analyses required by the nutrition sector. 

Following the development phase, the proposed solution could face challenges and barriers during its implementation: 
- Problems of connectivity.
- Data sensitivity.
- Upload of un-validated data.
- Additional time required from partners and IM officers when choosing to upload a summary of the survey rather than sharing raw data.

### What are the possibilities you see for better leveraging emerging data science & AI capabilities?

**Data transfer and synchronization** – Leveraging on mobile data collection systems that have digitized the process of data collation and on solutions for software interaction. With the use of API, the aggregator will sync data from different mobile data collection and analysis platforms and the dashboard will provide synchronized options to access survey data from different contexts through the aggregator.

**Data analysis** – a. Replicating the available analyses in NutriDash and graphing and visualizing trends on the proposed dashboard; b. Ensuring compatibility of the aggregator and dashboard with all operating systems. 

**Data storage** – Allowing long-term data storage and archiving on both the aggregator and dashboard. Security and confidentiality measures will need to be in place to avoid data breach.

**Data dissemination** – Linking the dashboard to social media platforms. This option can improve the dissemination of information.
