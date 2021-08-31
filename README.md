# SurvivalAnalysis

Available at https://link.springer.com/chapter/10.1007/978-3-030-67051-1_4

**Cite :** Mondal, S., Bhattacharya, N., Das, T., Ghosh, Z., & Khatua, S. (2021). Implication of Statistical Methods on Patient Data: An Approach for Cancer Survivability Prediction. In Intelligent Healthcare (pp. 57-80). Springer, Cham.

***Prerequisites :*** <br/>
The required dependencies for the analysis is R programming ***R version >= 3.6***
and is tested to work under windows as well as Ubuntu.<br/>
***Dataset preparation*** <br/>
breast.txt and ovary.txt is the input files for the analysis.  <br/>
We have preprocessed the original data and initialized some labels according to the category. <br/>

**Label for Breast & Ovarian cancer data:**
**Ethnicity:** <br/>
      white =0
      black or african american =1
      asian=2 <br/>
**Status:**   1 =alive, 2=dead <br/>
**Stage:** <br/>
stage:i=0, stage:ia=0, stage:ib=0
stage:iia=1, stage:iib=1
stage:iiia=2, stage:iiib=2, stage:iiic=2
stage:iv=3

BRCA1 avg FPKM 2.48
low FPKM =1
BRCA1 High=2

BRCA2 avg FPKM 1.03
low FPKM =1
BRCA1 High=2

ATM avg FPKM 2.43
low FPKM =1
BRCA1 High=2

*******************************

***To start a run :*** <br/>
Breast_KM.R & Ovary_KM.R for Kaplan-Meier

breast_cox.R & ovary_Cox.R for Cox PH
 <br/>



***Feedback*** <br/>
Any further information contact at <br/> 
smcse_rs@caluniv.ac.in,  namrata.bhattacharya03@gmail.com, dastroyee1993@gmail.com
