# Event Classification with data re-uploading in High Energy Physics

## Team name: 

Entangled_Nets

## Abstract: 

**To be further edited!!!**

The large experiments conducted in the field of particle physics require the detection and analysis of data produced in particle collisions that occurred using high-energy accelerators such as the LHC [2]. In these experiments, particles that are created by collisions are observed by layers of high-precision detectors surrounding the collision points, which produces large amounts of data about the collision. This motivated the use of "classical" machine learning techniques in different aspects to improve the performance and analysis of the data. Moreover, these developed techniques are also adapted to quantum computing, e.g, the unfolding measurement distributions via quantum annealing [3]. Intending to take advantage of both fields, the techniques in quantum machine learning, which are considered as one of the quantum computing algorithms that could bring quantum advantages over classical methods [4][5], will be used.

Furthermore, since the development of quantum hardware with a sufficient number of qubits is still in progress, circuits that make use of fewer qubits are more plausible to consider. Besides, such circuits may prove relevant even if they do not provide any quantum advantage, since they may be useful parts of larger circuits. We will use the idea of data reuploading discussed by Pérez-Salinas et al. [6], where it is shown that it's possible to load a single qubit with arbitrary dimensional data and then use it as a universal quantum classifier.

This project aims to use the method of data-reuploading, where qubits will be used as quantum classifiers to classify a certain dataset with high accuracy, and parametrized quantum circuit, whose variables are used to construct a cost function that should be minimized "classically". For our model, the SUSY dataset [1] will be considered.

[References: ](https://github.com/VoicuTomut/Event-Classification-with-data-reuploading-in-High-Energy-Physics/blob/main/Documentation/Abstract_references.md) [[1]](https://archive.ics.uci.edu/ml/datasets/SUSY#)  [[2]](https://arxiv.org/abs/2002.09935)  [[3]](https://link.springer.com/article/10.1007/JHEP11(2019)128)  [[4]](https://quantum-journal.org/papers/q-2018-08-06-79/#)  [[5]](https://arxiv.org/abs/2005.08582)  [[6]](https://arxiv.org/abs/1907.02085)

Project Organization
------------

    │
    ├── Data 
    │   ├── SUSY_cut                    <- A piece of "SUSY" data set that we used
    │
    ├── Layer performance  Pennylane    <- Simulation of 20 epochs experiments and test on data set of size 5000.
    │   ├── 1Qubit_4Layers_3var         <- training: 500; best_AUC:0.828.
    │   ├── 2Qubit_3Layers_6var         <- training: 5000; best_AUC:0.826.
    │   ├── 2Qubit_4Layers_3var         <- training: 1000; best_AUC:0.83.
    │   └── 2Qubit_5Layers_3var         <- training: 1000; best_AUC:0.809.
    │
    ├── Best performance                        
    │   ├── Edu best code               <- Edu short description +keras
    │   └── 1Qubit                      <- similar with 1Qubit_4Layers_3var 
    │
    ├── Layer by layer                        
    │   ├── 1Qubit_layer_by_layer                              <- train 1 qubit layer by layer
    │   ├── 2Qubits_layer_by_layer                             <- train 2 qubit layer by layer 
    │   └──Edu                                                 <- Edu layer by layer with keras
    │
    ├── Real                                                   <- experiments on real device.(Aspen-9)
    │   ├── QPU_Smart_Runn_1Qubit.ipynb                        <- test 1 Qubit 3 Layers on a real device
    │   ├── after_process_Smar_Runn.ipynb                      <- afterprocessing data from QPU_Smart_Runn_1Qubit
    │   └── Real1                                              <- Edu best algorithm that we have on real device 
    │
    ├── Data_Visualization.ipynb.                              <-  data information and graphic visualization
    ├── InitialEntry                                           <-  InitialEntry for power up
    ├── Presentation Notebook                                  <-  !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
    ├── Requirements                                           <-  !!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
    └──README.md                                               <- The top-level README .
    
    etc  ###Work in progress

--------
