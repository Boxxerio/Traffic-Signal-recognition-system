# Traffic-Signal-recognition-system
Dataset: German Traffic Sign Benchmark(GTSB) is used which has over 30,000 labelled images with approximate 20,000 images for training and 10,000 images for testing.
Scikit-Learn is used as the library for image processing and prediction.
MLP(Multi Layer Perceptron) and RFC(Random Forest Classifier) is used as classes.
Accuracy by RFC is 75% and 80% after Grid Search.
Accuracy by MLP is 78%.
Preprocessing techniques used are gray scale, addition of noise for better robustness, increasing screen brightness and image resize using opencv. 
