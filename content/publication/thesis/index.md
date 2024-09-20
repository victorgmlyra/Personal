---
title: Semantic Reconstruction of Aircraft from Incomplete LiDAR Data
authors:
- Victor Gouveia De M. Lyra
date: '2024-08-12'
publication_types:
- Master Thesis
publication: 'Danmarks Tekniske Universitet (DTU)'
abstract: | 
  To enhance the process of automating airplane deicing. This thesis presents a machine-learning approach for generating complete and contextualized 3D representations of airplanes from partial LiDAR scans by predicting the entire geometry of an aircraft and providing semantic information about its different parts, such as wings, body, tail, and turbines. The proposed solution integrates deep learning techniques to streamline the aircraft scanning part of the autonomous deicing process, thus improving its efficiency.

  This study investigates two primary approaches to semantic point cloud completion: a sequential model using separate networks for point cloud completion and segmentation (PoinTr+Next), and a unified model that combines both tasks within a single network (PoinTrSeg). I modified the PoinTr architecture by incorporating skip connections to enhance completion performance and introduced a novel segmentation head to facilitate simultaneous completion and segmentation. I evaluated these models using synthetic data from the ShapeNet and ShapeNetPart datasets and real-world airplane scans.

  The results indicate that the PoinTrSeg model achieves comparable completion quality to the sequential approach while significantly improving segmentation accuracy. The PoinTrSeg model also demonstrates a 35% faster inference time, making it more suitable for real-time applications. However, both models exhibit limitations when applied to real-world data, highlighting the challenge of bridging the gap between synthetic and real-world environments.

  This thesis contributes to the field by demonstrating the feasibility and advantages of integrating point cloud completion and segmentation into a single model, enhancing performance and efficiency. It provides a foundation for further research and development in real-time, robust 3D point cloud processing for various applications.

links:
- name: URL
  url: https://findit.dtu.dk/en/catalog/66cbc7ece9b650204c544c32

featured: true
---
