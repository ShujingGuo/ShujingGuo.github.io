---
layout: archive
title: "Research Experience"
permalink: /research_experience/
author_profile: true
---

{% include base_path %}

Unsupervised Image Captioning
======
* Unsupervised Image Captioning Method Based on the Extension of Object Features, 04/2023 - 02/2024
  * Proposed an unsupervised image captioning method based on object feature extension to address the problem of insufficient object features when constructing pseudo image-caption data.
  * Mined images from the MS-COCO dataset which contain certain objects corresponding to the sentences.
  * Proposed a novel object feature extension network to expand the original small amount of object features and construct a complete pseudo image feature that matches the given text, effectively enriching the object visual information in the task of unsupervised image captioning.
  * Fed the expanded object features into the transformer network for generating predicted sentences.
  * This method effectively improves the quality of the captioning model, enabling it to achieve optimal performance in most evaluation metrics.

Supervised Image Captioning
======
* Fusion Transformer for Image Captioning, 02/2022 - 09/2022
  * Proposed a novel fusion transformer network to fuse two types of visual features (region and grid features) considering multi-angle spatial relationships between objects.
  * Devised a modified multi-head self-attention that simultaneously contains relative directional relations, absolute information and relative positional information to enhance the orientation perception between visual features.
  * Implemented a fusion attention to thoroughly integrate the two types of visual features with word representations in an interlaced way.
  * Employed a fusion gate operation module to provide sophisticated control for the forward propagation of multimodal information as well as their backpropagating gradients.

* Further Improvement for Fusion Transformer, 09/2022 - 01/2023
  * Utilized segmentation features, which retains the spatial structure information of the original image, to substitute the original region features in order to be fused with the grid features more easily.
  * Performed competitively on various evaluation metrics, e.g., 134.7 CIDEr on COCO Karpathy test split.

Crawling and Visualization Analysis
======
* Crawling and Visualization Analysis System for Movie Website Data, 01/2021 - 5/2021
  * Designed a crawler and visualization analysis system that takes Douban Top250 Movies’ information as research objects.
  * Utilized XML Path Language to crawl basic information and short comments of classic movies on the Top250 film list, and stored the information into a database.
  * Obtained the target data from the database and filtered the short comments by constructing a stop word dictionary and an emotional dictionary.
  * Employed the Naive Bayes model to classify the sentiment of short comments.
  * Implemented the visual statistical display of the basic information and short comments of movies through Apache ECharts.
 
