# Land Use Land Cover

This project generates a high-accuracy Land Use Land Cover (LULC) map using an Ensemble Machine Learning model, designed specifically for urban landscapes. By taking .TIF images as input, the model classifies land into distinct categories, making it ideal for urban planning, environmental monitoring, and resource management applications.
## Usage

Given notebooks can be run in the following order:
1. model_training.ipynb
2. classification.ipynb
3. postclassification_correction.ipynb
4. ensembled.ipynb
5. groundtruth_accuracy.ipynb
\
Alternatively, the driver_output.ipynb class can be used directly which implements the given codes in the said order.

The individually Models, trained via Satellite Data Analytics of Cartosat 3, can be used for experimenatation purposes namely 
1. random_forest_model.pkl
2. svm_model.pkl
3. xgb_model.pkl
4. nn_model.keras