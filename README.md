# Using a Machine Learning Strategy to Predict Cancer Patient Outcome based on Clinical and Molecular Biomarkers

## Project Overview
  The decision of which treatment to pursue in head and neck cancer is often made based upon anatomic criteria only, certainly leading to inappropriate therapy in some patients.  As can be seen by complication and quality of life studies in head and neck cancer patients, some patients could be considered over treated, developing significant morbidity which may not be necessary, while others may be considered under treated, continuing with persistent disease. While there is an anatomic component to variation in tumour behavior, gross anatomy alone is not the only factor. 
  
  In order to provide effective treatment strategies, we will need to be able to predict, with high specificity and sensitivity, the tumour potential for metastasis and patient response to therapy. Development of such a prediction tool will advance the field of personalized medicine.
  
  With this in mind, I would like to use a machine learning strategy with gene expression and DNA methylation data to predict two critical parameters that would be useful in guiding treatment. The variables to predict would be:
  
1) presence of lymph node metastasis at diagnosis, 
2) 3-year overall patient survival

The dataset includes 530 head and neck cancer patients from the Cancer Genome Atlas (TCGA) (https://www.cbioportal.org/study/summary?id=hnsc_tcga ). For each patient, data is available on stage of disease, including lymph node metastasis (N stage), as well as overall patient survival. There are 93 additional clinical variables, such as the primary site of the tumour. For molecular data, there are a total of 482,421 DNA methylation measurements and measurements of expression for 20,531 genes.


