# RABIES tutorial
This is a hand-tutorial for learning the basic syntax for executing the RABIES software https://github.com/CoBrALab/RABIES. This tutorial was first developed for and presented at the INCF Neuroinformatics assembly 2023, and the original repository can be found here https://github.com/grandjeanlab/INCF_preclinical.

* tutorial_notebook.ipynb: main notebook of the tutorial. With a series of shell commands, will execute each stage of the pipeline on the token dataset.
* process_test_dataset.ipynb: documents the commands used to process the [test_dataset/](https://zenodo.org/record/8349029) and generate the QC outputs found in test_dataset_QC/.
* token_dataset/: a fake dataset regrouping low resolution images, which can be used to quickly test the execution of the pipeline.
* test_dataset_QC/: pre-generated QC outputs from the [test_dataset/](https://zenodo.org/record/8349029) (i.e. outputs on real data).
* RABIES_overview.pdf: slides presented during the workshop, providing an introduction to each stage of the pipeline.

## Pre-requisites for following the tutorial

* [Jupyter Notebook](https://jupyter.org/install) to open the notebooks. Alternatively, you can run operations directly from a terminal (the notebook itself is for demonstration purpose)
* [Docker](https://docs.docker.com/get-docker/), and pulling RABIES version 0.4.8 with `docker pull gabdesgreg/rabies:0.4.8` (make sure to have ~10Gb of free space). Alternatively, the same steps can be conducted using Singularity, although the syntax of the commands must be adapted ([see examples](https://rabies.readthedocs.io/en/latest/running_the_software.html#execution-syntax-with-containerized-installation-singularity-and-docker)).
* Download this github repository; the required notebooks and files are all include in the rabies/ folder. You can download the repo manually by clicking on "code -> download ZIP", or from a terminal using git with `git clone https://github.com/CoBrALab/RABIES_tutorial`.
