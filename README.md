# shellscripts
Obtaining SRRIDs in SRA accession table from GSMID 

grep ^SRR SRA_Accessions.tab | grep GSM1379814

Shell scripts for data handling
Another simple way is to check the SRR ID of your sample in SRA Run Browser: http://trace.ncbi.nlm.nih.gov/Traces/sra/
"Browse" -> "Run Browser" -> then input your ID
The LAYOUT result will tell you. Also, the 'Reads' label shows 1 read for single end, and 2 reads for paired end.

Syncing data from local to remote

rsync -avzh --progress Methylation_epic/user@xyz.com:/work/users/abc/SINGLECELL/Raw-data/
 SYncing data from REMOTE to REMOTE
 
 rsync -vuar --progress BwFormat.zip user@uio.no:/storage/scratch/ftp/Folder1/folder1_1
 
shell scripts: 
 BAMtoBW-treatment : bamCoverage command of deeptools for converting BAM files to BW 
 Changing Timestamps : It changes time stamps of the files.  
 REMOVING-DUPLICATE ID : removing duplicate id´s 
 Single_End_BAMTOBW : bamCoverage command  of deeptools for converting BAM files to BW
 bamToBW : bamCoverage command  of deeptools for converting BAM files to BW
 bwtobedconversion_liftover -  bedops tools bigwid to bed and wig to bedformat 
