# FQ-PETR: Fully Quantized Position Embedding Transformation for Multi-View 3D Object Detection

<p align="center">
    <a href="https://aaai.org/aaai-26/">🧠 AAAI 2026</a> • 
    <a href="https://arxiv.org/abs/2502.15488">📄 Paper (arXiv)</a> • 
    <a href="#citation">📚 Citation</a>
</p>

<p align="center">
    <img src="docs/assets/fqpetr_banner.png" width="70%">
</p>

---

### 🚧 Coming Soon

This repository will provide the **official implementation** of our AAAI 2026 paper:

> **FQ-PETR: Fully Quantized Position Embedding Transformation for Multi-View 3D Object Detection**  
> *Jiangyong Yu¹, Changyong Shu¹*, Sifan Zhou², Zichen Yu³, Xing Hu¹, Yan Chen¹, Dawei Yang¹*  
> ¹ Houmo AI, ² Southeast University, ³ Dalian University of Technology

Code, models, and documentation are being prepared.  
---

## 📋 Overview

**FQ-PETR** introduces the first fully-quantized framework for **multi-view 3D object detection** based on PETR.  
It features:

- 🔸 **Quantization-friendly position embedding transformation**  
- 🔸 **End-to-end INT8 pipeline** preserving detection accuracy  
- 🔸 **DULUT design** that abstracts nonlinear LUT allocation as a differentiable function and replaces it with a linear LUT, requiring **no dedicated hardware support** 
