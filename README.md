# Feature Descriptors & Feature Matching (SIFT / ORB / SURF)

This repository contains a Computer Vision lab implementation of classical feature descriptors and feature matching using OpenCV.

## Algorithms Implemented
- **SIFT** (Scale-Invariant Feature Transform)
- **ORB** (Oriented FAST and Rotated BRIEF)
- **SURF** (optional, may not work in standard OpenCV builds)

## Matching Pipeline
- Keypoint detection + descriptor extraction
- **BFMatcher**
- **KNN Matching (k=2)**
- **Lowe’s Ratio Test**
- Match visualization using `drawMatches`
- (Optional) Homography estimation using **RANSAC**

## Requirements
Install dependencies:

```bash
pip install -r requirements.txt
