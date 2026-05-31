# Early-Parkinson-s-Disease-Detection-using-1D-Deep-Shape-Descriptor-Network-1D-DSDNet-
This repository presents a deep learning framework for the early detection of Parkinson's Disease (PD) using DaTSCAN SPECT images from the Parkinson's Progression Markers Initiative (PPMI) dataset.

The proposed approach extracts shape-based descriptors from segmented striatal regions and employs a 1D Convolutional Autoencoder (1D-CAE) integrated with Squeeze-and-Excitation (SE) attention blocks to learn compact and discriminative latent representations. The learned features are subsequently classified using a Multi-Layer Perceptron (MLP) for Parkinson's Disease diagnosis.

Key Features
Automated shape-based analysis of striatal regions from SPECT scans
1D CNN Autoencoder for non-linear feature representation learning
SE Attention Modules for channel-wise feature refinement
Multi-task learning with reconstruction and classification objectives
Early PD vs Healthy Control classification
Early PD vs SWEDD classification
Evaluation on the PPMI DaTSCAN SPECT dataset
Methodology
Slice Selection and Intensity Normalization
Striatal Segmentation using Active Contours
Extraction of Shape Descriptors
Feature Learning using 1D CNN Autoencoder
Channel Attention using SE Blocks
MLP-based Classification
Joint Optimization using Reconstruction and Classification Losses
Dataset

The model is evaluated on the Parkinson's Progression Markers Initiative (PPMI) dataset consisting of:

Parkinson's Disease (PD): 947 subjects
Healthy Controls (HC): 184 subjects
SWEDD: 137 subjects

Total Subjects: 1268

Applications
Early Parkinson's Disease diagnosis
Computer-aided clinical decision support
Differentiation between PD and SWEDD subjects
Neurodegenerative disease research
