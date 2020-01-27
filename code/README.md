Code Folder contains the following files:

*Data Preparation*:
* **Data Exploration.ipynb**: contains all the data visualization and exploration in the report. 
* **Create_Data.ipynb**: Read all the available json files and save them as csv files.
* **Small_dataset_preparation.ipynb**: Prepare a small dataset to accommodate the baseline models. We have trained all the models using this small dataset.
* **Train_Test_Split.ipynb**: Split (large) dataset into train and test set.
* **Data_segmentation_user&business.ipynb**: Segment test set into different levels of users and businesses.

*Baseline model*:

* **Baseline_knn_nmf_bias.ipynb**: contains all three baseline models(knn,nmf,bias) and their results for small dataset. 

*NCF model*:

* **NCF_Small_Dataset.ipynb**: contains NCF model and its results for small dataset.
* **Neural_Matrix_Factorization_Relu.ipynb**: contains NCF model with ReLU activation using large dataset.
* **Neural_Matrix_Factorization_Leaky_Relu.ipynb**: contains NCF model with Leaky ReLU activation using large dataset.

*FM model*:
* **FM_Dataset_preparation.ipynb**: Prepare train and test set for FM model.
* **Factorization_Machine.ipynb**: Train and test FM model.

*Wide and Deep model*:
* **W&D_Dataset_preparation_larger.ipynb**: Prepare train and test set for W&D model.
* **W&D_model_large.ipynb**: Train W&D model on the large dataset.
* **WD_model_small.ipynb**: Train W&D model on the small dataset.
