Erythroblast Classification 
Project Overview
This project focuses on the classification and segmentation of erythroblasts in peripheral blood cell images. We utilize both traditional machine learning models and deep learning approaches to achieve high accuracy in identifying and classifying erythroblasts.


Erythroblasts are immature red blood cell precursors typically confined to the bone marrow. This project aims to develop robust models for the classification and segmentation of erythroblasts in blood smears, aiding in better diagnostic tools for hematological conditions.

Dataset
The dataset used for this study was sourced from the Mendeley repository titled "A dataset for microscopic peripheral blood cell (PBC) images for the development of automatic recognition systems". The dataset comprises 17,092 JPEG images of typical peripheral blood cells, organized into eight categories: neutrophils, eosinophils, basophils, lymphocytes, monocytes, immature granulocytes, erythroblasts, and platelets.

Citing the Dataset:
If you use this dataset in your research, please cite the original authors as follows:
Acevedo, Andrea; Merino, Anna; Alférez, Santiago; Molina, Ángel; Boldú, Laura; Rodellar, José (2020), “A dataset for microscopic peripheral blood cell images for development of automatic recognition systems”, Mendeley Data, V1, doi: 10.17632/snkd93bnjr.1

Aviavility:
Codes and weighs are present in the repo



Model Training
We employed a two-step process of feature extraction followed by classifier implementation. A range of models including traditional classifiers (KNN, SVM, RandomForest, XGBoost) and a deep learning model (ResNet-50) were used. Hyperparameters were optimized using grid search to maximize accuracy.





Contributors
Buddhadev Goswami, Adhitya B. Somaraj, Dr. Prantar Chakrabarti, Prof Ravindra Gudi and Prof Niramal Punjabi

Acknowledgments
We thank the authors of the dataset and the various tools and libraries that made this project possible.
