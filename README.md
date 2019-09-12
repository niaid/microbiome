# microbiome
Microbiome Data Analysis and Nephele Demo

### Nephele Web Server
<https://nephele.niaid.nih.gov>

### Resources for RML session on Microbiome Data Analysis ###
1. Slides - [download pdf of slides here](https://proj-bip-prod-publicread.s3.amazonaws.com/training/Microbiome+and+Nephele/Microbiome_RML.pdf)

2. Test input files: for 16S pipelines
    Download files from "How to submit a job" - <https://nephele.niaid.nih.gov/user_guide/>

#### Steps to run Demo.  For more details see: https://nephele.niaid.nih.gov/user_guide/
1. Request account in nephele server
2. Select Amplicon Data, 16S
3. Sign into Nephele with the email you registered with, then select **Paired End Fastq**
4. Select **"Upload files from publicly accessible URL(s)", Upload via FTP** . Provide the following path **ftp://helix.nih.gov/pub/mqbcbb/nepheleFQ/**  Please know that this folder will be available only temporarily from this FTP location.  
5. Download file from **<ftp://helix.nih.gov/pub/mqbcbb/N2_16S_mapping.xlsx>** then upload to Nephele as the mapping file. 
6. Follow along to submit a job.  THere is no need to change default parameters for this dataset.   
7. Expect an email with words "nephele pipeline success"

#### View results

[Download DADA2 example output here](https://nephele-prod-testdata.s3.amazonaws.com/dada_example_output.zip)

[Visit this page after receiving email with note that job has completed](https://nephele.niaid.nih.gov/results/f04730b61840)
