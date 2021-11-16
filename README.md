This is a code in a R markdown format **patient_S_analysis.Rmd**, used for analysis of patient-specific mutation effects on atigen presentation for CD4 and CD8 T cells, used in the study "SARS-CoV-2 escape from cytotoxic T cells during long-term COVID-19". An easy way to look at the code and to check its ouput is to open **patient_S_analysis.html** or **patient_S_analysis.pdf** files.

The code assumes, that the working directory contains following objects:

1. **pat_S_mut.rds** - the list of analysed aminoacid changing mutations (all that viral genome accumulated during the study period);
2. **pat_S_seq.rds** - the list of analysed aminoacid changing mutations (all that viral genome accumulated during the study period);
3.  **russian.fa** - SARS-CoV2 genome, sampled from the patient;
4.  **found_june1.txt** - known epitopes, immunogenic on patient-specific hla alleles from Immune Epitope Database;
5.  **allele_freq.txt** - worldwild frequency of hla alleles analysed.

**net_pan** directory includes examples of netMHCpan and netMHCIIpan outputs, produced by commands in a script.
