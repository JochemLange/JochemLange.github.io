---
title: "Inverse Design of Crystals and Quasicrystals in a Non-Additive Binary Mixture of Hard Disks"
collection: publications
permalink: /publication/2024-03-22-InverseDesignQuasicrystals
excerpt: 'This paper explores the inverse design of crystals and quasicrystals in a non-additive binary mixture of hard disks. 
To locate the necessary state points and physical parameters where self-assembly for (quasi)crystals occurs, we employed an inverse design technique. 
Essentially, we solve a black box optimization (BBO) problem using an evolutionary strategy (CMA-ES).
In the paper we utilize two different fitness functions. First of all a CNN, secondly a new symmetry-based order parameter.'
date: 2024-03-22
venue: 'Arxiv - Preprint'
paperurl: 'https://arxiv.org/pdf/2403.15277.pdf'
---

#### Authors: 
Edwin A. Bedolla-Montiel, Jochem T. Lange, Alberto Pérez de Alba Ortíz, Marjolein Dijkstra
--------------------

The development of new materials typically involves a process of trial and error, guided by insights from past experimental and theoretical findings. The inverse design approach for soft-matter systems has the potential to optimize specific physical parameters such as particle interactions, particle shape, or composition and packing fraction. This optimization aims to facilitate the spontaneous formation of specific target structures through self-assembly. In this study, we expand upon a recently introduced inverse design protocol for monodisperse systems to identify the required conditions and interactions for assembling crystal and quasicrystal phases within a binary mixture of two distinct species. This method utilizes an evolutionary algorithm to identify the optimal state point and interaction parameters, enabling the self-assembly of the desired structure. Additionally, we employ a convolutional neural network (CNN) that classifies different phases based on their diffraction patterns, serving as a fitness function for the desired structure. Using our protocol, we successfully inverse design two-dimensional crystalline structures, including a hexagonal lattice, and a dodecagonal quasicrystal, within a non-additive binary mixture of hard disks. Finally, we introduce a symmetry-based order parameter that leverages the encoded symmetry within the diffraction pattern. This order parameter circumvents the need for training a CNN, and is used as a fitness function to inverse design an octagonal quasicrystal.