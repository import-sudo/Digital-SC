# Digital-SC

# Digital-SC: Digital Semantic Communication Framework

This repository provides the official implementation of **Digital-SC**, a digital semantic communication framework based on deep learning. The system encodes and transmits task-oriented semantic information using a digital communication scheme, optimizing for both semantic fidelity and channel robustness.

## 🔍 Overview

Traditional semantic communication systems transmit symbols in an analog fashion, but it poses new challenges to hardware, protocol, and encryption. **Digital-SC** introduces a  digital semantic communication system, where a novel non-linear quantization module is used to efﬁciently quantize semantic features with trainable quantization levels.

The Class **Quantization** in this code can be applied to various tasks such as image classification, visual question answering (VQA), and captioning over wireless channels.

## ✨ Features

- Semantic encoder-decoder structure optimized for digital transmission.
- Channel simulation module (e.g., AWGN, Rayleigh fading).
- Support for downstream tasks (e.g., classification, VQA, reconstruction).
- Plug-and-play training and evaluation scripts.

## 🧠 Citation
If you use this code in your research, please cite:
@ARTICLE{10772628,
  author={Guo, Lei and Chen, Wei and Sun, Yuxuan and Ai, Bo},
  journal={IEEE Transactions on Cognitive Communications and Networking}, 
  title={\protect{Digital-SC}: Digital Semantic Communication With Adaptive Network Split and Learned Non-Linear Quantization}, 
  year={2024},
  doi={10.1109/TCCN.2024.3510586}}
