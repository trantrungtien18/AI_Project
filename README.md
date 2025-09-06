# Application of AI to some problems
1. Customer sentiment Clasifications
  - This problem uses a Sequential deep learning model built with Keras, which consists of 6 layers: an Embedding block, an RNN block (2 LSTM layers and 1 Dropout layer), and a Classification block (2 Dense layers).
  - The train dataset used in this problem was obtained from Kaggle, consisting of data aggregated from multiple sources and standardized to produce reliable and easily interpretable results for the model.
  - The results demonstrate the effectiveness of the model through its reliability and the accurate predictions it produces for each test sample.
2. Object Detection
  - And in this work, a Sequential deep learning model is implemented using Keras, comprising 14 layers in total. The architecture includes a convolutional feature extraction part (with multiple Conv2D, BatchNormalization, and MaxPooling2D layers), followed by a Global Average Pooling layer, and a classification part made up of Dense and Dropout layers, ending with a Softmax layer for multi-class prediction.
  - The training dataset for this task was sourced from Kaggle, where the data is compiled from various sources and standardized to ensure consistent quality and to provide results that are both reliable and easy to evaluate for the model.
  - The results of the study show that with the CNN model and appropriate parameters, high accuracy can be achieved, enabling precise entity detection across the test samples.
