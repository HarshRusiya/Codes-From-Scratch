Problem Statement 1:- Fischer faces- Data is posted here

http://leap.ee.iisc.ac.in/sriram/teaching/MLSP21/assignments/data/Data.tar.gz

Copy and paste the above link in the browser with the underscore for MLSP1915 subject faces with happy/sad emotion are provided in the data.  Each image is of 100x100 matrix.  Perform PCA on to reduce the dimension from 10000 toK(usingPCA for high dimensional data) and then perform LDA to one dimension. Plot the onedimension features for each image. Select the optimum threshold to classify the emotionand report the classification accuracy on the test data. Whatis the best choice ofKwhich gives the maximum separability?

Problem Statement 2:- Speech spectrogram- We have clean and noisy speech files here

http://leap.ee.iisc.ac.in/sriram/teaching/MLSP21/assignments/data/speech.zip

The files are in wav format sampled at 16kHz. Write a function to compute the spectro-gram of clean and noisy files (use 25 ms Hamming window with a shift of 10 ms, compute256 point magnitude FFT and retain the first 128 dimensions ineach window, apply logof the magnitude of the FFT.). For example, a speech file of 3s will have a spectrogram ofsize 128×298 (without any padding at the end, where 128 is the dimension of the featurevector and 298 is the number of frames).

(a) Assume that each speech frame (128 dimensional vector) is independent of each other.From the clean files, compute the whitening transform. Applythe transform on thenoisy speech features. Find the average of the absolute value of the non-diagonalentries of the sampled covariance matrix of the “whitenned”clean and noisy speechfeatures. Comment on use of whitenning when the data distribution has changed.

(b) Repeat the above procedure by reversing the roles of clean and noisy files.
