
# Image Deblurring using Blind Deconvolution 🎯

> MATLAB-based experiment demonstrating image restoration using **Blind Deconvolution**, including PSF size variation, edge-weighted deblurring, and constrained PSF restoration.

---

## 📋 Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Quick Start](#quick-start)
* [Results](#results)
* [Methodology](#methodology)
* [Evaluation Metrics](#evaluation-metrics)
* [Contact](#contact)

---

## 🎯 Overview

This project explores **image deblurring techniques** using MATLAB’s `deconvblind()` function.
It simulates motion blur on a sample image (`cameraman.tif`) and applies **Blind Deconvolution** under different PSF (Point Spread Function) conditions:

* Undersized, Oversized, and True-size PSFs
* Weighted deblurring (edge-based weighting)
* Constrained PSF restoration

**Category:** Image Processing
**Algorithm:** Blind Deconvolution
**Framework:** MATLAB + Image Processing Toolbox

---

## ✨ Features

* ✅ Simulate Gaussian blur with customizable PSF
* ✅ Compare different PSF sizes (under, over, true)
* ✅ Edge-based weighting for sharper restoration
* ✅ Constraint function for PSF optimization
* ✅ Quantitative evaluation: PSNR, SSIM, MSE
* ✅ Iteration-based quality analysis

---

## 🚀 Quick Start

### Run in MATLAB

```bash
# Clone repository
git clone https://github.com/Master-Megatron/matlab-image-deblurring.git
cd matlab-image-deblurring
```

### Execute

```matlab
run('deblurring_demo.m')
```

Observe visual results and evaluation metrics directly in MATLAB figures and console output.

---

## 📊 Results

### Evaluation Example

```
=== Evaluasi Hasil Deblurring ===
Step 5 (Weighted):     PSNR = 28.34 dB, SSIM = 0.8421, MSE = 0.0034
Step 6 (Constrained):  PSNR = 29.72 dB, SSIM = 0.8617, MSE = 0.0028
```

### Key Observations

* Weighted deblurring improves sharpness and PSNR.
* Constrained PSF yields best overall performance.
* Optimal iteration range found between **30–60**.

---

## 🔬 Methodology

1. **Read Original Image** (`cameraman.tif`)
2. **Simulate Blur** using Gaussian PSF
3. **Apply Blind Deconvolution** with varying PSF sizes
4. **Edge-weighted Deblurring** for enhanced accuracy
5. **Constraint-based Deblurring** to refine PSF
6. **Evaluate and Compare** using PSNR, SSIM, MSE
7. **Analyze Iterations** to find optimal convergence

---

## 📈 Evaluation Metrics

| Metric   | Description                                           |
| -------- | ----------------------------------------------------- |
| **PSNR** | Measures reconstruction quality (higher is better)    |
| **SSIM** | Measures structural similarity (closer to 1 = better) |
| **MSE**  | Measures pixel-wise error (lower is better)           |

---

## 👤 Contact

**Author:** Master Megatron

* GitHub: [@Master-Megatron](https://github.com/Master-Megatron)
* Email: [megatronelectronicmail@gmail.com](mailto:megatronelectronicmail@gmail.com)

---

## ⭐ If you found this helpful, please star this repository!

---

**Last Updated:** November 2025
**Status:** ✅ Active

---
