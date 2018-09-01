---
layout: page
title: Projects
permalink: /projects/
---
# Fun and Course Projects

* **ECE 566: Computational Inference and Learning** | [Project Report](../assets/docs/ece_566.pdf)
:-------------------------|:-------------------------
![sgd_var](../assets/img/sgd_var.png "ECE 566 Course Project"){:height="300px" width="400px"}  |  Optimization algorithms for large scale learning has gained considerable attention in the recent years in the Machine Learning community. Stochastic Gradient Descent (SGD) methods have become popular in today's world of data abundance. Many variants of SGD has since surfaced to attempt to reduce the variance of the gradients to provide better convergence to the optimal solution. We implement ten different variations (published within the last five years) of the standard stochastic gradient descent and report our findings in this article. To put the various SGD algorithms in practice, we apply them on a multilabel classification problem with different loss functions. Multi-label classification is one of the most interesting problems in Machine Learning having usefulness in multiple areas / industries, if solved properly. We study two loss functions - Hamming Loss and Subset 0/1 loss along with their similarities and differences. With these two losses, we identify two approaches to the multi-label problem - reduction to independent binary classification problems and reduction to a multi-class classification problem. This report contains related theoretical analysis and results for the two loss functions with ten different variants of SGD implemented on a benchmark multi-label classification dataset.

* **IE 510: Applied Nonlinear Programming** | [Project Report](../assets/docs/ie_510.pdf)
:-------------------------|:-------------------------
![sgd_var_extended](../assets/img/sgd_var_ext.png "IE 510 Course Project"){:height="300px" width="400px"}  |  In this paper, we extend the previous project and study the relative performance of nine recent variants of the stochastic gradient descent (SGD) algorithm across three data sets for three loss functions accustomed to a multi-label-classification setting. We present a theoretical analysis of SGD and two loss functions and highlight a critical drawback in the multi-label-classification literature. We also develop a set of guidelines for readers on the recommended use of these methods for different cases.

* **Finite State Automata** | [The link to the modified simulator](https://href.li/?https://www.dropbox.com/s/9c5tzwn1awkdp5u/Source%20Code.zip)
:-------------------------|:-------------------------
![sfa](../assets/img/sfa.png "Finite State Automata Simulator"){:height="300px" width="400px"}  |  Extended the famous simulator made by J.Bovet (Software Engineer @BEAS , San Francisco) for finite state automata. This was a course project for Theory of Computation (MTH401) offered in Fall 2012 at IIT Kanpur.<br />
[The link to the original simuator, Bovet, J. 2004. Visual Automata Simulator.](https://href.li/?http://www.cs.usfca.edu/~jbovet/vas.html)
<br />
Using computational algorithms, the new simulator converts any non-deterministic finite automata (NFA) to minimized deterministic finite automata (DFA), produces regular grammar, regular expression and equivalent states for any DFA.

* **Traffic Control Simulation** | [Link to the Simulator](https://href.li/?https://www.dropbox.com/s/vmyz7x1uxhvkui8/Code.zip)
:-------------------------|:-------------------------
![traffic_sim](../assets/img/traffic_sim.PNG "Traffic Simulator"){:height="300px" width="400px"}  |  This project was done with my two of my friends in the first year of my stay at IIT Kanpur. It is on simulating dynamically changing city traffic with real time updation (using weighted graph theory and optimization) in JAVA. Many companies are active in this this field, particularly, in construction of smarter traffic control systems. We tried to write everything from scratch, avoiding the use of existing libraries as much as we could.