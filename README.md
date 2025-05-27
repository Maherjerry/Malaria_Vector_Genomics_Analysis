# Bioinformatics Pipeline for Malaria Vector Genomics Surveillance
This notebook demonstrates a complete variant calling pipeline specifically designed for genomic surveillance of malaria vectors and focuses on variant detection in key genomic regions associated with insecticide resistance and other phenotypes relevant to malaria transmission and control. This a pipeline teaching the basics of bioinformatics and variant calling implemented in a cloud-based environment using Google Colab.

**Overview of the Pipeline**
1. Setting up the environment and data
2. Quality Control of raw sequencing data - Critical for accurate variant detection in complex mosquito genomes
3. Trimming and filtering reads - Removing adapters and low-quality sequences to improve mapping to Anopheles reference genomes
4. Alignment to a reference genome - Mapping reads to the appropriate Anopheles reference genome
5. Processing and quality control of alignments - Ensuring high-quality alignments for reliable variant detection
6. Variant calling - Identifying SNPs and indels, particularly in genes associated with insecticide resistance
7. Variant filtering and analysis - Focusing on key variants related to vector control and transmission dynamics
