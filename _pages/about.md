---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a fifth-year Ph.D. student in the School of Computer Science and Technology at University of Science and Technology of China. I am very fortunate to be advised by professor [Xiang-yang Li](http://staff.ustc.edu.cn/~xiangyangli/) and professor [Lan Zhang](https://scholar.google.com/citations?user=83QxmA8AAAAJ&hl=en). 
We work on mobile computing, human interaction, and GIS management. 
I recieved my Bachelor’s degree in Computer Science and Technology from the Special Class for the Gifted Young, University of Science and Technology of China in 2018.


Recent News
------


Publications
------
1. **ANTIGONE: Accurate Navigation Path Caching in Dynamic Road Networks leveraging Route APIs.** 
<small> (INFOCOM 2022) [Paper](https://ieeexplore.ieee.org/abstract/document/9796817) </small>
: **Xiaojing Yu**, Xiang-Yang Li, Jing Zhao, Guobin Shen, Nikolaos M. Freris, Lan Zhang. 
: Navigation paths and corresponding travel times play a key role in location-based services (LBS) of which large-scale navigation path caching constitutes a fundamental component. In view of the highly dynamic real-time traffic changes in road networks, the main challenge amounts to updating paths in the cache in a fashion that incurs minimal costs due to querying external map service providers and cache maintenance. In this paper, we propose a hybrid graph approach in which an LBS provider maintains a dynamic graph with edge weights representing travel times, and queries the external map server so as to ascertain high fidelity of the cached paths subject to stringent limitations on query costs. We further deploy our method in one of the biggest on-demand food delivery platforms and evaluate the performance against state-of-the-art methods. Our experimental results demonstrate the efficacy of our approach in terms of both substantial savings in the number of required queries and superior fidelity of the cached paths.
2. **Thumbup: Identification and Authentication by Smartwatch using Simple Hand Gestures.** 
<small> (PerCom 2020) [Paper](https://www.computer.org/csdl/proceedings-article/percom/2020/09127367/1l3yJSxjyqQ) </small>
:  **Xiaojing Yu**, Zhijun Zhou, Mingxue Xu, Xuanke You, Xiang-Yang Li.
: The widespread creative application and smart devices call for convenient and secure interaction with human users. We propose, design, and implement a smartwatch-based two-factor real-time identification and authentication system named ThumbUp, where smartwatch users can identify and authenticate themselves by some simple hand and finger gestures, such as thumb-up. ThumbUp leverages the signal collected from the Inertial Measurement Unit (IMU) in Commercial Off-The-Shelf (COTS) smart devices and discovers the unique fingerprint pattern produced by each user’s simple hand gestures using a carefully crafted deep learning model. We implement our system and conduct extensive experiments to evaluate its efficacy and efficiency with 65 different users over a period of more than 3 months. It reaches an accuracy of 97% for identification, and EER 0.014 for authentication using only one simple gesture. We also survey the users’ acceptance of our system and discuss how the proficiency of gestures affects authentication accuracy.
3. **XHAR: Deep Domain Adaptation for Human Activity Recognition with Smart Devices.** 
<small> (SECON 2020) [Paper](https://ieeexplore.ieee.org/abstract/document/9158431) </small>
:  Zhijun Zhou, Yingtian Zhang, **Xiaojing Yu**, Panlong Yang, Xiang-Yang Li, Jing Zhao, Hao Zhou
: To further improve the convenience and effectiveness of human computer interaction (HCI) with smart devices, human activity recognition (HAR) has been widely studied from various aspects. Unfortunately, deep learning based methods often suffer from either expensive labeling efforts or weak generalization ability. Inspired by recently developed domain adaptation strategies, we propose XHAR, a novel adversarial deep domain adaptation framework for HAR using smart devices, providing better device and user adaptation. XHAR first selects the most similar source dataset (with label), then extracts device and user independent spatial-temporal features through the combinations of Convolutional Neural Networks (CNN) and Bidirectional Gated Recurrent Units (BiGRU) feature extractors. Moreover, it removes the distribution discrepancy using multiple domain discriminators, and finally performs adaptation on the target dataset (without label) to obtain the predicted labels. We conduct extensive experiments on 50 users (i.e., of different ages, genders, and body shapes) and 4 smart devices with two kinds of datasets (i.e., gesture activities and sport activities). We compare our method with the source-only model and several state-of-the-art domain adaptation models. The results show that XHAR increases the classification accuracy by at least 4.81% (to 74.50%) on the adaptation between different users, and accordingly by at least 9.25% (to 69.23%) between different devices.
4. **Entropy Repulsion for Semi-supervised Learning Against Class Mismatch.** 
<small> (PerCom 2020) [Paper](https://ieeexplore.ieee.org/abstract/document/9158431) </small>
:  Xuanke You, Lan Zhang, Linzhuo Yang, **Xiaojing Yu**, Kebin Liu
: A series of semi-supervised learning (SSL) algorithms have been proposed to alleviate the need for labeled data by leveraging large amounts of unlabeled data. Those algorithms have achieved good performance on standard benchmark datasets, however, their performance can degrade drastically when there exists a class mismatch between the labeled and unlabeled data, which is common in practice. In this work, we propose a new technique, entropy repulsion for mismatch (ERCM), to improve SSL against a class mismatch situation. Specifically, we design an entropy repulsion loss and a batch annealing and reloading mechanism, which work together to prevent potentially mismatched unlabeled data from participating in the early training stages as well as facilitate the minimization of the unsupervised loss term of traditional SSL algorithms. ERCM can be adopted to enhance existing SSL algorithms with minor extra computation cost and no change to their network structures. Our extensive experiments demonstrate that ERCM can significantly improve the performance of state-of-the-art SSL algorithms, namely Mean Teacher, Virtual Adversarial Training (VAT) and Mixmatch in various class-mismatch cases.
