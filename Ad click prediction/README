**This work was done to effectively forecast, based on a user's profile and behaviour, whether or not the user will click on an advertisement. The actions were intended to:**

    1. Ensure Data Completeness: We made sure the dataset was full by managing missing values, which prevented any biases or errors that missing data would have introduced. 
    2. Focus on Relevant Features: We enhanced the model's performance and interpretability by eliminating unnecessary columns (such as {id} and {full_name}) and concentrating solely on the features that help forecast the target variable ({click}). 
    3. Standardise the Data: To guarantee that the data was consistent and in the proper format for model training, categorical variables were encoded and numerical features were normalised. This makes patterns easier for models to comprehend without being impacted by variations in data or scales.
    4. Leverage Automation for Efficiency: By using PyCaret's AutoML framework, which handles preprocessing chores like encoding, normalisation, and train-test splitting automatically, we were able to compare numerous machine learning models fast and effectively. This guarantees that we choose the model that performs the best while also saving time.
    5. Model Finalisation and Evaluation: We ensured the best model has good generalisation to new data by evaluating it and learning more about its performance across a range of criteria.
    6. Reusability: By saving the model, further deployments or forecasts can be made without requiring it to be retrained, which increases the workflow's usefulness and effectiveness for subsequent activities.

**Notes:-**

        1. AutoML: PyCaret automates many processes like model selection, scaling, and encoding. Most machine learning-specific preprocessing is managed by the setup() method.
        2. Model Selection: The compare_models() function in PyCaret helps identify the best-performing algorithm with default settings for your dataset. For better results, you can explore ensemble methods or further fine-tune the optimal model.
        3. Evaluation: Use evaluate_model() to obtain detailed performance metrics and visualizations, helping you understand the model's effectiveness.
        4. Deployment: Models can be saved for deployment, enabling future predictions without the need for retraining, making production deployment easier.
        
Using PyCaret, this workflow offers a strong foundation for forecasting ad clicks through an AutoML approach. Remember to evaluate the results, and if necessary, adjust the preprocessing steps or manually fine-tune the models to suit your specific use case.
