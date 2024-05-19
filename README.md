# Rain Prediction Analysis

## Description
This project explores advanced data mining techniques to analyze and predict rainfall patterns using a decade's worth of weather data from Australia. The analysis is conducted through a comprehensive Jupyter notebook which utilizes Python and several of its powerful libraries including Pandas for data manipulation, NumPy for numerical data operations, Scikit-Learn for modeling, and Matplotlib for data visualization.

The core of the project is focused on employing various predictive modeling techniques to forecast weather conditions, particularly rain. The models explored include K-Nearest Neighbors (KNN), Decision Trees, and Support Vector Machines (SVM), each evaluated on their accuracy, precision, recall, and F1 scores. To tackle the challenges of class imbalance in the dataset, strategies such as Random Under-sampling and SMOTE (Synthetic Minority Over-sampling Technique) are applied, creating balanced datasets that improve the predictive performance of the classifiers.

### Key Processes
1. **Data Preprocessing**: Initial data cleaning and preprocessing to structure the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Visual and statistical analysis to understand underlying patterns and relationships.
3. **Feature Engineering**: Enhancing the dataset with new, informative features and selecting the most relevant features for the models.
4. **Model Training and Evaluation**:
   - Implementing KNN, Decision Trees, and SVM.
   - Assessing models using metrics such as accuracy, precision, recall, and F1 score.
   - Applying cross-validation techniques to ensure the models' generalizability.
5. **Class Imbalance Management**: Utilizing Random Under-sampling and SMOTE to address class imbalance in training data.

### Results
The project not only showcases the effectiveness of different data balancing techniques but also compares the impact of these techniques on the predictive accuracy of the models. Through rigorous testing and validation, insightful conclusions are drawn about the suitability of each model for rain prediction based on the adjusted datasets.

### Conclusion
This analysis offers a deep dive into weather prediction, providing valuable insights into data-driven decision-making in meteorology. The techniques and findings presented could be particularly useful for academic researchers and professionals in data science and meteorology looking to enhance predictive accuracy in similar contexts.


## Technologies
- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib

## Usage
Open the `DataMining_Project2RainDataset.ipynb` notebook and run the cells to see the analysis.

## Dataset
The dataset used in this project is based on 10 years of weather history from Australia, available on Kaggle. This dataset contains historical weather data necessary for analyzing and predicting rainfall patterns. 

**Source**: The dataset can be accessed on [Kaggle](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package). Note that the dataset used in this project has modifications in the column names to improve clarity and usability in analysis.



