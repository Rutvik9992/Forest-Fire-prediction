# Forest-Fire-prediction

This project explored the use of decision tree, random forest, Knn, and Naive Bayes algorithms for predicting forest fires in the given years. Our analysis of the dataset revealed that certain features such as temperature, humidity, and wind speed had a significant impact on the occurrence of forest fires which is represented by month in our dataset.  

I built four models using these algorithms and evaluated their performance. Results showed that the random forest and Naive Bayes models had the highest prediction accuracy, achieving 99.45% and 100% respectively. The decision tree model achieved a prediction accuracy of 78.52%, while the Knn model had a relatively low accuracy of 23%.  

The reason of low accuracy of Knn model is the data is not well-suited for the KNN algorithm and not due to hyperparameters of the model are not well-tuned.However, generally, a higher accuracy score on the testing data and a good balance between precision and recall for each class would indicate a successful model.  

For Random forest  the training score and testing score show that the model has achieved a high accuracy on both the training set (100%) and the test set (99.44%), indicating that the model is not overfitting.
It has been found that the scatter plot can be a useful tool for evaluating the performance of a machine learning model and identifying areas for improvement as it help us visually understand how well the model is predicting the target values.  

Based on our analysis, we recommend the use of the random forest or Naive Bayes models for predicting forest fires, as they demonstrated the highest accuracy. However, it is important to note that the performance of these models may vary depending on the specific dataset and environmental conditions.  

In conclusion, this project provides valuable insights into the use of machine learning algorithms for predicting forest fires, and highlights the importance of selecting the appropriate algorithm based on the specific problem at hand. We hope that this report can inform future research and assist in the development of effective forest management strategies.
