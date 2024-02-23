# Email_Spam_Detection

Here are some of the key outcomes of the project:

The Dataset was quiet small totalling around 4600 samples & after preprocessing 14.6% of the datasamples were dropped.

The samples were slightly imbalanced after processing, hence SMOTE Technique was applied on the data to balance the classes, adding 16.7% more samples to the dataset.

Visualising the distribution of data & their relationships, helped us to get some insights on the relationship between the feature-set.

Feature Selection/Eliminination was carried out and appropriate features were shortlisted.

Testing multiple algorithms with fine-tuning hyperparamters gave us some understanding on the model performance for various algorithms on this specific dataset.

The Random Forest Classifier & XG-Boost performed exceptionally well on the current dataset, considering Precision Score as the key-metric.

Yet it wise to also consider simpler model like Logistic Regression as it is more generalisable & is computationally less expensive, but comes at the cost of slight misclassifications.
