# PmiBiCGR-CapsNet
A dual-channel CGR Capsule Network for plant miRNA promoter prediction
Official implementation of the paper:

"基于正逆序CGR与双通道重建胶囊网络的miRNA启动子预测方法" 
(PmiBiCGR-CapsNet: A Bidirectional CGR and Dual-Channel Reconstruction Capsule Network for Plant miRNA Promoter Prediction)

# Overview

PmiBiCGR-CapsNet is a deep learning framework for plant miRNA promoter prediction. The model employs:

- Bidirectional Chaos Game Representation (CGR) – encoding both forward and reverse DNA sequences into dual-channel images.
- Capsule Network – using vector neurons and dynamic routing to model part-whole relationships.
- Dual-Channel Reconstruction Decoder – applying self-supervised regularization to compensate for CGR rasterization loss.
- Layer-wise Initialization – Kaiming initialization for ReLU layers and Xavier initialization for Sigmoid layers.
