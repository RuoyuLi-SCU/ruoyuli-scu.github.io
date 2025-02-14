---
title:          "BAformer: Boundary Adaptive Transformer for Medical Image Segmentation."
date:           2024-08-15 00:01:00 +0800
selected:       true
pub:            "Frontiers in Bioengineering and Biotechnology <strong>(CCF-B, BIBM)</strong>"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
 Accurate automated segmentation of medical images remains a significant challenge due to the frequent presence of significant scale variations and unclear boundaries in the target areas. In this study, we propose a novel Boundary Adaptive Transformer (BAformer) specifically designed for medical image segmentation. BAformer is a hierarchical architecture that focuses on features highly relevant to target boundaries at any image resolution. Additionally, we introduce a Dense Feed-Forward Network (DenseFFN) to reuse features, enabling each layer to accumulate feature information from preceding layers. We extend the benefits of the dense network to the decoder architectures, achieving a balance between parameter efficiency and performance. Compared to TransU-Net, based on the conventional Transformer architecture, our approach reduces parameters and GFLOPs by 85\% and 35\% respectively. Extensive experiments demonstrate that BAformer achieves state-of-the-art performance on challenging medical segmentation tasks, including skin lesion, thyroid nodule, gland, and COVID-19 infection segmentation. Notably, BAformer can seamlessly integrate with existing segmentation networks to enhance their performance, showcasing its versatility and effectiveness. Our code will be made publicly available upon acceptance.
cover:          /assets/images/covers/BAFORMER.png
authors:
  - Junlong Cheng
  - Jilong Chen
  - Lei Jiang
  - Chenrui Gao
  - Junren Chen
  - <strong>Ruoyu Li</strong>
  - Min Zhu
links:
  Paper: https://ruoyuli-scu.github.io/Homepage/BAformer.pdf
  # Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
