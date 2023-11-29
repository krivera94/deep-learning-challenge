# REPORT ANALYSIS

Data Preprocessing

Target Variable: The target variable for the model was IS_SUCCESSFUL, indicating whether the funding was used effectively by the applicant.

Feature Variables: The features included variables such as APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, and ASK_AMT. These variables provided comprehensive information about each application.

Removed Variables: The variables EIN and NAME were removed from the input data. These columns were identifiers and did not contribute to the predictive model.
Compiling, Training, and Evaluating the Model

Neurons, Layers, and Activation Functions: The final model consisted of two hidden layers with 90 and 20 neurons, respectively. The activation function used for these layers was ReLU (Rectified Linear Unit), chosen for its efficiency and effectiveness in deep learning models. The output layer used the sigmoid activation function, suitable for binary classification.

Target Model Performance: The target performance was set at an accuracy of 75%. The final model achieved an accuracy of approximately 72.85%, falling slightly short of the target but still demonstrating reasonable predictive capability.

Performance Improvement Attempts:

- Adjusted the number of neurons in the hidden layers.
- Experimented with different structures and depths of the neural network.
- Applied data preprocessing techniques, such as binning rare categorical variables and scaling features.

The deep learning model developed for Alphabet Soup's funding application assessment performed reasonably well, achieving an accuracy of about 72.85%. While it did not meet the 75% accuracy target, the model demonstrated potential in predicting the success of funding applications.

Recommendation for a Different Model:

An alternative approach could be to use an ensemble learning method, like a Random Forest classifier. This model could potentially improve performance due to its ability to handle a large number of input features and its robustness to overfitting.

Random Forests are also beneficial for their interpretability, as they can provide insights into which features most significantly impact predictions, aiding in understanding the key drivers behind successful funding applications.

The process of building and optimizing the neural network model showcased the importance of iterative model development, the impact of data preprocessing, and the need for balancing model complexity with performance. Future work could explore more sophisticated feature engineering, alternative models, or hybrid approaches combining neural networks with traditional machine learning techniques.
