# Event Classification with data re-uploading in High Energy Physics

## Team name: 

Entangled_Nets


## Introduction

The large experiments conducted in the field of particle physics require the detection and analysis of data produced in particle collisions that occurred using high-energy accelerators such as the LHC. In these experiments, particles that are created by collisions are observed by layers of high-precision detectors surrounding the collision points, which produces large amounts of data about the collision. This motivated the use of "classical" machine learning techniques in different aspects to improve the performance and analysis of the data.

Accordingly, these developed techniques are also adapted to quantum computing, e.g, the unfolding measurement distributions via quantum annealing. Intending to take advantage of both fields, the techniques in quantum machine learning, which are considered as one of the quantum computing algorithms that could bring quantum advantages over classical methods, will be used where QML algorithms developed for gate based quantum hardware, in particular the algorithms based on variational quantum circuits. In variational quantum circuits, the classical data input is encoded into quantum states and a QPU is used to obtain and measure the quantum states which vary with some parameters. Exploiting a complex Hilbert space that grows exponentially with the number of qubits.

This project aims to use the method of data-reuploading, where qubits will be used as quantum classifiers to classify a certain dataset with high accuracy, and parametrized quantum circuit, whose variables are used to construct a cost function that should be minimized "classically". For our model, the SUSY dataset will be considered.

Project Organization
------------

    │
    ├── Best Edu                                                <- final submission with improvemant
    │   ├── SUSY Dataset                                        <- data set for the final submision
    │   └── QHack_Final.ipynb                                   <- final notebook       
    │
    ├── Data 
    │   ├── SUSY_cut                                            <- A piece of "SUSY" data set that we used
    │
    ├── Different tioes of implementation                       <- Simulation of 20 epochs experiments and test on data set of size 5000.
    │   ├── 1Qubit_4Layers_3var                                 <- training: 500; best_AUC:0.828.
    │   ├── 2Qubit_3Layers_6var                                 <- training: 5000; best_AUC:0.826.
    │   ├── 2Qubit_4Layers_3var                                 <- training: 1000; best_AUC:0.83.
    │   └── 2Qubit_5Layers_3var                                 <- training: 1000; best_AUC:0.809.
    │
    ├── Best Edu                                                <- Best implementation made by Edu
    │   ├── SUSY Dataset                                        <- data set for the final submision
    │   └── QHack_Final.ipynb                                   <- final notebook       
    │
    ├── Layer by layer                        
    │   ├── 1Qubit_layer_by_layer                               <- train 1 qubit layer by layer
    │   └── 2Qubits_layer_by_layer                              <- train 2 qubit layer by layer 
    │   
    ├── Optimizers_comparasion                                  <- A comparation of the available optimizers
    │   ├── Adagrad_Optimizer.ipynb     
    │   ├── Adam_Optimizer.ipynb  
    │   └── GradientDescendent_Optimizer.ipynb  
    │   
    ├── Real                                                    <- experiments on real device.(Aspen-9) (for the best option on real device see the QHack_Final.ipynb.)
    │   ├── QPU_Smart_Runn_1Qubit.ipynb                         <- test 1 Qubit 3 Layers on a real device
    │   └──  after_process_Smar_Runn.ipynb                      <- afterprocessing data from QPU_Smart_Runn_1Qubit
    │   
    ├── Data_Visualization.ipynb.                               <-  data information and graphic visualization
    │  
    ├── FinalSubmission.ipynb                                   <- Yeeei!! We are ready to win!!
    │
    ├── InitialEntry                                            <-  InitialEntry for power up
    │
    ├── QHack_Final.ipynb                                       <-  Final Notebook
    │
    └──README.md                                                <- The top-level README .
    


--------
