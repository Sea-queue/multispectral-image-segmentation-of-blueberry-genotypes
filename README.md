# Multispectral Image(MSI) Segmentation of Blueberry Genotypes

MSI captures unique reflectance patterns across wavelengths and has strong potential for early detection of crop stress and disease. Our goal is to segment blueberry genotypes from drone images captured by a MicaSense camera to support expert field analysis.
<p align="center">
  <img src="images/tells_more.png" alt="Example" width="60%">
</p>

---

## 📌 Overview

- Tested several RGB-based models, including the Segment Anything Model(SAM) and a pretrained UNet that used three-channel pseudo-RGB composites derived from PCA.
- Annoted 50 Blueberry field RGB images.
- Overfitted YOLO11 Segmentation Model to see the feasibility.

---

## 🎬 Raw MSI
<p align="center">
  <img src="images/IMG_0222_1.png" alt="img1" width="18%" />
  <img src="images/IMG_0222_2.png" alt="img2" width="18%" />
  <img src="images/IMG_0222_3.png" alt="img3" width="18%" />
  <img src="images/IMG_0222_4.png" alt="img4" width="18%" />
  <img src="images/IMG_0222_5.png" alt="img5" width="18%" />
</p>

---

## 🎬 RGB after MicaSense Alignment
<p align="center">
  <img src="images/IMG_0222_rgb.png" alt="img1" width="25%" />
  <img src="images/IMG_0008_rgb.png" alt="img2" width="25%" />
  <img src="images/IMG_0187_rgb.png" alt="img3" width="25%" />
</p>

---

## 🎬 Annotation
<p align="center">
  <img src="images/annotation_0222.png" alt="img1" width="25%" />
  <img src="images/annotation_0008.png" alt="img1" width="25%" />
  <img src="images/annotation_0187.png" alt="img1" width="25%" />
</p>


---

## 🎬 Model Predictions
<p align="center">
  <img src="images/pca_unet_out.png" alt="img1" width="25%" />
  <img src="images/SAM_mask.png" alt="img1" width="25%" />
  <img src="images/SAM_everything.png" alt="img1" width="25%" />
</p>



