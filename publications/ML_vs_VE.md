---
author: Bree Jones, Mathias Lambach, <b>Tong Chen</b>, Stavroula Michou, Nicky Kilpatrick, David P. Burgner, Christoph Vannahme, Mihiri Silva
date: 2025-06-16
title: "Dental caries detection in children using intraoral scans and deep learning"
details: <em>Journal of Dentistry</em> 
doi: 10.1016/j.jdent.2025.105906
categories: Applications
---

<b>Objective</b>: This study aimed to demonstrate the use of deep learning for automating caries detection using intraoral scan data from children and to evaluate diagnostic agreement between the models’ predictions and dental practitioner assessments on 3D models.

<b>Methods</b>: Intraoral scans were collected from two cohorts at Murdoch Children’s Research Institute. Two researchers annotated scan meshes using the International Caries Classification and Management System. A pre-processing pipeline converted the 2.5D data into a 2D format. Carious teeth from the first cohort (n=332) were split at the participant level into training (n=192), validation (n=63), and test (n=77) sets. An Attention U-Net was trained to classify initial, moderate, and extensive dental caries. Performance was evaluated on the test set using the Intersection over Union (IoU), Sensitivity (SE), Specificity (SP), and Precision (P), reported for both pixel-wise segmentation and lesion detection. Carious teeth from the second independent cohort (n=119) were used for external validation. Multilevel logistic regression assessed diagnostic agreement to compare the model performance to dental practitioners across all caries thresholds (initial, moderate and extensive).

<b>Results</b>: segmentation tasks, the model had the best performance for extensive caries (SE 71%, P 66%, IOU 0.55), and showed overall promising performance for lesion detection (SE 67%, P 73%). Performance slightly declined on an external dataset. Diagnostic agreement between the model and dental practitioners was comparable across all disease thresholds: initial (odds ratio OR 0.82, 95% Confidence Interval (CI) 0.6–1.15), moderate (OR 0.9, 95% CI 0.5-1.6) and extensive (OR 0.85, 95% CI 0.42–1.71).

<b>Conclusion</b>: The proof-of-concept demonstrates that deep learning can achieve moderate performance moderate performance in detecting extensive caries from intraoral scans, though performance was limited for early and moderate lesions. Further research is needed to improve model accuracy and generalisability across all disease stages.

<b>Clinical Significance</b>: This study represents an exploratory effort towards developing AI-assisted caries detection using intraoral scanner data in children. While the long-term potential of such technology could include support for early diagnosis, enhanced caries monitoring, and a reduction in the subjectivity of caries assessment, our current findings indicate that significant model refinement and extensive validation are imperative, especially for the detection of initial carious lesions, before such clinical applications can be realized.