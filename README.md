# Reinforcement learning via single-photon quantum walks

## Overview
This repository provides code and data for the paper <em>Reinforcement learning via single-photon quantum walks</em> by Fulvio Flamini*, Marius Krumm*, Lukas J. Fiderer, Thomas Mueller, and Hans J. Briegel. * denotes shared first authorship. 

The paper investigates a quantization of <em>Projective Simulation</em>, a reinforcement learning framework to study agency from a physical perspective, see: H. J. Briegel and G. de las Cuevas, <em>Projective simulation for artificial intelligence</em>, Sci. Rep., vol. 2, p. 400, 2012. An implementation based on integrated photonic technologies is also proposed and numerically analyzed.

This repository consists of two separate packages:
* A Mathematica notebook for the design and analysis of interferometer layouts for the implementation of quantum episodic and compositional memories (ECM). The notebook and accompanying data can be found in the folder <em>PhotonicECM</em>. 
* A Jupyter notebook simulating a photonics PS agent in a specific transfer learning scenario, together with data produced by the Jupyter notebook. This can be found in the folder <em>TransferLearning</em>. This analysis demonstrates how the quantum PS agent can use interference to outperform a classical PS agent on the same task. The considered task is an adapted version of the scenario investigated in B. Eva, K. Ried, T. Mueller, and H. J. Briegel, <em>How a minimal learning agent can infer the existence of unobserved variables in a complex environment</em>, Minds & Machines, pp. 1-35, 2022, online first, [`DOI = 10.1007/s11023-022-09619-5`](https://doi.org/10.1007/s11023-022-09619-5) .

## Libraries
The transfer-learning part uses the following libraries:
* Python 3.10.8
* PyTorch 1.13.0
* Numpy 1.23.4
* Matplotlib 3.6.2
* Torchvision 0.14.0
* Joblib 1.1.1

The Mathematica notebook uses Mathematica 12.1.1.0 .

## Code contributions
* Marius Ernst Hagen Krumm contributed the Python code simulating the photonic PS agent in the transfer-learning scenario.
* Fulvio Flamini contributed the Mathematica code for design and analysis of quantum optical PS agents.
