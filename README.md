# SARS-CoV-2-assembly-and-intra-host-variation-analysis
SARS-CoV-2 assembly and intra-host variation analysis involves using bioinformatics tools and pipelines to assemble the genome of SARS-CoV-2 and identify differences within the genome between viral samples within a host. This can be useful for studying the evolution and transmission of the virus.
To obtain Illumina and Oxford Nanopore reads for SARS-CoV-2 from the NCBI SRA, you can follow these steps:

- Go to the NCBI SRA website: https://www.ncbi.nlm.nih.gov/sra/

-  In the search bar, type "SARS-CoV-2" and hit enter.

-  You will see a list of SRA accessions that are associated with SARS-CoV-2. You can use the filters on the left-hand side of the page to narrow down your search by selecting the "Platform" filter and choosing "Illumina" or "Oxford Nanopore" as the platform.

-  Once you have selected your desired platform, you can click on the accessions to view the metadata associated with each dataset. The metadata will include information such as the study name, sample type, and sequencing strategy.

- To download the reads, you can use a tool such as SRA Toolkit to retrieve the data in the appropriate format. For Illumina reads, you can use the "fastq-dump" command, and for Oxford Nanopore reads, you can use the "fasterq-dump" command.

For this study I selected five SRA files of Illumina sequncing runs from same samples and different patients to verify this you can look at metadata of NCBI and compare to verify its from different patients you can look at  sample accession number (SAMN) for each SRR file

