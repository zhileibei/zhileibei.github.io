---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /research/
  - /research.html
---

Thoughts and Aspirations
======

How can we model biological systems <i>in silico</i>?

Working with data across atomic, molecular, and cellular levels has shaped my understanding of computational biology. Unlike the relatively flat structure of sentences or images, biological systems consist of multi-scale spatiotemporal information flows, necessitating tailored representation learning approaches.

This is further compounded by technological limitations, which often produce static snapshots with restricted resolution, incomplete coverage, and high dropout rates. How, then, can we extract the underlying principles of such intricate systems from partial observations? 

I aspire to answer this question by integrating data across scales and modalities in biologically meaningful ways, and developing computational tools with inductive biases that address unique and inherent characteristics of biological data. Through these efforts, I hope to gain a deeper understanding of the regulatory circuits within and between cells and how we can harness the complex biogical systems for therapeuatics and engineering.

Exploration and Preparations
======
Biology operates at atomic, molecular, and cellular scales. My research spans these three levels, focusing on tailoring computational approaches to distinct data types and exploring methods for modeling dynamics within and across scales.
 
At the atomic level, I investigated the generation of target-aware small molecules with high validity and affinity for specific protein pockets, a cornerstone of drug design. Representing molecules as graphs, with atoms as nodes and chemical bonds as edges, I utilized Graph Neural Networks (GNNs) within a diffusion framework to model the biochemical principles underlying molecular assembly. The alignment between the diffusion process and the chemical forces driving molecule generation fascinated me, as did the application of equivariant constraints for geometric GNNs. However, I also recognized that modeling macromolecules at this scale is computationally inefficient for capturing holistic properties and functions, prompting me to explore higher levels of abstraction.

At the molecular level, I applied language modeling techniques to study proteins, representing sequences by their basic residue units and leveraging evolutionary information to derive meaningful representations for understanding and generating proteins. The success of adapting language models to biological data highlighted their potential for extracting insights from protein sequences. Yet, this work revealed that the contextual information, not just individual molecular interactions, is key to understanding clinical outcomes, motivating my shift to broader system-level analyses.

At the cellular level, I explored spatial transcriptomics (ST) to uncover the spatial organization of tissues and the rules governing cell identity and interactions. I developed a Vision Transformer model to generate missing regions of ST slides, which not only supplemented incomplete data to facilitate downstream analyses but also learned fundamental principles of cell identity formation and tissue assembly through self-supervised generative pre-training. While the power of Transformer models in analyzing 2D spatial data was impressive, I encountered challenges stemming from the unique nuances of biological data, sparking my interest in addressing these limitations.

Beyond individual levels, I have also explored methods to integrate and model the interplay between them. By leveraging knowledge graphs, I generated cross-level insights and data-driven hypotheses from highly condensed information about biological entities such as genes and drugs. This approach offered a glimpse into the possibilities of capturing nonlinear regulations across scales, while also underscoring the need for new computational tools to better model intra- and inter-scale complexities.