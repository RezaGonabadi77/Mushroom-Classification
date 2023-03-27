#Mushroom Classification Using Neural Network (4 Layers)

Mushroom Classification Using Neural Network (4 Layers)
This project uses a neural network with 4 layers to classify mushrooms into edible or poisonous categories based on their physical characteristics.

Dataset
The dataset used for this project is the Mushroom Classification dataset from the UCI Machine Learning Repository. It contains 8124 samples of mushrooms, each with 22 categorical features describing the physical properties of the mushroom. The target variable is the class of the mushroom, which can be either edible or poisonous.

Neural Network Architecture
The neural network used for this project has 4 layers: an input layer, two hidden layers, and an output layer. The input layer has 22 nodes, one for each feature in the dataset. The two hidden layers have 16 and 8 nodes respectively, and the output layer has 1 node to classify the mushroom as either edible or poisonous.

Preprocessing
Before training the neural network, the dataset is preprocessed in the following ways:

One-hot encoding: Each categorical feature is one-hot encoded to convert it to a numerical representation.
Scaling: The numerical features are scaled to have zero mean and unit variance to improve the performance of the neural network.
Training and Evaluation
The dataset is split into training and testing sets, with 80% of the data used for training and 20% used for testing. The neural network is trained using the Adam optimizer and binary cross-entropy loss function for 50 epochs.

The performance of the neural network is evaluated using the accuracy, precision, recall, and F1 score metrics. Additionally, a ROC plot is generated to visualize the true positive rate and false positive rate of the model.

Results
The neural network achieved an accuracy of 99.8% on the testing set, with precision, recall, and F1 score of 1.0
