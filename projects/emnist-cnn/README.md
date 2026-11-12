# EMNIST Letter Recognition with a CNN

**Individual deep learning coursework · Singapore Polytechnic ST1504 CA1 Part A**

Built a convolutional neural network to classify handwritten letters from the 26-class EMNIST Letters dataset. The data preparation addressed invalid labels and the dataset's image orientation, then converted images to 28 × 28 grayscale tensors and normalised pixel values for training.

## What I did

- Explored class balance and inspected sample images before modelling.
- Compared a baseline CNN with a deeper architecture using batch normalisation, dropout and training callbacks.
- Tested image augmentation against the same model without augmentation.
- Evaluated the held-out test set with a classification report and confusion matrix.

**Tools:** Python, TensorFlow/Keras, pandas, NumPy, scikit-learn, Matplotlib

This portfolio page describes the individual coursework. The course dataset, notebook outputs and model weights are not included. I have left out a headline accuracy because the saved notebook's comparison table and conclusion report inconsistent values.
