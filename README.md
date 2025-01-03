<div align="center">
<h1>MLTrMR</h1>
<h3>Masked Latent Transformer with the Random Masking Ratio to Advance the Diagnosis of Dental Fluorosis</h3>

[Hao Xu](https://github.com/uxhao-o)<sup>1,2</sup>, Yun Wu<sup>1,2, :email:</sup>, Junpeng Wu<sup>3</sup>, Rui Xie<sup>3</sup>, Maohua Gu<sup>1,2</sup>, Rongpin Wang<sup>4</sup>

<sup>1</sup>  State Key Laboratory of Public Big Data, Guizhou University <br>
<sup>2</sup>  College of Computer Science and Technology, Guizhou University <br>
<sup>3</sup>  Zhijin County People’s Hospital <br>
<sup>4</sup>  Department of Medical Imaging, Guizhou Provincial People’s Hospital

( :email: ) Corresponding author. <!-- ( \* )Co-first authors, -->

ArXiv Preprint ([arXiv 2404.13564](https://arxiv.org/abs/2404.13564))
</div>

# Notes
- This study has been submitted to journal for review.
- We will publish the code and dataset of MLTrMR in this repository when our paper is accepted.

# Abstract
Dental fluorosis is a chronic disease caused by long-term overconsumption of fluoride, which leads to changes in the appearance of tooth enamel. It is an important basis for early non-invasive diagnosis of endemic fluorosis. However, even dental professionals may not be able to accurately distinguish dental fluorosis and its severity based on tooth images. Currently, there is limited research on applying deep learning to diagnosing dental fluorosis. Therefore, we propose a novel deep learning model called masked latent transformer with the random masking ratio (MLTrMR). MLTrMR introduces a mask latent modeling scheme based on Vision Transformer to enhance contextual learning of dental fluorosis lesion characteristics. Consisting of a latent embedder, encoder, and decoder, MLTrMR employs the latent embedder to extract latent tokens from the original image, whereas the encoder and decoder comprising the latent transformer (LT) block are used to process unmasked tokens and predict masked tokens, respectively. To mitigate the lack of inductive bias in Vision Transformer, which may result in performance degradation, the LT block introduces latent tokens to enhance the learning capacity of latent lesion features. Furthermore, we design an auxiliary loss function to constrain the parameter update direction of the model. MLTrMR achieves 80.19\% accuracy, 75.79\% F1, and 81.28\% quadratic weighted kappa on we construct the first open-source dental fluorosis image dataset (DFID), making it state-of-the-art (SOTA).

# Overview
![](./image/MLTrMR.png)

# Dental Fluorosis Image Dataset (DFID)
![DFID](image/dfid.png)
