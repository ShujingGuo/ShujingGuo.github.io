---
layout: archive
title: "Research Experience"
permalink: /research_experience/
author_profile: true
---

{% include base_path %}

Unsupervised Image Captioning
======
* New Idea based on Object-Centric Unsupervised Image Captioning, 04/2023 - Present
  * Proposed a novel transformer-based network for unsupervised image captioning which utilizes unpaired images and texts to train the model, and can effectively boost the object coverage of input image features.
  * Mined images from the MS-COCO dataset which not only have the higher similarities to the given sentences but also contain certain objects corresponding to the sentences.
  * Proposed a feature extension network to expand the few object regions extracted from the mined images and to mimic complete region features extracted from real images’ visual contents.
  * Fed the expanded region features into the transformer network for generating predicted sentences.
  * The Feature Extension Network has already been trained and is trying to be embedded in the original network.

Supervised Image Captioning
======
* Fusion Transformer for Image Captioning, 02/2022 - 09/2022
  * Proposed a novel Fusion Transformer network to fuse two types of visual features (region and grid features) considering directional relationships between objects. This network effectively captures both high-level and fine-grained details in the images for purpose of generating more reasonable sentences.
  * Proposed a modified Multi-Head Self-Attention which simultaneously contains relative directional relations, absolute and relative positional information to enhance the orientation perception between visual features.
  * Applied a Fusion Attention to thoroughly integrate the two types of visual features with word representations in an interlaced way.
  * Employed a Fusion Gate Operation module to provide sophisticated control for the forward propagation of multimodal information as well as their backpropagating gradients.

* Further Improvement for Fusion Transformer, 09/2022 - 01/2023
  * Utilized segmentation features to substitute for the original region features as another visual information source. The segmentation features retain the spatial structure information of the original images and are easier to be fused with the grid features.
  * The other modules in the network remain unchanged.
  * Performed competitively on various evaluation metrics, e.g., 134.7 CIDEr on COCO Karpathy test split.
