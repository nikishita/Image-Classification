# Image-Classification


## Overview
This repository presents an improved strategy for enhancing face recognition accuracy by refining the "hard-negative sample selection" process during "Triplet Loss" training. Unlike conventional methods that discard certain sample pairs, our approach incorporates these pairs to improve performance. To prevent early convergence caused by additional training samples, we utilize the "Adaptive Moment Estimation (Adam)" optimization algorithm.

Our method achieves "0.968 accuracy" on the "OpenFace dataset", significantly outperforming traditional techniques like "Local Binary Pattern Histogram (LBPH)", which show relatively lower performance.

---

## Key Features
- Enhanced Hard-Negative Selection: Retains additional hard-negative pairs for optimized Triplet Loss training.  
- Adam Optimization: Mitigates the risk of early convergence during training.  
- State-of-the-Art Accuracy: Achieves 0.968 accuracy on OpenFace.  
- Comparison with Traditional Techniques: Highlights the performance gap between deep learning models and LBPH.  

---

## Requirements
The following libraries are required to run the code:

- Python 3.x  
- TensorFlow or PyTorch (any deep learning framework of choice)  
- NumPy  
- OpenCV  
- Matplotlib  
- Scikit-learn  

## Results 
The following table presents the comparison of accuracy between our proposed method and the baseline approach:

- OpenFace (Deep Learning) => 0.968
- LBPH (Traditional)	     => Lower Accuracy

The results demonstrate the significant improvement in accuracy achieved through our improved hard-negative sample selection strategy combined with Triplet Loss training.

