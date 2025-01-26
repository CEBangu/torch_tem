# This is a Fork
This is a fork of the original repository, done for Robotics at ENS (Master of Cognitive Science [Cogmaster]), in 2025, to implement and experiment with the model. 

We explored the parameter space to probe the sensitivity of the model to changes in its memory matrix. We find that 
the model is very sensitive to changes in its Hebbian learning parameters, values which are set at biologically suspicious levels. 


# Original ReadMe:
<!--
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]
-->

# Torch TEM

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
	* [Installation](#installation)
	* [Model Training](#model-training)
	* [Model Analysis](#model-analysis)	
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)


<!-- ABOUT THE PROJECT -->
## About The Project

This is an implementation of the Tolman-Eichenbaum Machine in pytorch, written from scratch by following the Supplementary Material of [the original paper](https://www.biorxiv.org/content/10.1101/770495v2.full). It is extensively annotated and tries to follow the notation and terminology from the publication as closely as possible.


<!-- GETTING STARTED -->
## Getting Started

You need to install [python >= 3.6.0](https://www.python.org/downloads/) and [pytorch >= 1.6.0](https://pytorch.org/).


### Installation

Clone the repo
```sh
git clone https://github.com/jbakermans/torch_tem.git
```

### Model Training

With the repo as working directory, train a model by running
```sh
python run.py
```
Model parameters are specified in ```parameters.py```.

### Model Analysis

After training a model, analyse a model and plot analysis results by running
```sh
python test.py
```
You will need to specify the correct model run in ```test.py```.

<!-- CONTACT -->
## Contact

[Jacob Bakermans](http://users.ox.ac.uk/~phys1358/) - jacob.bakermans [at] gmail.com

Project Link: [https://github.com/jbakermans/torch_tem](https://github.com/jbakermans/torch_tem)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

Many thanks to James Whittington for advice and assistance throughout.
