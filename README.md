# Custom-Image-Classifier

https://colab.research.google.com/drive/1Deywayl1g8GiWOoUIGlfl0gBBFqd8fzz?usp=sharing

Answer the following questions based on your experience:

1.How did the number of images per class affect your model’s accuracy?
The model achieved 100% precision, recall, and f1-score for all classes on the validation set, indicating that the number of images per class was sufficient for accurate classification.

2.Which plant species were most commonly misclassified and why?
No plant species were misclassified in the validation set, as the model achieved 100% accuracy.

3.How did changing the epochs, batch size, or learning rate affect the training results?
The second training run increased epochs from 10 to 15 and, more importantly, introduced data augmentation and dropout layers. Both models reached 100% validation accuracy, but the second model is generally more robust due to these additions.

4.What challenges did you encounter during dataset collection and labeling?
The provided notebook does not contain any information about dataset collection or labeling, so this question cannot be answered from the given context.

5.If you were to improve your model, what specific changes would you make and why?
Given the current 100% validation accuracy, improvements would focus on ensuring real-world robustness. This could include testing with a more diverse, entirely new dataset, or exploring more advanced techniques like pre-trained models for increased generalization, though it might be overkill for this problem.
