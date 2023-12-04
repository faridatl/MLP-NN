## Multi-Layer Perceptron Neural Network Classifier (MLP NN):

The Accelerometer Dataset from the UCI machine learning repository is a study of classification for weight configuration. There are four features being used to classify the three classes; Normal, Perpendicular and Opposite configuration. To assess the dataset, a 5-Fold cross-validation of an MLP NN classifier for multi-class classification was employed. The model utilized three hidden layers, with 200, 150, and 100 neurons in each layer, and was trained for a maximum of 100 iterations. The runtime for the complete process ranged from an hour and a half to two hours. This specific configuration of hidden layers and neurons yielded optimal classification performance. Various performance metrics, including the confusion matrix, sensitivity, specificity, overall model accuracy, F1-score, and the ROC & AUC Curve, were calculated as part of the evaluation process.

**Important Note:** Number of neurons for each hidden layer used was increased after each run until highest accuracy score was reached. Originally started out The number of neurons for each hidden layer was increased after each run until the highest accuracy score was reached. The model originally started with an accuracy score of 50% when the number of neurons in each hidden layer was 10, 5, and 3. As the number of neurons for each hidden layer increased, the overall model accuracy also began to increase.with an accuracy score of 50% when number of neurons in each hidden layer was 10,5,3. As number of neurons for each hidden layer was increased, overall model accuracy began to increase as well. 

## 🛠️ Technologies Used:

Python: Leveraging the power of Pandas, NumPy, and Scikit-Learn.

Jupyter Notebooks: Transparent and interactive documentation of the entire workflow.

## 📈 Results:

* The study assessed the effectiveness of an MLP NN classifier on the UCI machine learning accelerometer dataset. Noteworthy sensitivity scores were observed, reaching 63% for Class 1 (Normal), 70% for Class 2 (Perpendicular), and an impressive 87% for Class 3 (Opposite). Specificity scores were also notable, ranging from 86.7% to 92%. Cross-validation accuracy consistently hovered around 73%, with F1 scores indicating balanced precision and recall. Precision scores for classes 1, 2, and 3 were 70%, 65%, and 85%, respectively. Overall, the model demonstrated a 73% accuracy rate, showcasing its proficiency in predicting whether a configuration was Normal, Perpendicular or Opposite.

* The sensitivity scores (63% for Class 1, 70% for Class 2, and 87% for Class 3) indicate the model's effectiveness in correctly identifying instances of different classes.

* The specificity scores (86.7% for Class 1, 81.2% for Class 2, and 92% for Class 3) suggest that the model performs well in recognizing instances that do not belong to each respective class.

* The precision scores (70% for Class 1, 65% for Class 2, and 85% for Class 3) reflect the model's ability to avoid false positives, providing an indication of the reliability of its positive predictions.

* The ROC and AUC analysis for the MLP NN classifier reveals distinct performance patterns among different classes. Class 3 (Opposite) stands out with a notable AUC of 0.97, indicating exceptional discriminatory power for this class. Class 2 (Perpendicular) exhibits a respectable AUC of 0.86, suggesting a good ability to distinguish between positive and negative instances. Similarly, Class 1 (Normal) also demonstrates an AUC of 0.86, reflecting effective discrimination despite being on par with Class 2. Overall, these findings from the ROC and AUC graph underscore the classifier's discriminative strength, particularly highlighting the superior performance in distinguishing instances belonging to Class 3.

* Collectively, these metrics indicate that the MLP NN classifier is performing well across various aspects of classification on the accelerometer dataset. It showcases proficiency in accurately detecting instances from various classes (sensitivity), minimizing false positive predictions (precision), and striking a balanced equilibrium between precision and sensitivity (F1 score). The high specificity scores further underscore the model's accuracy in discerning instances that do not pertain to each specific class. Together, these observations indicate the model's potential and dependability in effectively handling the accelerometer dataset.


## 🔗 How to Use:

Each project/code along with their dataset has been uploaded for your review or observation. Please feel free to reach out if you have questions, suggestions, or if you're interested in collaboration!

## 🌐 Connect with Me:

LinkedIn: (https://www.linkedin.com/in/faridatlawal/)

##### I'm continuously learning and expanding my skill set. Join me on this exciting journey through the world of machine learning! 🤖✨
