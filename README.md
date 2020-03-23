# PyBEL: a Computational Framework for Biological Expression Language [![DOI](https://zenodo.org/badge/144310970.svg)](https://zenodo.org/badge/latestdoi/144310970)

This repository contains the master's thesis of Charles Tapley Hoyt. Click [here](https://github.com/cthoyt/masters-thesis/raw/master/main.pdf) to get the PDF of the latest build from GitHub.

## Build

To build as a PDF, clone the repository and use the following command:

```bash
$ latexmk -pdf -pvc main
```

## Abstract

The quantity of data, information, and knowledge in the biomedical domain is increasing at an unprecedented rate — with no signs of deceleration. Even with the assistance of information retrieval technologies, it is overwhelming, if not impossible, for individuals or groups of researchers to be knowledgeable of the state-of-the-art in any but an incredibly specific topic. Besides their obvious increases in volume and velocity, data are also increasing in variety as multi- modal and multi-scale experiments grow more important in the investigation of complex diseases. As experiments’ complexities grow, so does the intellectual and temporal burden of analysis and interpretation.

The ability to reason over the wealth of knowledge from both structured and unstructured sources to generate and prioritize hypotheses in order to automat- ically interpret new data sets would provide a huge relief to this burden.
Developing systematic and reproducible methods first requires the formaliza- tion and assembly of knowledge in a computable form. As an aside, many techniques and methodologies in bioinformatics are biased towards the study of cancer biology and focus on data and knowledge at the molecular level. In this modeling strategy, often called the bottom-up approach, network and math- ematical models are validated against the literature and experiments.

As we foray into the assembly of knowledge pertaining to new disease ar- eas and associated clinical indications, we find much more focus on the process level and phenotypic level. Because the links between genetics, molecular mech- anisms, phenotypes, and clinical measurements are much less clear, they also require the top-down approach to modeling, which first focuses on the larger scales. While most modeling languages and data formats for assembling knowl- edge are insufficient, the Biological Expression Language (BEL) possesses the unique faculty to capture this multi-scale knowledge. It has the potential to serve as a semantic integration platform on which the data measured across scales can be integrated and analyzed.

The purpose of this work is to outline the first steps taken towards the building of an automatic interpretation and hypothesis generation machine. The contents of this thesis describe the framework built to parse and manipulate the knowl- edge assemblies encoded in BEL, which enables BEL to act as a semantic inte- gration layer for heterogeneous data and knowledge sources, the development of a framework for automatic integration of relevant knowledge from structured sources, and the development of schema-free analytical techniques to generate data-driven hypothesis.

## See Also

This work lead to several publications:

1. Hoyt, C. T., Konotopez, A., &  Ebeling, C. (2018). [PyBEL: a computational framework for Biological Expression Language](https://doi.org/10.1093/bioinformatics/btx660). *Bioinformatics (Oxford, England)*, 34(4), 703–704.
2. Hoyt, C. T., *et al.* (2019). [Integration of Structured Biological Data Sources using Biological Expression Language](https://doi.org/10.1101/631812). *bioRxiv*, 631812.

as well as later my doctoral thesis:

3. https://github.com/cthoyt/doctoral-thesis
