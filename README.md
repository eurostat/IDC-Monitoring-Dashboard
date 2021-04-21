# IDC-Monitoring-Dashboard
20210420 - Version presented to the MES-OG meeting 20210421

The dashboard on International Datasharing Cooperation (TFIDC) is launch using a R program. 

The program top launch the extraction is Report_Launch_WithoutCredential.R.
You have to make sure that you set parameters to access internet if your organisation is using a proxy (reason why it is called without credential).
You have also to set the working directory for the execution. 

The program use a parameter file REF_AEA_Map.csv. This table include mapping of the code list that are not strickly the same between the various organisations. 

The launcher call a rmarkdown procedure stored in IDC_Consistency_Report.rmd. 

The output generated is an HTML file  IDC_Consistency_Report.html. 
The opening of this file is much quicker with FireFox than with Edge (take in our environment more than 1 minute). 

For convenience, a Summary.csv file is also generated in the working directory.
