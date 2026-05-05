# Medicine Recommendation System using Machine Learning

## Project Overview
This project focuses on recommending appropriate medicines based on user symptoms using Machine Learning techniques. The system analyzes input symptoms and predicts the most suitable medicine or treatment category.

## Objective
- To build a machine learning model that recommends medicines based on symptoms  
- To compare multiple algorithms and evaluate their performance  
- To assist in preliminary healthcare guidance  

## Dataset
The dataset contains:
- Symptoms (Fever, Cough, Headache, etc.)
- Disease
- Recommended Medicine

Example features:
- fever
- cough
- fatigue
- headache
- nausea

Target:
- Medicine / Drug name or Disease

## Algorithms Used
1. Logistic Regression  
2. Decision Tree Classifier  
3. Random Forest Classifier  
4. (Optional) Naive Bayes  

## Data Preprocessing
- Handling missing values  
- Encoding categorical variables  
- Feature selection  
- Splitting dataset into training and testing sets  

## Evaluation Metrics
- Accuracy Score  
- Precision  
- Recall  
- F1 Score  
- Confusion Matrix  

## Results
| Model               | Accuracy |
|--------------------|---------|
| Logistic Regression| ~0.80   |
| Decision Tree      | ~0.85   |
| Random Forest      | ~0.90   |

Random Forest achieved the highest accuracy and better generalization.

## Visualizations
- Model accuracy comparison graph  
- Confusion matrix  
- Feature importance graph  

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

## How to Run
1. Upload dataset file (e.g., `medicine_dataset.csv`) in Google Colab  
2. Run the Python code  
3. Input symptoms to get prediction  

## Conclusion
Machine learning models can effectively recommend medicines based on symptoms. Random Forest provides the best performance in this project.

## Future Improvements
- Use real medical datasets  
- Add severity-based recommendations  
- Deploy as a web or mobile application  
- Integrate with chatbot  

## Disclaimer
This project is for educational purposes only and should not be used as a substitute for professional medical advice.
