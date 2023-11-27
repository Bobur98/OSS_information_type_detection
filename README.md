
This artifact contains the data and code used in the paper "Analysis and Detection of Information Types in Open Source Software Issue Discussions."

It comprises three main folders: data, code, and results. The components are as follows:

1. **data**: This folder contains all the data used in the experiments.

   - **new data**: Contains all the new data files, both separately and in a combined set.
   - **old data**: Contains all data collected by Arya2019.
   - **combined_dataset**: A combination of old and new data.
   - **combined_data_oversampled**: Data after applying the random oversampling technique to the combined dataset.
   - **old_data_oversampled**: Old data after applying the random oversampling technique.

2. **code**: This folder contains the logistic regression code used to detect information types.


   - **ClassBalancing.ipynb**: Contains the random oversampling technique to balance the minority classes.
   - **5fold_LTC_LTS_hyperparameter_experiment.ipynb**: Contains the code to detect the information types of the given data. It was used to experiment the combination of hyperparameter values.
   - **5fold_LTC_LTS.ipynb**: This file contains logistic regression code without using the smote technique by Arya2019.
   - **5fold_LTC_LTS_smote.ipynb**: This file contains logistic regression code using the smote technique by Arya2019.


3. **results**: Contains all the experiments that have been conducted, along with the hyperparameters and results of all the datasets used.
    - **hyperparameter_results**: Contains results of the different combinations of hyperparameters.
