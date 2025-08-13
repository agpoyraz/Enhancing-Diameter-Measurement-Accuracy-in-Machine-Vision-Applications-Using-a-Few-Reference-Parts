# Enhancing-Diameter-Measurement-Accuracy-in-Machine-Vision-Applications-Using-a-Few-Reference-Parts
In this work, instead of calculating the mm/px conversion factor from only a single reference part, we use multiple reference parts to build a more robust and adaptive model. The conversion factor values obtained from these parts are used to construct a parametric model, resulting in a variable conversion factor. This approach allows us to minimize measurement errors that occur across different diameters by leveraging just a few reference parts.

The methodology is based on the approach proposed by Ahmet Gökhan Poyraz et al., presented in the arXiv preprint Enhancing Diameter Measurement Accuracy in Machine Vision Applications Using a Few Reference Parts (arxiv.org/abs/2508.03721). The paper highlights the benefits of calculating the mm/px conversion using several reference parts instead of one.

Experimental results demonstrate that using multiple reference parts, rather than a single one, can reduce measurement errors from the initial range of 13–114 µm down to 1–2 µm in both glass and metal test samples. This provides not only improved accuracy but also a flexible, parameter-model-based measurement system.

- **Multiple reference parts** are used for mm/px conversion instead of relying on a single part, resulting in a more general and precise model.
- Different diameter measurements from reference parts are used to build a **parametric model**, enabling a **dynamic conversion factor** in real time.
- This method significantly reduces potential measurement errors — from **13–114 µm** down to **1–2 µm** in our experiments with glass and metal samples.
- The approach offers **high precision and flexibility** for industrial measurement systems.
- Reference: Poyraz et al., *Enhancing Diameter Measurement Accuracy in Machine Vision Applications Using a Few Reference Parts*, arXiv preprint, July 28, 2025.  
  [arxiv.org/abs/2508.03721](https://arxiv.org/abs/2508.03721)
  
Poyraz, Ahmet Gokhan, et al. "Enhancing Diameter Measurement Accuracy in Machine Vision Applications." arXiv preprint arXiv:2508.03721 (2025).
