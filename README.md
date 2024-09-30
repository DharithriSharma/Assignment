FINDINGS AND INSIGHTS

The dataset named planesnet is being used which consist of 32000 images in PNG format.The images are then preprocessed using normalisation techniques like scaling.
For training, the dataset was split into 80% for training and 20% for validation using a random permutation to ensure a balanced distribution. A total of 100 epochs were selected as the maximum iteration count, and a batch size of 200 was used for optimizing the learning process. To prevent overfitting, an early stopping mechanism was employed using the patience function, which monitored the validation loss. If there was no significant improvement in validation accuracy (i.e., no change in delta) for 10 consecutive epochs, the training process was terminated early.
Training concluded after 46 iterations. The training accuracy reached a peak of 97.89%. The model was trained using TPU in Google Colab to leverage faster computation, which significantly improved the training speed compared to CPU-only environments.

RESULT

The training process resulted in a model achieving a peak training accuracy of 97.89%. Additionally, plots of accuracy and loss versus epochs were generated to visualize the training progression. These visualizations provided insights into the model's learning behavior and highlighted areas where further refinements could enhance performance.
