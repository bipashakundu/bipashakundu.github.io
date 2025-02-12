---
title: "Multi-Scale Feature Fusion with Image-Driven Spatial Integration for Left Atrium Segmentation from Cardiac MRI Images"
excerpt: " <br/><img src='/images/model.png'>


Accurate segmentation of the left atrium (LA) from late gadolinium-enhanced magnetic resonance imaging plays a vital role in visualizing diseased atrial structures, enabling the diagnosis and management of cardiovascular diseases. It is particularly essential for planning treatment with ablation therapy, a key intervention for atrial fibrillation (AF). However, manual segmentation is time-intensive and prone to inter-observer variability, underscoring the need for automated solutions. Class-agnostic foundation models like DINOv2 have demonstrated remarkable feature extraction capabilities in vision tasks. However, their lack of domain specificity and task-specific adaptation can reduce spatial resolution during feature extraction, impacting the capture of fine anatomical detail in medical imaging. To address this limitation, we propose a segmentation framework that integrates DINOv2 as an encoder with a UNet-style decoder, incorporating multi-scale feature fusion and input image integration to enhance segmentation accuracy. The learnable weighting mechanism dynamically prioritizes hierarchical features from different encoder blocks of the foundation model, optimizing feature selection for task relevance. Additionally, the input image is reintroduced during the decoding stage to preserve high-resolution spatial details, addressing limitations of downsampling in the encoder. We validate our approach on the LAScarQS 2022 dataset and demonstrate improved performance with a 92.3% Dice and 84.1% IoU score for giant architecture compared to the nnUNet baseline model. These findings emphasize the efficacy of our approach in advancing the field of automated left atrium segmentation from cardiac MRI."

collection: portfolio
---

<!-- This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML.  -->
