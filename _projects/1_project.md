---
layout: page
title: event identification
description: A Machine Learning Framework for Event Identification via Modal Analysis of PMU Data
img: 
importance: 1
category: work
---

Power systems are prone to a variety of events (e.g. line trips and generation loss) and real-time identification of such events is crucial in terms of situational awareness, reliability, and security. Using measurements from multiple synchrophasors, i.e., phasor measurement units (PMUs), we propose to identify events by extracting features based on modal dynamics. 
We combine such traditional physics-based feature extraction methods with machine learning to distinguish different event types. Including all measurement channels at each PMU allows exploiting diverse features but also 
requires learning classification models over a high-dimensional space. 
To address this issue, various feature selection methods are implemented to choose the best subset of features.
Using the obtained subset of features, we investigate the performance of two well-known classification models, namely, logistic regression (LR) and support vector machines (SVM) to identify generation loss and line trip events in two datasets. The first dataset is obtained from simulated generation loss and line trip events in the Texas 2000-bus synthetic grid.
The second is a proprietary dataset with labeled events obtained from a large utility in the USA involving measurements from nearly 500 PMUs. 
Our results indicate that the proposed framework is promising for identifying the two types of events.

**Acknowledgments:**
This material is based upon work supported by the National Science Foundation  under  Grants  OAC-1934766, CCF-2048223, and CCF-2029044, and the Power System Engineering Research Center (PSERC) under projects S-87.

<a href="https://ieeexplore.ieee.org/document/9911774">Link to the paper</a>