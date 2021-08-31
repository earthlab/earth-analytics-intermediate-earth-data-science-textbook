---
tags: JOSE
---
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

https://openjournals.readthedocs.io/en/jose/submitting.html
JOSE Papers Should:
* List all authors and affiliations.
* Describe the submission, and explain its eligibility for JOSE.
* Include a “Statement of Need” section, explaining how the submitted artifacts contribute to computationally enabled teaching and learning, and describing how they might be adopted by others.
* For software submissions, describe the functionality of the software, usage and recent experience of use in teaching and learning situations.
* For learning modules, describe the learning objectives, content, instructional design, and experience of use in teaching and learning situations.
* Tell us the “story” of the project: how did it come to be?
    Cite key references, including a link to the open archive of the sofware or the learning module.


# Summary
_Describe the submission, and explain its eligibility for JOSE._

Earth data science (EDS) or earth analytics refers skills at the intersection of data science and earth and environmental science data. Skills associated with EDS include working with many different types of data formats including complex spatial data programatticaly and programatic access to data via APIs. This intermediate level textbook provides scientists and others with the core concepts, coding approachs and skills needed to work with a suite of data types and formats that are common in the earth and environmental science domain. The textbook fuses the following topics: 1. technical open reproducible data science skills; 2. understanding of different data types and structures (including spatial, hierarchical, tabular); 3. data collection methods and associated quality issues that are important to consider in data processing and 4. scientific domain knowledge needed to make processing decisions that inform science questions. Our fusion aproach to teaching EDS makes this textbook unique as many existing resources focus on teaching scientists how to code in isolation of scientific applications and few focus on scientific data structures and open reproducible approaches. A scientist that can problem solve by associating concepts with problems rather than programming steps will be more empowered to improve their technical skills over time. The textbook is the second in a progression that begins with an [Introductory Earth Data Science Textbook](https://www.earthdatascience.org/courses/intro-to-earth-data-science/) and is published on the [earthdatascience.org learning portal](https://www.earthdatascience.org/courses/use-data-open-source-python/). The growing earthdatascience.org learning portal currently receives over 300,000 unique global users a month and has served millions of unique users since 2017. Both textbooks were developed to support the Earth Data Analytics Program lead by Earth Lab at the University of Colorado - Boulder. 

 
## The Story of the Online Textbook
While most scientists do not begin their careers with the goal of becoming data scientists, data science skills are becoming increasingly more integral to science given the growing complexity and size of available data. Skills at the intersection of data and earth and environmental science are in demand in the job market currently, yet these skills are not equally available to everyone yielding a shortage labor in the workforce [@10.1371/journal.pcbi.1005755:2017].

At the University of Colorado, Boulder, we developed and run a professional graduate program in Earth Analytics which teaches these in demand EDS skills to both graduate and undergraduate students using a unique blended online and in person classroom approach. In this program we take an active learning approach to EDS where students are emersed in EDS challenges and learn technical skills as they address those challenges programmatically using open reproducible science principles. Diversity in engagement is critical to the Earth Analytics program. Given, not all scientists have the time and / or resources to pursue such a degree, we publish our course content openly to facilitate and democratize access to these skills. If desired, students can also follow along with our course assignments using our online Earth Analytics Python course [@wasser_leah_2021_5228063]. Instructors are also able to repurpose and use the course content in their courses further enabling access to EDS skills.

## Testing and Back End Technical Infrastructure
Our lessons require a working Python environment and free and open source software (FOSS). Given updates to packages can often break code, and code approaches change with updates we developed a Continuous Integration system that builds, tests and pushes the lessons to our website repo for final review and publication. This allows us to consistently test lesson updates and catch errors associated with environment updates in advance.

## Audience and Skills Taught
The Intermediate Earth Data Science Textbook is designed for an audience with some introductory Python, git and bash experience. Our intended audience wants to enhance their skills as they work with larger and more complex data types; they further desire content that supports their domain specific needs to use spatial data such as remote sensing imagery or lidar raster format data. 

The textbook covers topics at the intersection of science and data science. For example, remote sensing topics include a high level overview of spatial concepts, sensor concepts involved in collecting the data such as uncertainty and quality control in addition to the technical information needed to actually open and work with the data. As such students reading the textbook are empowered with the conceptual knowledge needed to work with a host of datasets that are collected via sensors or that are spatial in nature. There is a section further devoted to data stories which helps students better understand some of the data collection methods associated with data structures and types taught in earlier chapters. Most chapters have a broad science theme such as fire and disturbance of flood events.  

Data topics in the textbook include basic spatial data manipulation and data processing of larger datasets in more complex formats such as Hdf4 and netCDF using tools such as xarray. The textbook also introduces APIs and programmatic data access, JSON and GeoJSON formats and basic visualization skills for data exploration.


## Lesson Use and Progression
Lessons include interactive coding examples which can be completed using a free platform such as Google Colab. Lessons can also be completed by installing our earth analytics Python environment [@leah_wasser_2021_4657501] on a local computer. This environment is hosted on GitHub and tested via continuous integration to ensure it's up to date on all operating systems (Windows, Apple, Linux). Instructions for setting up the environment can be found in our setup module hosted on earthdatascience.org [@wasser_leah_2021_5228300].


# Acknowledgements

We acknowledge contributions from Lauren Herwehe on some of the data story lessons. We also acknowledge Joseph Tucillo and Gina Li for contributing to our lesson development build and workflow. We would also like to acknowledge our textbook reviewers <insert names here> for providing us with helpful feedback that improved the lesson content.

# References


# Paper.bib





#  JOSS notes
List all authors and affiliations.
Describe the submission, and explain its eligibility for JOSE.
Include a “Statement of Need” section, explaining how the submitted artifacts contribute to computationally enabled teaching and learning, and describing how they might be adopted by others.
For software submissions, describe the functionality of the software, usage and recent experience of use in teaching and learning situations.
For learning modules, describe the learning objectives, content, instructional design, and experience of use in teaching and learning situations.
Tell us the “story” of the project: how did it come to be?
Cite key references, including a link to the open archive of the sofware or the learning module.





# Citations Notes from JOSS

Citations to entries in paper.bib should be in
[rMarkdown](http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html)
format.

For a quick reference, the following citation commands can be used:
- `@author:2001`  ->  "Author et al. (2001)"
- `[@author:2001]` -> "(Author et al., 2001)"
- `[@author1:2001; @author2:2001]` -> "(Author1 et al., 2001; Author2 et al., 2002)"

# Figures

Figures can be included like this: ![Example figure.](figure.png)
