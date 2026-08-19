# MI-BCI Code Repositories

This section provides links to publicly available code repositories related to motor imagery brain-computer interfaces (MI-BCI), EEG preprocessing, deep learning architectures, feature extraction, and efficient/embedded implementation.

The repositories are included as reference implementations for methods discussed in the review and may be useful for reproduction, comparison, and further development.

## 1. MI-BMInet — Efficient CNN for MI-BCI

Repository:\
[MI-BMInet — GitHub](https://github.com/pulp-platform/MI-BMInet)

Paper:\
Wang, X., Hersche, M., Magno, M., & Benini, L. (2024). *MI-BMInet: An Efficient Convolutional Neural Network for Motor Imagery Brain–Machine Interfaces With EEG Channel Selection. IEEE Sensors Journal, 24(6), 8835–8847.[10.1109/JSEN.2024.3353146](https://doi.org/10.1109/JSEN.2024.3353146)

### Summary

MI-BMInet is an efficient convolutional neural network developed specifically for motor imagery EEG-based brain-machine interfaces. The repository covers the development pipeline from model training through quantization and deployment on resource-constrained hardware.

## 2. CSP-Based CDF Filtering

Repository:\
[CSP-based CDF Filtering — GitHub](https://github.com/Ardalan-Faezmehr/CSP_based_CDF_Filtering)

Paper

*Designing class discrepancy-guided sub-band filter using common frequency pattern for preprocessing EEG signals in MI-BCIs.*

### Summary

This repository provides code for an EEG preprocessing approach based on class-discrepancy-guided sub-band filtering and Common Spatial Pattern (CSP)-related processing.


## 3. TSFF — Time-Space-Frequency Feature Fusion

Repository:\
[TSFF — GitHub](https://github.com/MiaoZhengQing/TSFF)

Paper:\
Miao, Z., & Zhao, M. (2023). *Time-space-frequency feature Fusion for 3-channel motor imagery classification*. arXiv:2304.01461.
[arXiv:2304.01461](https://arxiv.org/abs/2304.01461)

### Summary

TSFF implements a **time-space-frequency feature fusion** approach for motor imagery classification using EEG signals.


## 4. FSTA-Net — Frequency-Spatial-Time Attention Network

**Paper: 
Li, W., Ma, Y., Qin, P., Wang, X., Yi, Z., Shao, K., & Wu, X. (2024). *FSTA-Net: Motor Imagery EEG Decoding Based on Frequency-Spatial-Time Features*. IEEE Sensors Journal, 24(15), 24031–24043. [10.1109/JSEN.2024.3403875](https://doi.org/10.1109/JSEN.2024.3403875)

### Summary

FSTA-Net is a deep-learning framework for **frequency-spatial-time (FST) feature extraction** in motor-imagery EEG decoding. It first uses **short-time Fourier transform (STFT)** to obtain time-frequency representations and then applies covariance operations to the time segments. The proposed network combines a **frequency-spatial attention module**, a **time-domain attention module**, and a classification network. A time-domain translation augmentation strategy is also introduced to reduce overfitting.

## 5. RCSP — Regularized Common Spatial Pattern

**RCSP Toolbox:**  
[Fabien Lotte — RCSP Toolbox](https://sites.google.com/site/fabienlotte/research/code-and-softwares)

**R-CSP-A MATLAB implementation:**  
[Regularized Common Spatial Pattern with Aggregation — MATLAB File Exchange](https://www.mathworks.com/matlabcentral/fileexchange/35734-regularized-common-spatial-pattern-with-aggregation-r-csp-a-for-eeg-classi-cation)

**Paper:**  
Lu, H., Eng, H.-L., Guan, C., Plataniotis, K. N., & Venetsanopoulos, A. N. (2010). *Regularized Common Spatial Pattern with Aggregation for EEG Classification in Small-Sample Setting*. **IEEE Transactions on Biomedical Engineering, 57(12), 2936–2946.**

**DOI:**  
[10.1109/TBME.2010.2082540](https://doi.org/10.1109/TBME.2010.2082540)

### Summary

Regularized Common Spatial Pattern (RCSP) extends conventional CSP by introducing **regularization into covariance estimation/spatial-filter optimization**, helping reduce estimation variance and overfitting when the available EEG training data are limited. R-CSP-A further aggregates multiple regularized CSP solutions. The approach is particularly relevant to **small-sample MI-BCI classification and robust spatial feature extraction**.

## 6. Covariance Toolbox

**GitHub:**  
[Covariance Toolbox — Alexandre Barachant](https://github.com/alexandrebarachant/covariancetoolbox)

### Summary

The Covariance Toolbox is a **MATLAB toolbox for covariance-matrix processing and Riemannian geometry**, developed for applications including EEG-based brain-computer interfaces. It provides tools for working with covariance matrices and Riemannian methods and has been used in EEG/BCI research involving covariance-based representations and transfer learning.

The toolbox is particularly relevant to:

- Covariance-matrix estimation
- Riemannian geometry
- EEG/BCI signal processing
- Spatial feature representations
- Transfer learning and domain adaptation

## 7. LMDA-Net — Lightweight Multi-Dimensional Attention Network

**Code:**  
[LMDA-Code — GitHub](https://github.com/MiaoZhengQing/LMDA-Code)

**Paper:**  
Miao, Z., Zhao, M., Zhang, X., & Ming, D. (2023). *LMDA-Net: A lightweight multi-dimensional attention network for general EEG-based brain-computer interfaces and interpretability*. **NeuroImage, 276, 120209.**

**DOI:**  
[10.1016/j.neuroimage.2023.120209](https://doi.org/10.1016/j.neuroimage.2023.120209)

### Summary

LMDA-Net is a **lightweight deep neural network for EEG-based BCI decoding** that introduces two EEG-oriented attention mechanisms: a **channel attention module** and a **depth attention module**. These modules integrate information across multiple dimensions while maintaining a relatively lightweight architecture.


