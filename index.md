---
---

Data Carpentry’s aim is to teach researchers basic concepts, skills, and tools 
for working
with data so they can get more done in less time and with less pain. This workshop uses 
Data Carpentry's approach to
teach data management and analysis for metagenomics research, including: 
best practices for the organization of bioinformatics projects and data, use
of command-line utilities, use of command-line tools to analyze sequence quality, 
use of R studio and use of R libraries to compare diversity between samples, 
and connecting to and using cloud computing. 
This workshop is designed to be taught over two full days of instruction.

**Please note that workshop materials for working with Metagenomics data are in “beta” development. 
These lessons are available for review and informal teaching experiences but are not yet part 
of The Carpentries’ official lesson offerings.**

Interested in teaching these materials? We have an 
[Slack channel](https://join.slack.com/t/metagenomicslesson/shared_invite/zt-pjaldgg7-BQVHxLTAqxlklkaH881xbA) 
were we will be happy to help you!


> ## Frequently Asked Questions
> Read our [FAQ](/metagenomics-workshop/faq/) to learn more about Data Carpentry's Metagenomics workshop as an Instructor or a workshop host.
{: .callout}

> ## Getting Started
>
> This lesson assumes that learners have no prior experience with the tools covered in the workshop.   
> 
> However, learners are expected to have some familiarity with biological concepts,
> including the 
> concept of DNA sequencing, nucleotide abbreviations, genome, microbiome, and taxonomy. Participants should bring their own laptops and plan to participate actively.  
> 
> To get started, follow the directions in the [Setup](setup.html) tab to 
> get access to the required software and data for this workshop.
> 
{: .prereq}

> ## Data
> 
> This workshop uses data from the environmental experiment: [Genomic adaptations in information 
> processing underpins trophic strategy in a whole-ecosystem nutrient 
> enrichment experiment](https://elifesciences.org/articles/49816), by Jordan G Okie et al.
> In this research, authors compared the differences between the microbial community 
> in its natural, oligotrophic, phosphorus-deficient 
>environment, a pond from the Cuatro Ciénegas Basin (CCB), and the same microbial 
>community under a fertilization treatment.
>
> All of the data used in this workshop can be downloaded from
>  [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.4285900.svg)](https://doi.org/10.5281/zenodo.4285900)
> More information about this data is available on the [Data page](https://carpentries-incubator.github.io/metagenomics-workshop/data/index.html).
{: .prereq} 

# Workshop Overview 

| Lesson    | Overview | Estimated time|
| ------- | ---------- | ---------- |
| [Project Organization and Management](https://carpentries-incubator.github.io/organization-metagenomics/) | Learn how to structure your metadata, organize and document your metagenomics data and bioinformatics workflow, and access data on the NCBI sequence read archive (SRA) database.|1:30 hr|  
| [Introduction to the Command Line](https://carpentries-incubator.github.io/shell-metagenomics/) |  Learn to navigate your file system, create, copy, move, and remove files and directories, and automate repetitive tasks using scripts and wildcards. | 4:00 hr| 
|[Introduction to R](https://carpentries-incubator.github.io/introduction-to-R-for-metagenomics/) | Use R studio to manage several data types and data structures. | 1:00 hr| 
|[Data Processing and Visualization for Metagenomics](https://carpentries-incubator.github.io/metagenomics/) | Use command-line tools to perform quality control, metagenomic assembly, metagenomic binning, taxonomic assignment, and diversity exploration. | 6:30 hr| 

<!--
# Optional Additional Lessons

| Lesson | Overview |
| ------- | -------- |
| [16S genomics](https://datacarpentry.org/genomics-r-intro/) | Use R to analyze and visualize between-sample variation. |
!-->

# Lessons Reference
The content of this page and three of the lessons presented in this workshop are adapted from lessons on the [Data Carpentry Genomics Workshop](https://datacarpentry.org/genomics-workshop/).

# Teaching Platform
This workshop is designed to be run on pre-imaged Amazon Web Services (AWS)
instances. All the software and data used in the workshop are hosted on an Amazon Machine Image (AMI).
If you want to run your own instance of the server used for this workshop, follow the directions in the [Setup](setup.html) tab. 

## Citation 
Preparing to submit to [JOSE](https://jose.theoj.org/about)
