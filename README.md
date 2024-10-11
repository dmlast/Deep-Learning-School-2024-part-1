# Deep-Learning-School-2024-part-1

In this repository I keep my homework, which I do as part of the first part of the MIPT Deep Learning School project. First part of the course is focused on the basics of neural networks, convolutional neural networks and computer vision.

* **Homework 1** was provided to feature engineering and consisted of solving classification problems about which of the Game of Thrones characters would survive. Various methods of feature engineering were implemented, but classifiers were developed: `Logistic Regression`, `AdaBoostClassifier`, `RandomForestClassifier`, `Gaussian Process Classifier`, `GaussianNB`, `KNeighborsClassifier`, `SVC`. A gridsearch was conducted. After that, the boosting of the classifier (`gradient`, `xgm`, `lgbm`, `catboost`) was developed. Then, unimportant features were noted to combat retraining. In this assignment, **I was able to get a quality metric for the maximum score (accuracy = 0.85)**.
  
* **Homework 2** focused on employing `linear models` for `image classification` tasks.  Initially, baseline models were constructed using linear classifiers, including `logistic regression` and `support vector machines` (SVMs), and their performance was assessed using metrics such as `accuracy`, `precision`, `recall`, and `F1-score`. Additionally, the assignment explored `regularization techniques` like `L1 and L2 penalties` to mitigate overfitting and enhance model generalization. The assignment also introduced advanced methodologies such as `cross-validation` to ensure robust model evaluation. This approach provided insights into model stability and facilitated hyperparameter tuning to achieve optimal performance.

  
* **Homework 3** focused on exploring advanced metrics and boosting techniques in machine learning. The task involved working with a Kaggle dataset to enhance predictive performance through the use of various boosting algorithms. Initially, baseline models were established using common classifiers, and their performance was evaluated using standard metrics such as `precision`, `recall`, `F1-score`, `ROC-AUC`. Subsequently, the assignment delved into the implementation and comparison of different boosting methods, focusing on `CatBoost`. The emphasis was placed on tuning hyperparameters to optimize model performance. Additionally, the importance of feature selection was highlighted to mitigate overfitting and improve generalization. I also implemented several `probability calibration methods` to improve the quality of predictions. This included using calibration techniques such as `isotonic regression` and `Platt scaling`. Additionally, I conducted `iterative feature selection` for `logistic regression`. This process involved sequentially adding and removing features to determine their impact on the model's performance. This approach allowed me to identify the most significant features and eliminate irrelevant or redundant ones, which helped improve the model's generalization ability and reduce the risk of overfitting.



