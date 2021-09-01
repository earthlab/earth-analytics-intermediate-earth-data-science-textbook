# JOSE Paper - Intermediate EDS Textbook

title: 'Data Science for Earth and Environmental Data - The Intermediate Earth Analytics Online Textbook'
tags:
  - Python
  - data science
  - earth analytics
  - earth data science
  - spatial data
  - remote sensing
authors:
  - name: Leah A. Wasser
    orcid: 0000-0002-8177-6550
    affiliation: "1, 2" 
  - name: Jenny Palomino
    orcid: 0000-0003-4879-9299
    affiliation: "3"
  - name: Nathan Korinek
    orcid: 0000-0002-8177-6550
    affiliation: "1"
  - name: Martha Morrisey 
    affiliation: "5"
  - name: Chris Holdgraf
    orcid: 0000-0002-2391-0678
    affiliation: "4"
affiliations:
 - name: Earth Lab, University of Colorado - Boulder
   index: 1
 - name: pyOpenSci
   index: 2
 - name: Google
   index: 3
 - name: 2i2c
   index: 4
 - name: Development Seed
   index: 5
date: 20 August 2021
bibliography: paper.bib
---

# Summary

Science today is becoming increasingly data-driven which in turn has preciptated a growing demand for skills at the intersection of science and data science in both industry and academia. Earth and environmental data science (EDS), also known as earth analytics, refers skills at this intersection and as defined by the Earth Analytics Program includes: 1. technical open reproducible data science skills; 2. understanding of different data types and structures (including spatial, hierarchical, tabular); 3. data collection methods and associated quality issues that are important to consider in data processing and 4. scientific domain knowledge needed to make processing decisions that inform science questions. As defined we also include soft skills in this suite of skills such as science communication and interdisciplinary collaboration. The intermediate earth and environmental data science textbook provides scientists with the core concepts, coding approaches and technical skills and knowledge needed to work with a suite of data types and formats that are common in the earth and environmental science domain. 

Our fusion aproach to teaching EDS makes this textbook unique. Many existing resources focus on teaching scientists how to code in isolation of scientific applications and few focus on scientific data structures combined with open reproducible approaches and principles. A scientist that can problem solve by associating concepts with problems rather than learning programming "steps" will be more empowered to use different types of data and approaches and thus b build upon their technical skills over time. The textbook is the second in a progression that begins with an [Introductory Earth Data Science Textbook](https://www.earthdatascience.org/courses/intro-to-earth-data-science/). It is published on the [earthdatascience.org learning portal](https://www.earthdatascience.org/courses/use-data-open-source-python/) which currently receives over 200,000 unique global users a month and has served millions of unique users since 2018. Both textbooks were developed to support the Earth Data Analytics Program lead by Earth Lab at the University of Colorado - Boulder. 

 
## The Story of the Online Textbook
While most scientists do not begin their careers with the goal of becoming data scientists, data science skills are becoming increasingly more integral to science given the growing complexity and size of available data. Skills at the intersection of data and earth and environmental science are in demand in the job market currently, yet these skills are not equally available to everyone yielding a workforce shortage [@10.1371/journal.pcbi.1005755:2017].

At the University of Colorado, Boulder, we developed and run a professional graduate program in Earth Data Analytics which teaches these in demand EDS skills to both graduate and undergraduate students using a unique blended online and in-person classroom approach. In this program we take an active learning approach to EDS where students are emersed in EDS challenges and learn technical skills as they address those challenges programmatically using open reproducible science principles. Diversity in engagement is critical to the Earth Analytics program. Given, not all scientists have the time and / or resources to pursue such a degree, we publish our course content openly to facilitate and democratize access to these skills. This textbook aligns with the second of three courses in the Earth Data Analytics program. Students can follow along with our course assignments using the online Earth Analytics Python course [@wasser_leah_2021_5228063]. Instructors can repurpose and use the course content in their courses further enabling access to EDS skills.


## Audience and Skills Taught
The Intermediate Earth Data Science Textbook is designed for an audience with some introductory Python, git and bash experience. Our intended audience wants to enhance their skills as they work with larger and more complex data types; they further desire content that supports their domain specific needs to use spatial data such as remote sensing imagery or lidar raster format data. 

The textbook teaches core skills and concepts topics using applied scientific applications. For example, remote sensing topics include a high level overview of spatial concepts, sensor concepts involved in collecting the data such as uncertainty and quality control in addition to the technical information needed to actually open and work with the data. As such students reading the textbook are empowered with the conceptual knowledge needed to work with a host of datasets that are collected via sensors or that are spatial in nature. There is a section further devoted to data stories which helps students better understand some of the data collection methods associated with data structures and types taught in earlier chapters. Most chapters have a broad science theme such as fire and disturbance of flood events.

Data topics in the textbook include basic spatial data manipulation and data processing of larger datasets in more complex formats such as Hdf4 and netCDF using tools such as xarray. The textbook also introduces APIs and programmatic data access, JSON and GeoJSON formats and basic visualization skills for data exploration.

## Lesson Use and Progression
Lessons include interactive coding examples which can be completed using a free-to-use platform such as Google Colab. Lessons can also be completed by installing our earth analytics Python environment [@leah_wasser_2021_4657501] on a local computer. This environment is hosted on GitHub and tested via continuous integration to ensure it is up to date on all operating systems (Windows, Apple, Linux). Instructions for setting up the environment can be found in our setup module hosted on earthdatascience.org [@wasser_leah_2021_5228300].

## Testing and Back End Technical Infrastructure
Our lessons require a working Python environment and use free and open source software (FOSS). Given updates to packages can often break code, and code approaches change with updates we developed a Continuous Integration system that builds, tests and pushes the lessons to our website repo for final review and publication. This allows us to consistently test lesson updates and catch errors associated with environment updates in advance.

# Acknowledgements

We acknowledge contributions from many who have contributed to our textbook via edits and content suggestions and updates. These people include students in the Earth Data Analytics program who catch issues with the lessons, Lauren Herwehe and others for work and feedback on some of the data story and other lessons. We also acknowledge Joseph Tucillo and Gina Li for contributing to our lesson development CI build and workflow. We would also like to acknowledge our textbook reviewers <insert names here> for providing us with helpful feedback that improved the lesson content.

# References



