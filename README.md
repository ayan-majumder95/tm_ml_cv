This repository contains the initial structures of the membrane bilayer, plumed scripts used to generate the potentials of mean force using well-tempered metadynamics, and Python codes used to derive CV using the DeepLDA and SPIB protocol for the paper "Machine Learning Derived Collective Variables for the Study of Protein Homodimerization in Membrane" by Ayan Majumder and John E. Straub


Input files used for 3D metadynamics protocol are available on: https://github.com/ayan-majumder95/tm_metad
The DeepLDA code was adapted from https://github.com/luigibonati/data-driven-CVs
The SPIB code was adapted from https://github.com/tiwarylab/State-Predictive-Information-Bottleneck

In this study, we used pytorch and libtorch version 1.13.1+. To compile plumed with pytorch/libtorch, please follow the instructions on:https://www.plumed.org/doc-master/user-doc/html/_p_y_t_o_r_c_h__m_o_d_e_l.html
