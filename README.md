# covid19_and_stroke

We share here R-code and data to replicate the Mendelian randomization (MR) analysis for our study on "Leveraging genetic data to elucidate the relationship between Covid-19 and ischemic stroke".  Our motivation is to investigate whether genetic predisposition to critical Covid-19 is also associated with risk of ischaemic stroke.

Please see the following two analysis files:
1. mr-covid19-stroke.Rmd
which uses 31 genetic variants associated with critical Covid-19 as instrumental variables. this dataset is provided in SupplementaryTable2.csv. this script describes the main analysis using inverse-variance weighted MR, model diagnostics and sensitivity analysis based on pleiotropy robust MR approaches and using only genome-wide significant genetic variants as instrumental variables

2. mr-additional-analysis.Rmd
which uses additional data provided in the object additional.data.Rdata including pleiotropic pathways (in particular obesity, inflammation and smoking), other definitions of Covid-19 and bidirectional analysis (considering ischemic stroke as exposure)
