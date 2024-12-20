# Challenge: Pancreatic Cancer Analysis

## Overview
This is a coding challenge designed to test your ability to analyze data from a real-world pancreatic cancer dataset based on the real-world domain we deal with at Radical Health. The dataset contains longitudinal clinical, genomic, and treatment data for all cancer patients. 

You may do this at your own pace at home. The time you should spend on this task is 3 hours. The scope of the challenge is designed to take much more than 3 hours and it is normal to not have finished your task by the end of the time limit. We will schedule a call with Gediminas where we explore up to where you stopped and your thought processes!

There are two first-line chemotherapy treatment options for metastatic pancreatic cancer. Clinicians believe their efficacy is equivalent, but we believe there is an optimal treatment for an individual (note: the dataset size might not be sufficient to show this). Your overarching task is to develop model(s) to compare differential overall survival or other treatment effectiveness metrics for patients on the two main chemotherapy treatments for stage IV pancreatic cancer. They are (1) Folfirinox and (2) Gemcitabine + Nab-Paclitaxel. Also, if possible, identify the most important features that would predict OS or treatment effectiveness 

## Instructions
Your specific instructions are as follows:
1. Download the dataset from [here](https://cbioportal-datahub.s3.amazonaws.com/msk_chord_2024.tar.gz). This dataset is ~360Mb was published alongside this [paper](https://www.nature.com/articles/s41586-024-08167-5) from MSK. We do not recommend you spend time looking at the paper itself as it will not be of much help for the task.


> Hints: demographic data can be found in `data_clinical_patient.txt` and each patient is identified with an ID in *PATIENT_ID* column.
> Genetic mutation data can be found in `data_mutations.txt` - a patient can then be identified with through *Tumor_Sample_Barcode* column.
> There is a lot of hidden data in files with the format `data_timeline_*.txt` - for instance, `data_timeline_treatment.csv` lists all cancer treatments given to patients.

2. This dataset contains 24,950 cancer patients, of which only 3,109 are pancreatic cancer patients. Only ~1330 patients are Stage IV pancreatic cancer patients and should be included in your main analysis. You may include any other patients in your side-analysis if you choose.
3. Write scripts to achieve your overarching task. (You may use any programming language & any open source libraries you want.)
4. Document all of your work, including exploratory data analyses and thought processes.
5. Delete any unneeded files to avoid storage issues on your local machine.
6. When you're finished, send your code to Simone (simone@radicalhealth.ai) and Gediminas (gediminas@radicalhealth.ai) and schedule a call!

Beyond anything specifically mentioned, feel free to make any assumptions and justify your assumptions to achieve your tasks. 
Note that while we expect submitted code to run, we don't expect it to be ready to deploy! Leaving comments about things you would like to do given more time is totally fine.
