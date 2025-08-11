# Loading Pre-extracted Vector Embeddings into Pandas DataFrames

A Jupyter notebook demonstrating how to efficiently load and analyze pre-computed vector embeddings from medical imaging datasets.

## 📋 Overview

This notebook provides a workflow for:
- Loading pre-extracted vector embeddings from disk into pandas DataFrames
- Merging embeddings with clinical metadata and labels
- Implementing machine learning classification using embeddings as features

## 🗂️ Supported Datasets

- **EmoryCXR v2**
- **MIMIC-CXR**
- **MRKR**
- **EMBED**

## 🧠 Supported Embedding Models

- **MedImageInsights**
- **RAD-DINO**
- **CheXagent**
- **MedGemma**
- **Mammo-CLIP** 

## 🚀 Quick Start

### Prerequisites

```bash
pip install pandas numpy scikit-learn tqdm
```