# IGF-Network-Expression-in-the-Brown-Anole
This repository holds all supplemental files for "Gene expression of the IGF hormones and IGF binding proteins across time and tissues in a model reptile".

## Publication Abstract: 
**Insert abstract here**

### Quick Key to File Directory: Detailed Descriptions of file use can be found below.
File Type                            |
------------------------------------ | -----------------------------------------------------
Protocols and interactive worksheets | [Molecular Protocol](Brown.Anole.qPCR.Protocol.pdf) 
                                     | [Appendix A: Primer Design](Appendix_A.Primer_Design.txt)
                                     | [Appendix B: Standard Preparation](Appendix_B.Standard.Prep.Worksheet.xlsx)
                                     | [Appendix C: qPCR Calculations](Appendix_C.qPCR.Calculations.xlsx)
Raw Data                             | [Plate 1](qPCR_Plate_10_24.zip)
                                     | [Plate 2](qPCR_Plate_2.zip)
Final Data                           | [IGFs and EEF2 Final](combined.data.final.csv)
                                     | [IGF1 Undiluted](undiluted.samples.csv)
                                     | [Presence Absence Heatmap](heatmap.data2.csv)
Statistical Code                     | [Code](Publication_Code.Rmd)
                                     | [Code output](Publication_Code.html)
Sample Classification                | [Gel images](Presence.Absence.Gel.Images.pptx)


### Molecular Protocols 
The protocol for molecular processes used in this experiment, RNA extraction through qPCR analysis, can be found [here](Brown.Anole.qPCR.Protocol.pdf). 

Within the molecular protocol, a series of appendices are referenced. [Appendix A](Appendix_A.Primer_Design.txt) contains the gene sequences for IGF1, IGF2, and EEF2 that were used for primer and probe design. [Appendix B](Appendix_B.Standard.Prep.Worksheet.xlsx) contains the excels spreadsheet used to prepare the absolute standard curve. If downloaded, this sheet is easily amendable for use. [Appendix C](Appendix_C.qPCR.Calculations.xlsx) contains an amendable spreadsheet for qPCR mastermix preparation and plate setup. 

### qPCR Amplification Data Output 
Raw data output files for two plates of qPCR amplification ([Plate 1](qPCR_Plate_10_24.zip) and [Plate 2](qPCR_Plate_2.zip)) were exported from the Bio-Rad CFX Maestro qPCR Analysis Program. Triplicates were examined for consistancy, and any triplicate more than 0.25 cycles from the mean were discluded from the analysis. If more than one sample from a triplication was outside of the cutoff, the sample was dropped from analysis. The [final data set](combined.data.final.csv) contains only samples used in statistical analysis.
The [file](undiluted.samples.csv) containing undiluted amplifications of IGF1 was used in order to verify negative IGF1 results seen at a cDNA concentration of 1:100. 

### Statistical Analysis 
The statistical analyses were performed in R (version 3.5.1) using [code](Publication_Code.Rmd) in an R Markdown format. [Code output](Publication_Code.html) displays all statistical models, results, and figures produced. 

### Presence-Absence Visualization
Following conventional PCR, gel electrophoresis was used to visualize samples as being present, or absent. [Gel images](Presence.Absence.Gel.Images.pptx) were used to classify samples. The file used to create the expression [heatmap](heatmap.data2.csv) contains the average percentage of indivdiuals that expressed each gene (IGF1, IGF2, and IGFBPs) across tissues. 
