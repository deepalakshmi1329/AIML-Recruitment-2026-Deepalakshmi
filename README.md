AIML Recruitment 2026
- Name: Deepalakshmi
- Branch: CSE Core
- Year: 2nd Year

 Task 2: Neural Network using MNIST - Completed

Problem Statement
this task was to build a simple neural network to classify handwritten digits from 0 to 9 using the MNIST dataset.

Approach

1. Loaded the MNIST dataset.
2. Checked the image dimensions, pixel values and classes.
3. Normalized pixel values from 0-255 to 0-1.
4. Built a simple neural network with one hidden layer.
5. Used ReLU in the hidden layer and Softmax in the output layer.
6. Trained the model and monitored training and validation performance.
7. Evaluated the model using test accuracy, confusion matrix, precision, recall and F1-score.
8. Changed the number of hidden neurons from 128 to 64 and compared the results.

Technologies Used
- Python
- Google Colab
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn

Results
Original Model
- Hidden neurons: 128
- Test accuracy: 97.67%

Modified Model
- Hidden neurons: 64
- Test accuracy: 97.22%
Reducing the hidden neurons from 128 to 64 decreased the test accuracy by about 0.45 percentage points. The modified model had fewer neurons available to learn patterns from the images.
The notebook also contains training and validation curves, a confusion matrix and a classification report.

Key Learnings
Learned MNIST preprocessing.
Learned neural network basics.
Understood ReLU and Softmax.
Learned model evaluation.
Learned model experimentation.

Challenges
Understanding how to prepare the image data correctly before feeding it into the neural network was a practical challenge during implementation.
