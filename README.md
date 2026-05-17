# LW4-Activity--Improving-CNN-Performance-Using-Regularization

## google colab link:https://colab.research.google.com/drive/1lHcTo6Zux4VBd56v83G1X7jZC58fI5Xc?usp=sharing

## PART 4: Compare Results (Before vs After)

| Metric               | Baseline Model | Improved Model |
|----------------------|----------------|----------------|
| Training Accuracy    |                |                |
| Validation Accuracy  |                |                |
| Precision            |                |                |
| Recall               |                |                |
| F1-score             |                |                |
| AUC Score            |                |                |

# GUIDE QUESTIONS (Student Explanation & Reflection)

## A. Model Evaluation Analysis
1. What were the weakest-performing classes based on the confusion matrix? The weakest-performing classes were the ones most often confused with other classes in the confusion matrix. This means the model had difficulty distinguishing their features.
2. How did Precision, Recall, and F1-score vary across classes? Precision, Recall, and F1-score were different for each class. Classes with clearer features had higher scores, while similar-looking classes had lower scores.
3. What does a low recall indicate in your model? A low recall means the model missed many actual images of a class, resulting in more false negatives.
4. How does AUC score reflect model performance compared to accuracy? Accuracy shows overall correctness, while AUC measures how well the model separates classes. A high AUC means the model performs well even across different thresholds.
## B. Model Improvement
5. How did data augmentation affect validation accuracy? Data augmentation improved validation accuracy by making the training images more diverse, helping the model generalize better.
6. Why is Batch Normalization important in CNNs? Batch Normalization made training faster and more stable by normalizing data between layers.
7. What role did Dropout play in improving your model? Dropout reduced overfitting by preventing the model from depending too much on certain neurons.
8. How did Early Stopping prevent overfitting? Early Stopping prevented overfitting by stopping training once validation performance stopped improving.
## C. Performance Comparison
9. What improvements were observed after modifying the model? After improving the model, validation accuracy, F1-score, and AUC increased, while overfitting decreased.
10. Which enhancement contributed the most to performance improvement? Why? Data augmentation contributed the most because it exposed the model to more image variations, improving generalization.
11. Did the gap between training and validation accuracy decrease? Explain. Yes, the gap between training and validation accuracy became smaller, showing better generalization.
D. Explainability (Grad-CAM Integration)
12. How did Grad-CAM help in understanding model predictions? Grad-CAM helped visualize which parts of the image the CNN focused on during prediction.
13. Did the improved model focus on more relevant regions? Provide evidence. Yes, the improved model focused more on the actual object instead of the background, showing better feature learning.
14. Why is explainability important in real-world AI applications? Explainability is important because it helps people trust AI systems and understand how predictions are made.
