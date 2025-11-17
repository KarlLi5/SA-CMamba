# SA-CMamba
# [Elsevier-Measurement-2025]SA-CMamba: Stripe-aware CNN-mamba hybrid network for pixel-level surface defect detection

This is the official repository for SA-CMamba. 

Related links:
[[Official PDF Download]](https://doi.org/10.1016/j.measurement.2025.119510)

## Introduction
Automated surface defect detection provides a foundation for the quantitative evaluation of defects, while being critical for ensuring product quality and infrastructure safety. However, pixel-level detection remains challenging due to intra-class feature heterogeneity, inter-class feature similarity, and the difficulty in capturing long-range dependencies and contextual relationships across stripe-like structures. Although convolutional neural networks (CNNs) have been successfully and widely used in the design of surface defect detection models, current CNN-based methods are still unable to cope with the above challenges due to insufficient global context modeling. To address these challenges, we propose a Stripe-aware CNN-Mamba Hybrid Network (SA-CMamba) for surface defect detection. First, we construct a hybrid CNN-Mamba feature extraction block. The CNN branch incorporates multi-scale dilated convolutions to adaptively capture fine-grained local textures and morphological details, thereby mitigating intra-class heterogeneity. In parallel, the Mamba branch applies directional scanning to efficiently learn long-range dependencies and model defect context associations, effectively addressing inter-class similarity. Second, we design a Stripe-aware Enhancement Module (SAEM), which combines self-stripe attention and cross-stripe attention mechanisms to enhance continuity modeling within stripe features and enable contextual interaction across different stripe patterns. Finally, extensive experiments on the three public datasets NEU-Seg, DAGM, and CRACK500 show that SA-CMamba achieves mean intersection-over-union values of 90.97%, 79.24%, and 62.33%, respectively, and outperforms existing methods.

## Citation

If you are using the code/model/data provided here in a publication, please consider citing our works:

````
@article{li2025sa,
  title={SA-CMamba: Stripe-aware CNN-mamba hybrid network for pixel-level surface defect detection},
  author={Li, Wukai and Wang, Chao and Feng, Wenlu and Wang, Xiaoxu and Ren, Zeyu and Wang, Jiarui and Wang, Cheng and Lu, Qianbo},
  journal={Measurement},
  pages={119510},
  year={2025},
  publisher={Elsevier}
}
````

## Other Notes

If you meet any problems, please do not hesitate to contact us.
Issues and discussions are welcome in the repository!
You can also contact us via sending messages to this email: liwukai51@gmail.com

## License
This code is released under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License for Non-Commercial use only. Any commercial use should get formal permission first.
