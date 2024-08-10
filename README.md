The structure of the repository is as follows:

1. Raw Datsets: Contains two file corresponding to two area datasets of the Vaihingen. The datasets have x, y, z coordinate as well as cl, cp, cp values along with a class label.
2. Datasets (with features): Contains two folders corresponding to two Are2 and Area2 of Vaihingen. IN each folder, there are four files which are for the fewatures corresponding to four different neighborhood sizes.
3. Feature Computation: Contains three notebooks. BrtueForce is the notebook which is the brute force mthod of computing features. PySpark notebook has PYspark code for computing features. Jakteristics has code to cmpute features using the Jakterisitics library.
4. Models: Bayesian notebook has the bayesian neural network for classifciation. 3Models contains three models which are- Basic Neural Newtork, Classifciation MOdel using UNceratinty as Feature, Classification Model sing a custom Loss Function.
5. GVCL.pdf is the report for the project. 
