# MINT-RVAE Dataset for Multimodal Intent Prediction in Human–Robot Interaction

This repository contains the dataset accompanying the paper:

**MINT-RVAE: Multi-Cues Intention Prediction of Human-Robot Interaction using Human Pose and Emotion Information from RGB-only Camera Data**  

---

## Overview
We introduce a dataset of extracted features for frame-level human–robot interaction (HRI) intent prediction.  
- Data were collected across three different indoor environments.
- Each frame is annotated with a binary intent labe (`intent` vs. `no intent`).  
- Each feature vector contains:  
  - 2D human pose coordinates and detector confidence score (keypoints extracted from RGB frames)  
  - Facial emotion embeddings 
- The dataset is provided as `.npz` files, containing only de-identified extracted features.  
- No raw video or personally identifying information is released.  




 
 
