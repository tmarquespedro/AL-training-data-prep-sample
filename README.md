# AL-training-data-prep-sample
Sample of code from a project utilising active learning for the prediction of mitochondrial toxicity.

**AL00_datasets**

- All datasets required for this excerpt of code

**AL01_Dataset_Prep**

- Preprocessing of datasets (i.e. standardisation, joining of dataframes and generation of phys-chem descriptors)

**AL02_initial_training_RF_model**

- Train-test split of total training data (80:20). Remaining 80 further split into different subset sizes from 10-100% (increasing sizes of 10%) to test how the size of training data may affect active learning predictions (not shown). Splits were randomly selected 10 times for each subset size. Each training subset was tested against holdout test data, compared based on various performance metrics. Each of these training subsets was used to train various active learning models to assess the impact of training data size on prediction performance (not shown).

**AL03_1_diff_training_subset_size_performance_individual**

- Performance metrics for all splits of each training subset

**AL03_2_diff_training_subset_size_performance_avg**

- Averaged performance metrics for each training subset
