---
title:          "SEAformer: Selective Edge Aggregation transformer for 2D medical image segmentation."
date:           2024-10-10 00:01:00 +0800
selected:       true
pub:            "Biomedical Signal Processing and Control <strong>(SCI Q1, IF=4.9)</strong>"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
# pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
 Automatic medical image segmentation has a wide range of applications and high research values in medical research and practice, which can assist medical workers in clinical lesion assessment and diagnosis analysis of disease. However, it is still challenging due to the large-scale variations, blurred structural boundaries, and irregular shapes of segmentation targets in medical images. To tackle these challenges, we propose a selective edge aggregation Transformer (SEAformer) with an encoder-decoder architecture for 2D medical image segmentation. Specifically, we first combine densely connected CNNs and Transformers (with Dense MLP) in a parallel manner to form a dual encoder that efficiently captures shallow texture information and global contextual information in medical images in a deeper, multi-scale way. Then, we propose a plug-and-play selective edge aggregation (SEA) module that removes the noisy background unsupervisedly, selects and retains useful edge features, making the network more focused on the information related to the target boundary. Finally, we design a loss function that combines the target content and edges and use a multi-level optimization (MLO) strategy to refine the blur structure. This optimization helps the network to learn better feature representations and produce more accurate segmentation results. In addition, due to our densely connected approach to building the entire network, SEAformer has only 16 MB parameters and 32 GFlops. Extensive experimental results show that SEAformer performs well compared with state-of-the-art methods in four different challenging medical segmentation tasks, including skin lesion segmentation, thyroid nodules segmentation, GLAnd segmentation, and COVID-19 infection segmentation.
cover:          /assets/images/covers/SEAFORMER.png
authors:
  - Junlong Cheng
  - Jilong Chen
  - Lei Jiang
  - <strong>Ruoyu Li</strong>
  - et.al
links:
  Paper: https://ruoyuli-scu.github.io/Homepage/SEAformer.pdf
  # Unsplash: https://unsplash.com/photos/sliced-in-half-pineapple--_PLJZmHZzk
---
