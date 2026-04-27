# Deep-learning-assignments
 
Course assignments for **Introduction to Deep Learning** (University, 2023).  
Each folder contains the assignment specification, Jupyter notebooks with experiments, and a written report.
  

 
## Folders
 
### `classifiers_and_nn_intro/`

**Topics covered:**
- Data exploration on a 16×16 MNIST subset (2707 samples)
- Dimensionality reduction and visualization
- Distance-based classifiers (nearest-neighbour variants)
- Building a neural network from scratch for the XOR problem
 

 
### `MLPs_CNNs_GANs/`
Hands-on with Keras/TensorFlow: building and comparing deep network architectures for classification, regression, and image generation.
 
**Topics covered:**
- MLP and CNN architectures for image classification
- Hyperparameter tuning and performance comparison
- CNN for the "tell-the-time" regression problem
- Generative models (VAE / GAN) with latent-space experiments
 

 
### `RNNs/`
Sequence-to-sequence modelling with encoder-decoder RNNs, applied to arithmetic and MNIST-based inputs.
 
**Topics covered:**
- Encoder-decoder RNN architecture
- Text-to-text sequence mapping (integer arithmetic: e.g. `81+24` → `105`)
- Multi-modal input: MNIST handwritten digits as alternative query representation
- Generalisation with limited training data
 

 
## Requirements
 
- Python 3.8+
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib, scikit-learn
- Jupyter Notebook 
Install dependencies:
```bash
pip install tensorflow numpy pandas matplotlib scikit-learn jupyter
```
