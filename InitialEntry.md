**Team Name:** 

Entangled_Nets

**Project Description:**

The large experiments conducted in the field of particle physics require the detection and analysis of data produced in particle collisions that occurred using high-energy accelerators such as the LHC [2]. In these experiments, particles that are created by collisions are observed by layers of high-precision detectors surrounding the collision points, which produces large amounts of data about the collision. This motivated the use of "classical" machine learning techniques in different aspects to improve the performance and analysis of the data. Moreover, these developed techniques are also adapted to quantum computing, e.g, the unfolding measurement distributions via quantum annealing [3]. Intending to take advantage of both fields, the techniques in quantum machine learning, which are considered as one of the quantum computing algorithms that could bring quantum advantages over classical methods [4][5], will be used.

Furthermore, since the development of quantum hardware with a sufficient number of qubits is still in progress, circuits that make use of fewer qubits are more plausible to consider. Besides, such circuits may prove relevant even if they do not provide any quantum advantage, since they may be useful parts of larger circuits. We will use the idea of data reuploading discussed by Pérez-Salinas et al. [6], where it is shown that it's possible to load a single qubit with arbitrary dimensional data and then use it as a universal quantum classifier.


This project aims to use the method of data-reuploading, where qubits will be used as quantum classifiers to classify a certain dataset with high accuracy and the parametrized quantum circuit, whose variables are used to construct a cost function that should be minimized "classically". For our model, the SUSY dataset [1] will be considered.


[1] [SUSY Data Set - UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/SUSY#)

[2] [Event Classification with Quantum Machine Learning in High-Energy Physics](https://arxiv.org/abs/2002.09935)

[3] [Unfolding measurement distributions via quantum annealing](https://link.springer.com/article/10.1007/JHEP11(2019)128)

[4] [Quantum Computing in the NISQ era and beyond](https://quantum-journal.org/papers/q-2018-08-06-79/#)

[5] [Quantum Machine Learning in High Energy Physics](https://arxiv.org/abs/2005.08582)

[6] [Data re-uploading for a universal quantum classifier, Adrián Pérez-Salinas, Alba Cervera-Lierta, Elies Gil-Fuster, José I. Latorre](https://arxiv.org/abs/1907.02085)


**Source code:**

[The draft source code](https://github.com/VoicuTomut/Event-Classification-with-data-reuploading-in-High-Energy-Physics/blob/main/Data%20visualisation.ipynb)

Note: This is a draft code for the initial entry for the AWS Power-up. The final source code will be modified and submitted next within the final deadline.

**Resource Estimate:**

We intend to use the power-up prize to further investigate the algorithms and try different approaches to increase the accuracy of our model using simulators. Besides testing the developed model on the quantum hardware access provided by AWS.

(Aspen-8)
Task charges: 1 task x $0.30 / task = $0.30
Shots charges: 1,000 shots x $0.00035 / shot = $0.35
Total charges/Task: $0.65 = $0.30 + $0.35

1Qubit testing:
<ul>
  Number of Tasks: 1000
  Total charges: $650=1000*$0.65
<ul>
2Qubits testing:
Number of Tasks: 1000
Total charges: $650=1000*$0.65

1 Qubit training:
Number of Tasks: 200*10=20000 (10 epoch 200 tasks/epoch)
Total charges: $1300=2000*$0.65

2 Qubit training:
Number of Tasks: 200*10=20000 (10 epoch 200 tasks/epoch)
Total charges: $1300=2000*$0.65

Total resourece estimation: $3900



