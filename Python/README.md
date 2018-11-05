# README

## Environments

Each notebook uses a specific set of libraries and to make it easier to reproduce, there are virtual environments that have been created. To run any specific example, please follow the steps listed under the specific header. For generic instructions on environments, refer to [conda documentation](https://conda.io/docs/user-guide/tasks/manage-environments.html).

## Simple Neural Net

Builds a simple 3 layer neural net from scratch.

*Data file:* [Wine.csv](https://github.com/DheerajAgarwal/NeuralNet_Examples/blob/master/data/Wine.csv)
*Notebook:* [Wine.ipynb](https://github.com/DheerajAgarwal/NeuralNet_Examples/blob/master/Python/SimpleNeuralNet/Wine.ipynb)
*Environment:*[NN.yml](https://github.com/DheerajAgarwal/NeuralNet_Examples/blob/master/Python/environments/NN.yml)

**Create Simple NN environment**

```
$ git clone https://github.com/DheerajAgarwal/NeuralNet_Examples.git
$ cd NeuralNet_Examples/Python/environments
$ conda env create -f NN.yml
$ activate NN
$ cd ../../
$ jupyter notebook
```

