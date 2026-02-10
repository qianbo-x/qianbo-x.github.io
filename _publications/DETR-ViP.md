---
title: "DETR-ViP: Detection Transformer with Robust Discriminative Visual Prompts"
collection: publications
category: conferences
permalink: /DETR-ViP
# excerpt: ''
date: 2026-4-23
venue: 'The Fourteenth International Conference on Learning Representations'
# slidesurl: 'https://academicpages.github.io/files/slides1.pdf'
# paperurl: 'https://academicpages.github.io/files/paper1.pdf'
# bibtexurl: 'https://academicpages.github.io/files/bibtex1.bib'
citation: 'Bo Qian, Dahu Shi, and Xing Wei. (2026). &DETR-ViP: Detection Transformer with Robust Discriminative Visual Prompts.&quot; <i>The Fourteenth International Conference on Learning Representations</i>. 1(1).'
---
<!-- The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font. -->
**Abstract**:
Visual prompted object detection enables interactive and flexible definition of target categories, thereby facilitating open-vocabulary detection. Since visual prompts are derived directly from image features, they often outperform text prompts in recognizing rare categories. Nevertheless, research on visual prompted detection has been largely overlooked, and it is typically treated as a byproduct of training text prompted detectors, which hinders its development. To fully unlock the potential of visual-prompted detection, we investigate the reasons why its performance is suboptimal and reveal that the underlying issue lies in the absence of global discriminability in visual prompts. Motivated by these observations, we propose DETR-ViP, a robust object detection framework that yields class-distinguishable visual prompts. On top of basic image-text contrastive learning, DETR-ViP incorporates global prompt integration and visual-textual prompt relation distillation to learn more discriminative prompt representations.  In addition, DETR-ViP employs a selective fusion strategy that ensures stable and robust detection. Extensive experiments on COCO, LVIS, ODinW, and Roboflow100 demonstrate that DETR-ViP achieves substantially higher performance in visual prompt detection compared to other state-of-the-art counterparts. A series of ablation studies and analyses further validate the effectiveness of the proposed improvements and shed light on the underlying reasons for the enhanced detection capability of visual prompts.