# RNA-seq pipeline
A pipeline for RNA-seq analysis of two samples (with 4 replicates each)

Since in order to perform an RNA-seq analysis a user has to call many programs an automated pipline has been created which can be used in order to carry out the RNA-seq analysis automatically. Instead of using manually the required packages (Hisat2, Cufflinks, Cuffmerge and Cuffdiff ), in order to perform the aligment,transcript assembly and differential expression respectively, we created a script enabling the user to call it and perform these tasks automatically. The user has to define the location of the fna file ,the location of the genomic.gff file and name to his/her liking the two groups that they are putting into test for differential expression. An important note is that functional annotation is not included into the tool and that this tool runs with 4 replicates for each sample. If however a user has more or less replicates they should define it. 

> For additional information or questions please do not hesitate to contact us .
