Problem Statement:- Implementing BackPropagation

leap.ee.iisc.ac.in/sriram/teaching/MLSP21/assignments/HW3/Data.tar.gz

The above dataset has training/test subject faces with happy/sad emotion are provided inthe data. Each image is of 100×100 matrix. Perform PCA to reduce the dimension from10000 toK= 12. Implement a 2 hidden layer deep neural network (each layer containing10 neurons) to classify the happy/sad classes. Use the crossentropy error function withsoftmax output activations and ReLU hidden layer activations. Perform 20 iterations ofback propagation and plot the error on training data as a function of the iteration. Whatis the test accuracy for this case and how does it change if thenumber of hiddent neuronsis increased to 15. Does momentum (with a momentum factor of 0.9) improve the learningprocess ? Provide your detailed analysis.
