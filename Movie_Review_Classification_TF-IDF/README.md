Problem Statement 1:- Use the following data source for the remaining two questions

leap.ee.iisc.ac.in/sriram/teaching/MLSP21/assignments/data/Data.tar.gz

Implementing Linear SVMs- 15 subject faces with happy/sad emotion are providedin the data. Each image is of 100×100 matrix. Perform PCA to reduce the dimensionfrom 10000 toK. Implement a classifier on the training images with linear kernel basedsupport vector machine. One potential source of SVM implementation is the LIBSVMpackage http://www.csie.ntu.edu.tw/cjlin/libsvm/

(a) Use the SVM to classify the test images.  How does the performance change forvarious choice of kernels, parameterCandǫ. How does the performance change asa function ofK.

(b) Compare the SVM classifier with LDA classifier and commenton the similarity anddifferences in terms of the problem formulation as well as the performance.

Problem Statement 2:-Supervised Sentiment Analysis- 

Download the movie review data (each line is aindividual review)http://www.leap.ee.iisc.ac.in/sriram/teaching/MLSP21/assignments/movieReviews1000.txt 

a Split the data into two subsets. One for training (first 3000reviews) and the otherfor testing (last 1000 reviews).

b Use TF-IDF features and train PCA (using the training data)to reduce the data to10 dimensions.

c Train a SVM model. And check the performance on the test set in terms of reviewclassification accuracy.

d Compare different kernel choices - linear, polynomial and radial basis function. Re-port the number of support vectors used and the classification performance for dif-ferent kernel choices.
