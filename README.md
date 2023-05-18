# ANN_classifier_MLP


We need to develop a neural network based classifier for three various but related products. The collected data are the results of a chemical analysis of liquid products grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of products. The data file provided is in text format and has fourteen dimensions, the first of which determines the class of products (product ‘1’, product ‘2’, product ‘3’), which should serve as the output of the neural network classifier. The remaining ones determine the input of the classifier and has 13 constituents as:
1. Ethanol
2. Malic acid
3. Ash
4. Alcalinity of ash
5. Magnesium
6. Total phenols
7. Flavanoids
8. Nonflavanoid phenols
9. Proanthocyanins
10. Color intensity
11. Hue
12. OD280/OD315 of diluted liquid
13. Proline
2.1  Build a classifier (multilayer neural network), vary its parameters (number of hidden layers and number of nodes in each layer) and try to find the best possible classification performance (a table illustrating various results as parameters are varied would be preferred). Please discuss.
2.2 Once this is done, classify (determine to which product they belong) the following entries each of which has 13 attributes:
a) 13.72; 1.43; 2.5; 16.7; 108; 3.4; 3.67; 0.19; 2.04; 6.8; 0.89; 2.87; 1285
b) 12.04; 4.3; 2.38; 22; 80; 2.1; 1.75; 0.42; 1.35; 2.6; 0.79; 2.57; 580
c) 14.13; 4.1; 2.74; 24.5; 96; 2.05; 0.76; 0.56; 1.35; 9.2; 0.61; 1.6; 560
