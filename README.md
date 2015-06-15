# Wild_Barley_Diversity-2013
These scripts were used for read mapping for samples located in ~/Project/WBDC.

The scripts are located in ~/Jobs/Wild_Barley_Diversity.

The WBDC_103_2013-11-20.job script takes fastq.gz files and outputs .sam files.

Process_SAM.job takes .sam files and outputs Finished.bam files.

GATK_RTC.job takes .bam files and outputs Realigned.bam files.

GATK_HaplotypeCaller.job takes .bam files and creates RawVCF_Long_Calhoun.vcf files.

Merge_BAMs.job merges all the .bam files.
