##############################################################################
# Author  : Sagar Surendran
# Data    : 3/21/2020 
# 
# ReadMe file.
##############################################################################

Naive Bayes algorithm implementation with Log Probabilities
 
The Naive Bayes algorithm has been implemented is separately for the three data sets.

The accuracy of the Naive Bayes algorithm using 10-Fold cross validation on the three datasets from the UCI-Machine Learning Repository
is compared with that obtained with Naive Bayes from Weka.

1.	Hayes-Roth Dataset

Naïve Bayes algorithm has been implemented with Log probabilities.

Results from the model:

Accuracy at fold  1  is : 0.5714285714285714
Accuracy at fold  2  is : 0.9285714285714286
Accuracy at fold  3  is : 0.6923076923076923
Accuracy at fold  4  is : 0.5384615384615384
Accuracy at fold  5  is : 0.6923076923076923
Accuracy at fold  6  is : 0.7692307692307693
Accuracy at fold  7  is : 0.6923076923076923
Accuracy at fold  8  is : 0.7692307692307693
Accuracy at fold  9  is : 0.8461538461538461
Accuracy at fold  10  is : 0.6153846153846154
Total Accuracy :  71.1538 %

Accuracy from Weka: 76.51 %
 
References: 
https://archive.ics.uci.edu/ml/datasets/Hayes-Roth
https://machinelearningmastery.com/naive-bayes-classifier-scratch-python/
https://machinelearningmastery.com/k-fold-cross-validation/
https://www.youtube.com/watch?v=2QjFgfjjRwk
	
2.	Car Evaluation Dataset
During the initial data processing, all the column values has been converted to integer values as below.

New values for 
Column 1 are,
[low] => 1
[high] => 2
[med] => 3
[vhigh] => 4

Column 2 are,
[low] => 1
[high] => 2
[med] => 3
[vhigh] => 4

Column 3 are,
[2] => 1
[4] => 2
[3] => 3
[5more] => 4

Column 4 are,
[2] => 1
[4] => 3
[more] => 2

Column 5 are,
[med] => 1
[small] => 2
[big] => 3

Column 6 are,
[low] => 1
[high] => 2
[med] => 3

Column 7 are,
[good] => 1
[acc] => 2
[vgood] => 3
[unacc] => 4


Programming Results:

Accuracy at fold  1  is : 0.7803468208092486
Accuracy at fold  2  is : 0.7572254335260116
Accuracy at fold  3  is : 0.7803468208092486
Accuracy at fold  4  is : 0.7630057803468208
Accuracy at fold  5  is : 0.7456647398843931
Accuracy at fold  6  is : 0.8034682080924855
Accuracy at fold  7  is : 0.791907514450867
Accuracy at fold  8  is : 0.791907514450867
Accuracy at fold  9  is : 0.7732558139534884
Accuracy at fold  10  is : 0.7441860465116279
Total Accuracy :  77.3131 %

Accuracy from Weka: 85.53 %


References: 
https://archive.ics.uci.edu/ml/datasets/Car+Evaluation
https://machinelearningmastery.com/naive-bayes-classifier-scratch-python/
https://machinelearningmastery.com/k-fold-cross-validation/
https://www.youtube.com/watch?v=2QjFgfjjRwk


3.	Breast Cancer Data set

Data preprocessing: During the initial data processing, all the column values has been converted to integer values as below. Also, the rows with missing attributes are removed to avoid unusual behavior. Since the data is already sorted based on Class, the data, during the program execution, is sorted using Column 3.

New values for

Column1 are,
[no-recurrence-events] => 1
[recurrence-events] => 2

Column 2 are,
[50-59] => 1
[30-39] => 2
[70-79] => 3
[20-29] => 4
[40-49] => 5
[60-69] => 6

Column 3 are,
[lt40] => 1
[ge40] => 2
[premeno] => 3

Column 4 are,
[10-14] => 1
[35-39] => 2
[45-49] => 3
[40-44] => 4
[5-9] => 5
[50-54] => 6
[0-4] => 7
[15-19] => 8
[30-34] => 9
[20-24] => 10
[25-29] => 11

Column 5 are,
[24-26] => 1
[9-11] => 2
[6-8] => 3
[3-5] => 4
[15-17] => 5
[12-14] => 6
[0-2] => 7

Column 6 are,
[no] => 1
[yes] => 2

Column 7 are,
[3] => 1
[1] => 2
[2] => 3

Column 8 are,
[right] => 1
[left] => 2

Column 9 are,
[right_up] => 1
[right_low] => 2
[central] => 3
[left_up] => 4
[left_low] => 5

Column 10 are,
[no] => 1
[yes] => 2


Programming logs:

Accuracy at fold  1  is : 0.8928571428571429
Accuracy at fold  2  is : 0.6428571428571429
Accuracy at fold  3  is : 0.75
Accuracy at fold  4  is : 0.8214285714285714
Accuracy at fold  5  is : 0.7857142857142857
Accuracy at fold  6  is : 0.6071428571428571
Accuracy at fold  7  is : 0.8214285714285714
Accuracy at fold  8  is : 0.6666666666666666
Accuracy at fold  9  is : 0.7037037037037037
Accuracy at fold  10  is : 0.7037037037037037
Total Accuracy :  73.955 %

Accuracy from Weka: 74.82%

 
References: 
https://archive.ics.uci.edu/ml/datasets/Breast+Cancer
https://machinelearningmastery.com/naive-bayes-classifier-scratch-python/
https://machinelearningmastery.com/k-fold-cross-validation/
https://www.youtube.com/watch?v=2QjFgfjjRwk

