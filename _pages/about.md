---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

* I am a Ph.D. student in the [School of Mechanical Engineering](https://www.me.gatech.edu/) at [Georgia Institute of Technology](https://www.gatech.edu/), advised by Prof. [Yan Wang](https://www.me.gatech.edu/faculty/wang-y) in the [Multi-Scale Systems Engineering Research Group](https://msse.gatech.edu/). My dissertation title is "Investigation of process-structure relationship for additive manufacturing with multiphysics simulation and physics-constrained machine learning".
* I received my Bachelor’s Degree in [Tsinghua University](https://www.tsinghua.edu.cn/publish/thu2018en/index.html). My undergraduate research advisors are Prof. [Yiming Rong](https://mee.sustech.edu.cn/2016/node1_0809/130.html) and Prof. [Gang Wang](https://www.tsinghua.edu.cn/publish/jxxen/4192/2014/20141108142525343207364/20141108142525343207364_.html).

* Welcome to view my latest [Curriculum Vitae](http://dehaoliu.github.io/files/DehaoLiu_CV.pdf) if you want to learn more about me.


# Research Interests
The overall goal of my research is to establish comprehensive and robust **process-structure-property (P-S-P) relationships** for the systematic process and materials design by combining **multiscale multiphysics simulation** and **physics-constrained machine learning**. The main research thrust areas are listed as follows.

* Multiscale Multiphysics Modeling and Simulation
	In this research direction, I aim to utilize the **Integrated Computational Materials Engineering (ICME)** approach to establish P-S-P relationships by integrating models at multiple length scales. Specifically, various models, from macro-scale (finite element, finite volume), mesoscale (phase-field method, thermal lattice Boltzmann method, kinetic Monte Carlo), to nano-scale (molecular dynamics, density functional theory), are integrated to make an accurate forward prediction of material properties or behavior. A multiphysics simulation framework called **phase-field and thermal lattice Boltzmann method (PF-TLBM)** has been developed to predict microstructure evolution in metal additive manufacturing, whereas others remain as future work.

* Physics-Constrained Machine Learning
	Machine learning (ML) models such as neural networks and deep learning models have been applied successfully in diverse fields. Nevertheless, data sparsity is still the main challenge to apply these models to solve complex scientific and engineering problems. The root cause is the **“curse of dimensionality”** in training these models. Training algorithms need to explore and exploit in a very high dimensional nonlinear parameter space to search the optimal parameters for complex models. This research direction aims to develop novel, robust, and data-efficient physics-constrained machine learning models to alleviate the curse of dimensionality during the construction of P-S-P relationships. A **multi-fidelity physics-constrained neural network (MF-PCNN)** has been developed to be applied in materials modeling. A **physics-constrained neural network with minimax architecture (PCNN-MM)** has been developed to systematically adjust the relative importance of training data and prior knowledge. A new saddle point search method called **Dual-Dimer method** has been developed to search **highorder saddle points** of nonconvex-nonconcave objective functions.

* Scalable Versatile Bayesian Optimization
	Once P-S-P relationships are established, the classical Bayesian optimization framework can be used to conduct process and materials design. Since real engineering optimization problems are usually high-dimensional, constrained, and multi-objective, some extensions are needed to make the Bayesian optimization framework more versatile.



# Recent News
* February 7, 2020. One paper entitleed ["Multiphysics simulation of nucleation and grain growth in selective laser melting of alloys"](https://asmedigitalcollection.asme.org/computingengineering/article/doi/10.1115/1.4046543/1075062/Multiphysics-Simulation-of-Nucleation-and-Grain) was accpeted to Journal of Computing and Information Science in Engineering.
* July 16, 2019. One paper entiled ["Multi-Fidelity Physics-Constrained Neural Network and Its Application in Materials Modeling"](https://asmedigitalcollection.asme.org/mechanicaldesign/article/141/12/121403/956256/Multi-Fidelity-Physics-Constrained-Neural-Network) was accpeted to Journal of Mechanical Design.
* April 8, 2019. Two papers were accepted to IDETC/CIE 2019.
* December 6, 2018. One paper entitled ["Mesoscale multi-physics simulation of rapid solidification of Ti-6Al-4V alloy"](https://www.sciencedirect.com/science/article/pii/S2214860417306139) was accepted to Additive Manufacturing(Impact Factor: 7.173).

