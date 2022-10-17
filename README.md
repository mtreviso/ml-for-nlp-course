# Machine Learning for NLP course [work in progress]

This repo contains practical examples and exercises that will be used throughout the course.


## Background

This course is an excerpt from the first set of lectures given at Lisbon Machine Learning Summer School (LxMLS). The goal is to provide a theoretical revision of ML alongside practical implementations, moving from shallow linear models, such as CRFs and SVMs, to modern deep learning models, such as recurrent and self-attention networks. At the end of the course, students will be able to understand modern deep learning architectures and write powerful state-of-the-art models via transfer learning using PyTorch. 

More references can be found in:
- [Deep Structured Learning Course by André Martins](https://andre-martins.github.io/pages/deep-structured-learning-ist-fall-2020.html)
- [LxMLS](http://lxmls.it.pt/2021/)
- Machine Learning: a Probabilistic Perspective. Kevin P. Murphy. MIT Press, 2013



## Schedule (15h)

- Foundation: 
  - Linear Algebra, Calculus & Optimization, Probability and Statistics
  - Practical: Numpy, matplotlib, pandas

- Machine Learning:
  - Slides: Supervised learning vs unsupervised learning vs reinforcement learning, overffiting vs underfitting
            Linear models, iris dataset, feature processing
  - Practical: something to do with NLP + tf idf

- Linear Sequential models:
  - HMM, CRF

- Neural Networks
  - CNNs, RNNs

- Self-attention Networks and Transfer Learning
  - Transformers
  - Huggingface library


## Preparing the environment

If you are a Mac/Linux user, you can proceed with:

```bash
python3 -m venv env
source env/bin/activate 
pip3 install -U pip
pip3 install -r requirements.txt
jupyter-notebook
```

If you are a Window user, the above command might not work. In this case, install Miniconda:
https://docs.conda.io/projects/conda/en/latest/user-guide/install/

And then proceed with:

```bash
conda env create -f environment.yml
conda activate ml-for-nlp-course
jupyter-notebook
```
