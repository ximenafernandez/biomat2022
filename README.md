# Topological Data Analysis and Applications in Dynamics
##  <a href="https://ximenafernandez.github.io/">  _Ximena Fernandez_ </a>
## BIOMAT 2022

<!--<img src="figures/filtration_circle.gif" width="300" height="300" class="center"/>-->

This repository contains all the lectures and code related to the course.

### Lecture 1: Topological Data Analysis
This lecture is about a general exposition of Persistent Homology and some applications. The slides of the lecture are available <a href="https://ximenafernandez.github.io/reveal.js-presentations/slides/PersistentHomology.html"> here</a>.
The demo of the software Ripser can be found at <a href="https://live.ripser.org/"> this link</a>. The synthetic point clouds to test the software are available at the folder _data_: cicle, sphere and torus.

### Lecture 2: Hands on: computational topology in action
This lecture is a live-coding exposition of the use of the software Ripser to compute Persistent Homology, and some real applications with concrete data.

 All the datasets are available at the folder _data_.

 To run the notebooks, it is required to have installed ```jupyter```, as well as the following:
 ``` 
Python (>= 3.6)
NumPy (>= 1.19.1)
SciPy (>= 1.5.0)
scikit-learn (>= 0.23.1)
```

The specific libraries for TDA we use are:
```
ripser
tadasets
persim
```

The notebook _Intro_Persistent_Homology.ipynb_ provides a complete description and implementation of tools related to the computation of persistent homology with the software ```Ripser```. It also contains  some simulations in synthetic point clouds to describe properties of persistent homology and to infer topological features from a sample.

The notebooks with the implementation of several applications from the literature can be found at the folder _applications_:
 - _Example_CycloOctane.ipynb_
 - _Example_GridCells.ipynb_
 - _Proteins_Binding.ipynb_
 - _Proteins_Structure_Classification.ipynb_ 

### Lecture 3: Applications in dynamics
This lecture is about some applications of Persistent Homology to study dynamical systems and analize time series. <!--The slides of this lecture can be found <a href="https://"> here </a>.-->
Some of the applications are based on recent work of the author: 
- **Birdsongs, EEG and Dynamical Systems**: <a href="https://github.com/ximenafernandez/intrinsicPH">Repository IntrinsicPH </a> 
- **iEEG and MEG**: <a href="https://github.com/ximenafernandez/epilepsy">Repository Epilepsy </a> 

