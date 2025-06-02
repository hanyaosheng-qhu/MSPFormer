<p align="center">
  <img src="files/1.png" alt="Logo" width="200"/>
</p>
<p align="center">
  <strong>Yaosheng Han<sup>1</sup>,<sup>2</sup>, <strong>Chunmei Li<sup>1</sup>,<sup>2</sup>, <strong>Qing Dong<sup>1</sup>,<sup>2</sup>,<strong>Xiangjie Huang<sup>1</sup>,<sup>2</sup>,<strong>Hao Wang<sup>1</sup>, <sup>2</sup></strong><br>
    <strong><sup>1</sup>School of Computer Technology and Applications, Qinghai University, Xining, Qinghai, China</strong><br>
    <strong><sup>2</sup>Intelligent Computing and Application Laboratory of Qinghai Province, Qinghai
University, Xining, Qinghai, China</strong><br>
  <a href="https://hanyaosheng-qhu.github.io/MSPFormer/">Paper</a> | <a href="https://hanyaosheng-qhu.github.io/MSPFormer/">Demo</a>


# MSPFormer: Multi-Scale and Semantic-Preserving Transformer for Herder-Oriented Sheep Ownership Recognition
Overgrazing is one of the main causes of grassland degradation on the Qinghai–Tibet Plateau, and how to leverage intelligent technology to achieve effective grass–livestock balance supervision has become a significant challenge in livestock management. Accurately distinguishing different herders’ sheep flocks can effectively facilitate scientific grazing management and reduce the risk of overgrazing. In practice, herders usually apply different colors to the backs of their sheep to indicate ownership. This study focuses on the intelligent recognition of sheep ownership by analyzing sheep back color features. First, a dedicated dataset was constructed under variable lighting and complex background conditions, capturing diverse color distributions. Then, to address the challenge of fine-grained segmentation of sheep back colors in complex environments, a robust and efficient multi-scale and semantic-preserving Transformer model called MSPFormer is proposed. This model builds on the Mask2Former architecture by introducing an Atrous Spatial Pyramid Pooling (ASPP) module between the Pixel Decoder and the Transformer Decoder to enhance multi-scale feature extraction, integrating a Dynamic Prompt Attention (DPA) module to improve semantic consistency, and adding a Content-Aware ReAssembly of Features(CARAFE) upsampling module after the Transformer Decoder to optimize spatial detail recovery. Experimental results show that MSPFormer increases the mIoU from 82.46% to 83.81% (a relative improvement of ~1.35%), the mF1-score from 90.08% to 90.92% (an increase of ~0.84%), the mPrecision from 89.50% to 91.52% (an increase of ~2.02%), and the mRecall from 90.74% to 90.92% (an increase of ~0.18%). Further validation on the public VOC2012 dataset and several small-sample subsets demonstrates the model’s strong generalization capability and stability. This research demonstrates that MSPFormer provides effective technical support for intelligent sheep ownership recognition and sustainable grazing management in the Qinghai–Tibet Plateau region. Future work will focus on lightweighting the model by integrating pruning and knowledge distillation techniques to improve practical deployment efficiency. 


The code will be uploaded shortly. Please stay tuned as we finalize the preparation.
