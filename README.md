# Data Glacier Week 9: Persistency of a Drug (continued)

**Business Problem**

Medication persistence refers to a patient’s continued action of taking medications for the duration instructed by the prescriber. Therefore, persistency of a drug is a critical factor which contributes to industry profits as well as patient outcomes. Using data in real cases, a machine learning model can learn relationships between target variables (persistence) and dependent variables, such as patient related variables, prescriber attributes, and indicators of disease severity (e.g.: DEXA scans, t-scores of the bone, and history of bone fractures) at the beginning and during the therapy. Eventually, the model will be able to predict whether the patient will be persistent in medication therapy, given the values of dependent variables.

**Project Description**

A model will be established and deployed to automate identifying persistency of a certain pharmaceutical product. Records of 3,424 patients who take the medication will be used for analysis, and correlation between medication persistency and other factors such as patient demographics, provider attributes, clinical factors, and disease factors will be investigated. Finally, an optimal model to predict persistency based on above features will be selected and developed.

**Weekly Progress**

Pre-processing was performed. Features with missing values exceeding 40% were deleted, and other missing values were imputed using different strategies (i.e. median, mode, and establishing a separate 'unknown' category). Extreme values were replaced using winsorization. Skews in the features were further reduced using square root transformation.
