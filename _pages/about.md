---
permalink: /
title: "Direct RGB-D Visual Odometry via Gaussian Gradient Features"
excerpt: "prePrint"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Abstract
---
Point-wise tracking in either geometric or photometric paradigm greatly relied on pixel saliency in a local region or a sub-window, where the former requires reliable feature detection and the latter is prone to suffer from redundancies, especially for dense tracking. To estimate a rigid-body motion, in addition, target points evenly distributed in the image plane are preferred due to transformations or distortions in projections. Inspired by existing studies, this paper gives a direct Visual Odometry (VO) of RGB-D cameras by using features measured by low-order Gaussian derivative functions such as Gaussian gradient operator which is commonly known as a band pass filter enables removing significantly image spatial redundancies whereas could remain certain correlations between adjacent pixels. By filtering the image with such a local contrast feature metric, it improves further the possibility for sampling more reliable points from scenarios that are lack of structure or texture and is beneficial to continuous tracking. Without elaborating optimization or hybrid Jacobian computation, the proposed approach reaches relatively acceptable performance with a globally heuristic framework built on the general coarse-to-fine and inverse compositional estimation. To evaluate its validity in direct VO, comparative study of this work is conducted via several experimental results on a group of TUM datasets.

Download: [Direct RGB-D Visual Odometry via Gaussian Gradient Features .pdf file.](../020700564800ImagePDF.pdf)
