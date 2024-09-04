## Module 1: Medical Codexes Analysis

### I performed the steps provided in the Wk 1_helperStarter_code.py file.
#### 1) I used 'df' instead of data. Attached the inpatient file link.

#### 2) I identified the different types of medical codexes in each column by assigning and printing a variable (x) in df.columns. This then populated the different codes.

#### 3) I assigned each data depending on the type of medical codes (icd/drg/hcpcs). It populated different codes for each type. There are fewer hcpcs and drg codes compared to icd codes.

#### 4) Initially, I had issues in checking the missing values for each code columns. I utilized the 'explain the error' message. By clicking it, I discovered that I was not able to define the codes prior to calculating their frequency.
##### ***Troubleshoot: I went back to each code frequency and typed in (icd/drg/hcpcs_frequency) (see #83-#84-#92 in Google Collab). By doing this, I was able to check for any missing data/values, and if there's any, it allowed me to perform the 'placeholder filling' as instructed.

#### 5) I was able to identify the most common ICD-DRG-HCPCS codes in the csv file.
##### - One of the most common DRG code: 951.0 [ I am not quite sure, but this code obviously doesn't fall under ICD. I tried to search the code on Google and it says 'Other Factors influencing health' which is quite general (?) ] 
##### - Two of the most common HCPCS code: (1) 99221 - New or Established Patient, (2) G0444 - Annual Depression Screening
##### - I am not quite sure why it didn't autopopulate under the ICD code (?) (see #94 in Google Collab)

#### 6) I have observed that under the HCPCS code, the most commonly used code is 99221, which is billed for new and established patients. As a former ED nurse in the Bronx, I can confidently say that this is accurate, as there are many patients constantly seeking medical care, whether for obsevation or inpatient services.
#### While the second most commonly used code falls under the 'G0444'. It is the code used for annual screening for depression. It reflects that there are more patients utilizing the necessary help for their mental well-being. 

#### 📌 By using different codes, healthcare providers/clinicians can classify and diagnose the patients' medical conditions appropriately. Health systems and/or organizations can bill patients according to thte procedures performed by the providers. 
#### 📌 For instance, according to the CODEBOOK - Medicare FFS Claims, the lower the number, the more important the diagnosis in the patient treatment/billing (i.e., ICD_DGNS_CD1 is considered the primary diagnosis); For Claim procedure code, ICD_PRCDR_CD1 is considered the primary procedure performed.


##### 📌 *This assignment tested my patience and resilience once again. It was very frustrating at first. It probably took me a day before I figure everything out. Although I am not quite sure if I did everything correctly [ Please let me know ]. Going back to the recorded zoom class, utilizing the 'explain error' messages, and practicing several times under private repositories really helped. For someone who has no prior experience in anything related to coding, I cannot explain how happy I was once I finally solved the error messages. I am more inspired to practice and do better.🙂
