# BIMM143_Python_Project2
*This is the first draft of Project2.

Scientific question: Does the reduction of protein tyrosine phosphatase receptor type S (PTPRS) expression contribute to breast cancer tumorigenesis? If yes, is EGFR mediated EMT (epithelial-mesenchymal transition) pathway involved, or what other pathways are involved? 

Scientific Hypothesis: If PTPRS is shown as a metastatic suppressor in hepatocellular carcinoma, then it may also exhibit a similar regulatory role in breast ductal carcinoma and the loss of PTPRS may also contribute to the breast cancer metastasis by regulating similar mediators like EGFR.

3 files are needed to successfully run the code:

1) The jupytor notebook ([Project2C](https://github.com/ChulingZhuang/BIMM143_Python_Project2/blob/main/Project2C.ipynb)).
2) The csv file containing TPM count results of RNA seq ([30_breast_cancer_rna_TPM.csv](https://github.com/ChulingZhuang/BIMM143_Python_Project2/blob/main/30_breast_cancer_rna_TPM.csv
)).
3) The csv file containing experimental design of RNA seq ([30_breast_cancer_rna_experiment_design.csv](https://github.com/ChulingZhuang/BIMM143_Python_Project2/blob/main/30_breast_cancer_rna_experiment_design.csv))

Information about the source of csv files:
    The RNA-seq results were obtained from EBI Expression Atlas database. I found this experiment by clicking on the "browse experiment" tabe in the mainpage, and search "RNAseq breast" in the "Title" query. The experiment "Variation in RNA expression in a panel of 30 breast cancer cell lines" is the first result of the query and it performed RNA-seq on 30 breast cancer cell lines of Homo Sapiens. To download these file, I first clicked "Downloads" tab in the page of this experiment, and clicked "Expression values across all genes (TPM)" for the file containing TPM count results, and "Expression Design (tsv)" containing information about experimental details. 
    
    *Note: The original files are tsv files, and I converted them into csv files for convenience.

    
Enjoy!
