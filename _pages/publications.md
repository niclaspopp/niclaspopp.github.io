---
title: "Projects and Publications"
permalink: /publications/
author_profile: true
---
<br>
<br>


Publications
======

**Structural Benchmarking for Gene Regulatory Network Inference based on Single-Cell RNA Sequencing Data**<br><br>
In collaboration with Marco Stock, Jonathan Fiorentino and Antonio Scialdone we carried out a benchmarking study on algorithms for the inference of gene regulatory networks with respect to the preservance of topological graph properties as well as the definition and formation of hubs. As a joint first author I took care the theoretical foundations and carried out the experiments. Published in Bioinformatics, Volume 40, Issue 5, May 2024, [link](https://academic.oup.com/bioinformatics/article/40/5/btae267/7646844).


Additional Projects
======

**Randomized Diagonal Estimation**<br><br>
Implicit diagonal estimation is a long-standing problem that is concerned with approximating the diagonal of a matrix (function) that can only be accessed through matrix-vector products. For my master thesis, I worked both on theoretical and software-related aspects of implicit diagonal estimation. Therefore, I developed  [RandomizedDiagonalEstimation.jl]([https://github.com/niclaspopp/MultivariateDiscretization.jl](https://github.com/niclaspopp/RandomizedDiagonalEstimation.jl/tree/master), which implements existing and novel randomized methods for accomplishing this task in a scalable way. The practical applications of the provided algorithms extend across diverse domains such as network science, material science, optimization and machine learning. Additionally, I provide first-of-their kind convergence guarantees with corresponding proofs which can be found in my [thesis](https://niclaspopp.github.io/files/thesis_popp.pdf](http://kth.diva-portal.org/smash/record.jsf?pid=diva2%3A1811790&dswid=-3251). The project was presented at [JuliaCon 2024](https://pretalx.com/juliacon2024/talk/3M8WUH/) in Eindhoven.

**Gene regulatory network inference from scRNA-seq data by incorporating prior knowledge with graph autoencoders**<br><br>
Together with Marco Stock and Antonio Scialdone we have developed a novel algorithm for the inference of gene regulatory networks from single-cell transcriptomic data which is based on graph autoencoders and has a focus computational efficiency. My part of the project was to present the theoretical background and assist the evaluation of the results as well as writing the manuscript (which is currently still in preparation).

**Interaction Preserving Discretization Methods and Applications in Single-Cell RNA Sequencing Data Analysis**<br><br>
The project for my Bachelor thesis dealt with interaction preserving discretization schemes that were implemented and published in the form of a [Julia package](https://github.com/niclaspopp/MultivariateDiscretization.jl) as well as their application to biological single-cell omics data. The project was supervised by Prof. Dr. Dr. Fabian Theis, Dr. Antonio Scialdone and Dr. Jonathan Fiorentino and the thesis can be found [here](https://niclaspopp.github.io/files/thesis_popp.pdf).


**Stochastic gene expression in mammalian cells**<br><br>
In 2021 I was granted the DAAD RISE scholarship to carry out a summer internship in the lab of [Ramon Grima](https://grimagroup.bio.ed.ac.uk/home) at the University of Edinburgh and was introduced into the usage of stochastic differential equations for the modelling of gene expression in mammalian cells. The main focus was on computational aspects of model reduction.

**A Parallel Implementation of the Spectral Clustering Algorithm**<br><br>
As part of my coursework at KTH, I implemented a parellel version of the Spectral Clustering Algorithm using MPI in C. The building blocks of the algorithm are the QR method, parallel odd-even sort and k-means. The code can be found in [this](https://github.com/niclaspopp/SpectralClusteringMPI) repository and the project report is uploaded [here](https://niclaspopp.github.io/files/SpectralClustering_report_corrected.pdf).
The project was supervised by [Niclas Jansson](https://www.kth.se/profile/njansson).

**Exploring Neural Ordinary Differential Equations**<br><br>
For the project course in Deep learning for Data Science and KTH, Jannik Wagner, Katrina Liang and I were experimenting with Neural ODEs. First, we modelled the evolution of daily new COVID-19 cases in Sweden as an example for Time Series Analysis. Furthermore, we used generative models based on continuous normailizing flows in conjunction with simple densities as well as the MNIST dataset to sample new images. The implementation was done in Julia and Python based on Flux and Pytorch. The repository can be found [here](https://github.com/jannikwagner/DD2424) and the report is [here](https://niclaspopp.github.io/files/dd2424_report.pdf).

**Facial Expression Recognition Using Topological Data Analysis**<br><br>
During of the final project for the course "Topological Data Analyis" given by [Wojciech Chachólski](https://www.kth.se/profile/wojtek/). Yuqi Shao, Lea Keller, Maxime Scali and I investigated whether topological data analysis can be used to achieve progress in the difficult field of facial expression recognition. Therefore, we experimented with the FER2013 dataset and used a computational framework based on higher homologies in Python. The results can be found in [this](https://github.com/yuqish/TDA_project) repository together with the [report](https://niclaspopp.github.io/files/TDA Report.pdf).
