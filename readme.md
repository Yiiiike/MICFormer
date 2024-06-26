# Multimodal Information Interaction for Medical Image Segmentation.

## Welcome to reproduce our code!!!

Our article is now publicly available on ArXiv（[[2404.16371\] Multimodal Information Interaction for Medical Image Segmentation (arxiv.org)](https://arxiv.org/abs/2404.16371)）. This repository provides the training code for the MM-WHS dataset. If you need to reproduce our results, you can use the training scripts provided in this repository.



### Dataset

The dataset used in this paper is the MM-WHS dataset, which can be found at [Multi-Modality Whole Heart Segmentation Challenge](https://zmiclab.github.io/zxh/0/mmwhs/). Additionally, the data preprocessing method used in this paper can be performed through the registration method described in the text.

We also provided our dataset processing script in prepocess.py, which we can run by changing the file path to get the same data as the article.

```shell
python prepocess.py
```



### Run

In addition to providing the MicFormer code, this repository also includes training and testing code for state-of-the-art methods. These include VT-Unet, Swin-Unet, SwinUneter, nnFormer, and MedNeXt.



### Citations

```latex
@misc{fan2024multimodal,
      title={Multimodal Information Interaction for Medical Image Segmentation}, 
      author={Xinxin Fan and Lin Liu and Haoran Zhang},
      year={2024},
      eprint={2404.16371},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

