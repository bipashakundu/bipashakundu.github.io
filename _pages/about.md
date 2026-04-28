---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
I am a 4th year Ph.D. student in Imaging Science at Rochester Institute of Technology (RIT), working as a Research Assistant at the BiMVisIGN Lab. My research sits at the intersection of medical image analysis, deep learning, and computer vision, with a primary focus on cardiac MRI, specifically the left atrium (LA).
My work spans automatic segmentation, deformable image registration, cardiac motion estimation, and vision-language model evaluation for clinically grounded image quality assessment. I am passionate about building robust, data-efficient deep learning pipelines that can directly support clinical decision-making — particularly for patients undergoing ablation therapy for atrial fibrillation (AF).

Prior to RIT, I earned my M.S. in Electrical Engineering from the University of Minnesota Duluth and my B.S. in Electronics & Communication Engineering from Khulna University of Engineering & Technology, Bangladesh. I have also gained industry experience as a Pre-Sales Engineer and Power & Infrastructure Specialist at multinational telecommunications companies in Bangladesh.


<!-- I am a 4th year Ph.D. student in Imaging Science with a focus on Medical Image Analysis using machine learning (ML) and deep learning (DL) algorithms. Currently, I am also a Research Assistant at BiMVisIGN Lab. I have experienced developing and fine- tuning deep learning for multi-modal medical images to improve automatic semantic and instance segmentation accuracy, and deformable registrations. I completed my MSEE from University of Minnesota Duluth, USA and undergrad from Khulna University of Engineering & Technology, Bangladesh. -->


## Research ##
The heart is one of the most complex and dynamic organs to image — and yet, accurate analysis of cardiac MRI is critical for millions of patients living with atrial fibrillation. My doctoral work is driven by a simple but ambitious question: how can we teach machines to see and understand the heart the way a skilled cardiologist does?

I work at the intersection of deep learning, computer vision, and cardiac imaging, building computational tools that help clinicians plan and evaluate ablation therapy,  a procedure used to treat atrial fibrillation by deliberately creating small scars in heart tissue to disrupt abnormal electrical signals. Getting this right matters enormously: too little ablation leaves the arrhythmia untreated; too much damages healthy tissue. My research aims to give clinicians better, faster, and more reliable information at every stage of this process.


A central challenge I tackle is the left atrium segmentation problem — precisely delineating the left atrium from LGE-MRI scans, which are notoriously difficult to interpret due to low contrast, imaging artifacts, and high variability across patients. I have explored how large-scale vision foundation models, including self-supervised Vision Transformers like DINOv2, can be adapted to this task without requiring massive amounts of labeled medical data. 

A second thread of my research asks: can we infer what a heart is doing from a single static image? Through cardiac motion estimation, I developed a framework that extracts motion patterns of the left atrium across the cardiac cycle, using those patterns as a signal to detect and localize scar tissue — even from images that capture just one frozen moment in time. This work was recognized as an oral presentation at SPIE Medical Imaging 2026

I have also worked on automated image quality assessment for LGE-MRI, recognizing that even the best segmentation model will fail if fed a poor-quality scan. By evaluating vision-language models for this task, I aim to create an early filter in the clinical pipeline that flags problematic acquisitions before they influence downstream analysis. I am currently exploring the integration of vision-language frameworks into the segmentation pipeline, with the goal of leveraging semantic and textual supervision to produce anatomically consistent, clinically interpretable delineations of the left atrium.

## News ##

- Our paper **"A Two Stage Pipeline for Left Atrial Wall Constrained Scar Segmentation and Localization from LGE-MR Images"** was accepted in EMBC 2026 (April 2026)

- Our paper **"Motion-Guided Scar Detection from Static Left Atrial MRI via Deformable Registration to a Healthy Atlas"** was accepted in SPIE Medical Imaging 2026 for Oral Presentation (October 2025)

- Our paper **“Multi-Scale Feature Fusion with Image-Driven Spatial Integration for Left Atrium Segmentation from Cardiac MR Images”** was accepted in EMBC 2025 (April 2025)

- Our paper **“Investigating the Domain Adaptability of General-Purpose Foundation Models for Left Atrium Segmentation from MR Images”** was accepted in Functional Imaging and Modeling of the Heart (FIMH) 2025 (April 2025)

- Attended SPIE Medical Imaging, 2025 to present our paper on **“Assessing the Performance of the DINOv2 Self-supervised Learning Vision Transformer Model for the Segmentation of the Left Atrium from MRI Images”**.

- Received Travel Award from RIT **Women in science (WISe)** program (December 2024)

- Our paper, **“Assessing the Performance of the DINOv2 Self-supervised Learning Vision Transformer Model for the Segmentation of the Left Atrium from MRI Images”** was accepted in SPIE Medical Imaging 2025 for Oral Presentation (October 2024)

- Our paper, **“Comparative analysis of non-rigid registration techniques for liver surface registration,”** was accepted in SPIE Medical Imaging, 2024 (October 2023)

- Passed Qualifying Exam (July 2023)

- Started Ph.D. in Imaging Science, Rochester Institute of Technology (August 2022)

- Started Ph.D. in Electrical Engineering, Texas Tech University (August 2021)

- Started MS in Electrical Engineering, University of Minnesota Duluth (August 2018)

- Joined Banglalink Digital Communications Ltd. as Power & Infrastructure Specialist (January 2018)

- Joined Express Systems Ltd. as Pre-sales Engineer (January 2016)

- Graduated (BSc in ECE) from Khulna University of Engineering & Technology (July 2015)
