# Final-Project Outline
## Title
Using DeSEQ2 to inspect the gene expression differences from Esophagus cancer within T3N1M0 stage between a longer survival time section and a shorter survival time section
## Author
Huizi Gao
## Overview of project
In this analysis, I will look for differences in gene expression between the patients with a long survival time and the patients with a short survival time. The two groups were divided on whether the survival time is over two and a half years (913 days) or not. After finishing this analysis, I expect a relationship between the gene expression in esophageal cancer at the T3N1M0 stage and patients’ survival time could be identified, so as to provide data support for the development of prospective therapies that can prolong the life of patients. I will use DeSEQ to remove the variables I am not interested in and follow the specific steps in the Vignette. For variables, sex and country are controlled, the key variable is the survival time. 
## Data
* The dataset I need can be downloaded from the ICGC portal. Here is the link:https://dcc.icgc.org. They are publicly available 
* Sex: male
* Country: UK
* I will use 2.5 years(913 days) of the survival time as a delimitation and divide the donors into 2 groups: a long survival time group and a short survival time group. After examining clinical data, the former group has 31 tumor samples while the latter group has 60 tumor samples.
## Milestone 1

**Due Date: November 11th**

**The main task in the first step is to make data fully loaded into the vignette through HT-SEQ steps**, which is prepared for completing an entire first draft of analysis analyzed through the vignette in the succeeding steps.

## Milestone 2
**An initial completion of vignette.** I will complete an entire first draft of analysis analyzed through the vignette.Data loaded into vignette (through htseq), for seeking feedback.

Form the core content of the final project in this step.
## Deliverable

**Due Date: December 3rd**

A complete repository with clear documentation and description of your analysis and results.
