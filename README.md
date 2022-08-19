# Normal adjacent tissues in HCC project
Study of transcriptomics data of normal liver tissues adjacent to HCC


## Pipeline process
1A)   bamToCTSS_v0.6.pl - Conversion of BAM files to CTSS files<br/>
1B)   bamToCTSS_wrapper.sh - wrapper to run multiple BAM files in parallel<br/>
2A)   ctssToBigWig.sh - Conversion of CTSS files to BigWig files using ENCODE tool: bedGraphToBigWig<br/>
2B)   loop_CTSS_to_BigWig_CAGEfightR<br/>
3)		quantifyCTSS.Rmd - Quantify CTSSs<br/>
4)		
