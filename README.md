# Deep Learning Benchmark Challenge
My workspace files where I try to reach highest accuracy benchmarks on standard datasets by combining techniques from various Deep Learning conference papers.

## MNIST

### Target \#1
Neural Network built by Srivastava et al, in their [Dropout paper][1]

| Model                    | Architecture                                                         | Error         |
| ------------------------ |:-------------------------------------------------------------------- |:------------- |
| NN - Srivastava et al    | 2 hidden layers; 8192 units per layer; Dropout + max-norm constraint | 0.95          |
| NN - Srivastava et al    | 3 hidden layers; 1024 units per layer; Dropout                       | 1.35          | 
| NN - (Me)                | 2 hidden layers; 2048 units per layer; Dropout                       | 1.71          |
| NN - (Me)                | 1 hidden layer; 2048 units per layer; Dropout                        | 2.02          |
| NN (Tensorflow) - (Me)   | 2 hidden layers; 4096 units per layer; Dropout                       | (In Progress) |
| NN (Keras + TF) - (Me)   | 2 hidden layers; 4096 units per layer; Dropout                       | (In Progress) |


[1]: https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf
