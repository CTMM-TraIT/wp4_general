# Work-package 4 (general) #

## Galaxy-Workflows ##

### RNA-Seq ###
This repository contains 12 RNA-Seq analysis workflows to do SNV/SNP detection and expression estimation. Because *some libraries require a specific adapter removal process*, all workflows are duplicated with this functionality. These workflows have the suffix *"Adapter-sequence_contamined"* in their name. An overview of the workflows is given below:

| Type data  | Adapter removal | Measure expression | Detect SNP/SNV | Measure expression & Detect SNP/SNV |
|:-----------|:----------------|:------------------:|:--------------:|:-----------------------------------:|
| Single-end | No              | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_(Single_End).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_SNV_detection_(Single_End).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_and_SNV_detection_(Single_End).ga) |
| Single-end | Yes             | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_(Single_End__Adapter-sequence_contaminated).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_SNV_detection_(Single_End__Adapter-sequence_contaminated).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_and_SNV_detection_(Single_End__Adapter-sequence_contaminated).ga) |
| Paired-end | No              | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_(Paired_End).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_SNV_detection_(Paired_End).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_and_SNV_detection_(Paired_End).ga) |
| Paired-end | Yes             | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_(Paired_End__Adapter-sequence_contaminated).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_SNV_detection_(Paired_End__Adapter-sequence_contaminated).ga) | [LINK](https://github.com/yhoogstrate/wp4_general/tree/master/galaxy-workflows/RNA-Seq/Galaxy-Workflow-RNA-Seq_expression_estimation_and_SNV_detection_(Paired_End__Adapter-sequence_contaminated).ga) |


For each of these workflows, the starting point are the FASTQ files of an experiment; the output for the gene-expression is a tabular format and the output for SNP/SNV detection is VCF.
