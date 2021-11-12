
# Milestone1 log: 

what I have done in the milestone1:

At the beginning, I wanted to analyze and compare the difference in gene expression between esophagus cancer patients with or without drinking history, because alcohol is a serious carcinogen, so I wanted to identify whether alcohol stimulation is an important factor leading to esophagus cancer in this analysis. However, in the initial data collation, I found that there was a serious shortage of cases that met the conditions of the two control groups in the database, and it didn’t also work out when I adjusted the filter conditions, let alone try to control variables (because I wanted to use DeSEQ later). Later, the variables to be analyzed and compared were changed into: Gender (because there is a significant difference between men and women in esophagus cancer, so it is also a seemly reliable variable to analyze) and age at diagnosis (but later I realized that choosing this variable is not specific for the study of esophagus cancer, since the risks of most types of cancers increase with age). I tried one last time with esophageal cancer: I changed the research object to Survival Time, and obtained the sufficient number of donors for analysis from ICGC portal. But later, I found that the file type I needed, HT-count, could not be found under esophageal cancer on ICGC platform, and I failed to use my current esophagus  cancer files on Vignette. Therefore, the previous collated data had to be abandoned.
However, I was very interested in this topic, namely the gene expression differences between the long survival time and short survival time of cancer, so I had to give up esophageal cancer as the type I wanted to study. Esophageal cancer could not meet the number of samples I needed to analyze on the three platforms. After research, I found that pancreatic cancer with high mortality and short survival is more suitable for studying this proposition. At the same time, I successfully identified enough files that meet the requirements on TCGA. I divided all cases into the long survival group (> 300days) and the short survival group (< = 300days) and I controlled for IIB cancer stage, male, dead and White. Therefore, I got 36 cases in the long survival group and 32 cases in the short survival group.

# Next step:

* The above controlled variables and grouping operations were performed in Excel, and I need to reproduce them in R.
* Upload the data to Google Drive
* Data was processed with DeSEQ and imported into Vignette
* Update and store scripts

# Known issues:
* look up into more details about DeSEQ 
* Rescheduling the planned milestone time points so that I can ensure that the analysis is completed efficiently and flawlessly at the appropriate time.
