# CardioOncology

### Prediction of cardiooncology diseases based on the human plasma proteomics data

**Morteza Mahmoudi**

#### Executive summary
This code is aimed to identify which proteins in the blood proteomics datasets can distinguish among cardio-oncology patients across four categories: i) Patients with cardiac atherosclerosis and non-metastatic prostate cancer; ii) Patients with cardiac atherosclerosis and metastatic prostate cancer; iii) Patients without cardiac atherosclerosis and with non-metastatic prostate cancer; and iv) Patients without cardiac atherosclerosis and with metastatic prostate cancer.

#### Rationale
Early detection of diseases through simple blood tests is a crucial and accessible step toward treating lethal conditions before clinical symptoms even appear. Analyzing blood-based proteomics data offers a promising approach to achieve this goal. By detecting serious illnesses such as cardiovascular diseases and cancers early—conditions that can accelerate disease progression when co-occurring—millions of lives can be saved through timely intervention.

#### Research Question
We want to use classification techniques on the proteomics outcomes of collected blood samples from i) Patients with cardiac atherosclerosis and non-metastatic prostate cancer; ii) Patients with cardiac atherosclerosis and metastatic prostate cancer; iii) Patients without cardiac atherosclerosis and with non-metastatic prostate cancer; and iv) Patients without cardiac atherosclerosis and with metastatic prostate cancer; and see whether there are proteomics features that can be used for identification and discrimination of each diseases.

#### Data Sources
Blood-based proteomics data by the use of nanomedicine protein corona; the data set is uploaded in the project file: "MM-Data_BUP_35Samples.xlsx"

#### Methodology
We use LASSO (Least Absolute Shrinkage and Selection Operator) to see the classification accuracy of each patient group.

#### Results
The confusion matrix analysis of the outcomes showed that the LASSO classification applied to the proteomics data achieved an 80% accuracy in identifying and distinguishing patients with cardiac atherosclerosis from those with metastatic prostate cancer.
#### Next steps
Identifying important proteins that can be used in improving the classification accuracy and therefore can serve as potential biomarkers for blood-based disease detection.

#### Outline of project

the code is available in this notebook: LASSO.ipynb

##### Contact and Further Information
For proteomics database and other information, please contact Morteza Mahmoudi at mahmou22@msu.edu 
