# Handwritten-digit-recognition
One-versus-all multiclass classification

Recognizing handwritten digits is a popular multiclass classification problem commonly
built into the software of mobile banking applications, as well as more traditional automated
teller machines, to give users e.g., the ability to automatically deposit paper
checks. Here each class of data consists of (images of) several handwritten versions of a
single digit in the range 0-9, giving a total of ten classes. we aim
to learn a separator that distinguishes each of the ten classes from each other.

In this project, we will perform C = 10 multiclass classification for handwritten digit
recognition, employing the OvA multiclass classification framework. Employ the softmax cost with gradient descent or Newton’s method to solve
each of the two-class subproblems.
1) Train our classifier on the training set located in MNIST_training_data.csv, that
contains P = 60 000 examples of handwritten digits 0 − 9 (all examples are vectorized
grayscale images of size 28 × 28 pixels). We can report the accuracy of our trained model on
this training set.
2) Using the weights learned from part 1), we can report the accuracy of our model on a new
test dataset of handwritten digits located in MNIST_testing_data.csv. This contains P =
10 000 new examples of handwritten digits that were not used in the training of our
model.
