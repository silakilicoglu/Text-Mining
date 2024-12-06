# Text-Mining
![Course Code](https://img.shields.io/badge/Course%20Code-732A81-yellow)
![Master's Degree](https://img.shields.io/badge/Master's%20Degree-Statistics%20&%20Machine%20Learning-lightblue)
![Institution](https://img.shields.io/badge/Institution-Linköping%20University-blue)

## Overview
This repository contains lab projects and implementations from the graduate-level course Text Mining at Linköping Univeristy. The course focuses on techniques and methods for analyzing and extracting meaningful information from text data.

---

## Course Content
The course covers the following topics and methods in text mining:

- **Information Retrieval**  
- **Basic Methods in Language Technology**  
- **Predictive Modeling**  
- **Text Clustering and Theme Modeling**  
- **Information Extraction**  
- **Validation Methods**  
  
---

## Requirements:  
This project requires the following dependencies:  

- jupyter [![jupyter](https://img.shields.io/badge/jupyter-latest-blue)](https://jupyter.org/)  
- jupyterlab [![jupyterlab](https://img.shields.io/badge/jupyterlab-latest-blue)](https://jupyterlab.readthedocs.io/en/latest/)  
- jupyter notebook >= 7.0 [![Jupyter Notebook](https://img.shields.io/badge/Jupyter--Notebook-7.0.0-orange?logo=jupyter)](https://jupyter.org/)    
- numpy >= 1.25.0 [![NumPy](https://img.shields.io/badge/numpy-1.25.0-blue?logo=python)](https://numpy.org/)    
- matplotlib >= 3.7.0 [![Matplotlib](https://img.shields.io/badge/matplotlib-3.7.0-blue?logo=python)](https://matplotlib.org/)  
- scikit-learn >= 1.3.0 [![scikit-learn](https://img.shields.io/badge/scikit--learn-1.3.0-blue?logo=scikit-learn)](https://scikit-learn.org/1.5/install.html)  
- pandas >= 2.1.0 [![Pandas](https://img.shields.io/badge/pandas-2.1.0-blue?logo=pandas)](https://pandas.pydata.org/)
- Seaborn >= 0.13.0 [![Seaborn](https://img.shields.io/badge/seaborn-0.13.0-blue?logo=python)](https://seaborn.pydata.org/)  
- huggingface-hub [![Hugging Face](https://img.shields.io/badge/Huggingface-Hub-yellow?logo=HuggingFace)](https://huggingface.co/docs/hub/)  
- nbgrader >= 0.9.0 [![Nbgrader](https://img.shields.io/badge/nbgrader-0.9.0-blue?logo=python)](https://nbgrader.readthedocs.io/)  
- Rich [![Rich](https://img.shields.io/badge/rich-Latest-purple?logo=python)](https://rich.readthedocs.io/)  
- Torch [![Torch](https://img.shields.io/badge/Torch-Latest-red?logo=pytorch)](https://pytorch.org/) (with CPU support via [index URL](https://download.pytorch.org/whl/cpu)) 
- spaCy >= 3.8.0 [![spaCy](https://img.shields.io/badge/spaCy-3.8.0-green?logo=spacy)](https://spacy.io/)  
- [en_core_web_sm-3.8.0](https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-3.8.0/en_core_web_sm-3.8.0-py3-none-any.whl)  
- [en_core_web_md-3.8.0](https://github.com/explosion/spacy-models/releases/download/en_core_web_md-3.8.0/en_core_web_md-3.8.0-py3-none-any.whl)
- llama-cpp-python >= 0.3.1 [![Llama-cpp-python](https://img.shields.io/badge/Llama--cpp--python-0.3.1-blue)](https://abetlen.github.io/llama-cpp-python/whl/cpu)
- pyLDAvis >=3.4.0 [![pyLDAvis](https://img.shields.io/badge/pyLDAavis-3.4.0-green?logo=pyLDAvis)](https://pypi.org/project/pyLDAvis/)  

### **Additional Notes for Specific Labs**

- **Clustering and Topic Modelling**:
  - This lab additionally requires `gensim`, which is **not included in the `requirements.txt`** due to dependency conflicts. Install `gensim` separately **after** installing all other dependencies:  
    ```bash
    pip install gensim
    ```  
  - Alternatively, you can create a **separate virtual environment** for this lab to avoid conflicts.

- **Text Summarization**:
  - This lab uses **llama-cpp** and **PyTorch** but is configured for **CPU-only installations** of these libraries.
  - If you have a GPU and wish to use it for this lab, follow the official [PyTorch installation instructions](https://pytorch.org/get-started/locally/) to set up a GPU-enabled environment.

---

## Installation Instructions  
1. Clone the repository:  
   
```bash
git clone https://github.com/silakilicoglu/Text-Mining.git  
cd Text-Mining 
```

2. Create a Conda environment:  

```bash
conda create --name text_mining_env python=3.9  
```

3. Activate Conda environment:

```bash
conda activate text_mining_env    
```

4. Install dependencies:  
   
```bash
pip install -r requirements.txt  
```
5. For Clustering and Topic Modelling:  
   - After setting up the environment, install gensim:  
     ```bash
     pip install gensim
     ```
6. For Text Summarization:
   - By default, the environment is set up for CPU usage. To use GPU, adapt your PyTorch installation as per [this guide.](https://pytorch.org/get-started/locally/)

## Usage  
To run the Jupyter notebooks:  
1. Launch Jupyter Notebook:  
```bash
jupyter notebook  
```
2. Navigate to the desired notebook in the Jupyter Interface and run the code.  
