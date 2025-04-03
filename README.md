# Animal-Classification-Tree
UC Irvine https://archive.ics.uci.edu/dataset/111/zoo | Ideas: https://treevis.net/

Decision Tree Visualization for Zoo Dataset

Overview

This project trains a decision tree classifier on the UCI Zoo dataset to classify animals into different groups such as mammals, birds, reptiles, and more. The decision tree is then visualized using NetworkX to create a graphical representation with human-readable labels.

Dataset

The dataset consists of various animal attributes (e.g., hair, feathers, eggs, milk, airborne, aquatic, predator, backbone) and a class label indicating the type of animal. The animal_name column is removed from the features since it is non-numeric and not useful for training.

Features of the Code

- Loads the Zoo dataset from the UCI repository.

- Prepares the data by separating features and target labels.

- Splits the dataset into training and testing sets (80/20 split).

- Trains a DecisionTreeClassifier with a depth limit.

- Maps numeric class labels to their respective animal groups.

- Builds a directed graph representation of the decision tree using NetworkX.

- Displays the decision tree with appropriate labels and colors to differentiate internal nodes and leaf nodes.


Dependencies : pandas, numpy, matplotlib, sklearn, and networkx.
