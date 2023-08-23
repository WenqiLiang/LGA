# LGA

This is the Pytorch Implementation for [No One Left Behind: Real-World Federated Class-Incremental Learning](https://arxiv.org/abs/2302.00903)

This paper is a substantial extension of [[CVPR-2022] Federated Class-Incremental Learning](https://openaccess.thecvf.com/content/CVPR2022/html/Dong_Federated_Class-Incremental_Learning_CVPR_2022_paper.html)


## Overview
![image](https://github.com/JiahuaDong/LGA/blob/main/data/overview.png)

## Requirements:
* python == 3.8
* torch == 1.7.0
* numpy
* PIL
* torchvision == 0.8.1
* cv2
* scipy
* sklearn

## Datasets:
* CIFAR100: You don't need to do anything before running the experiments on CIFAR100 dataset.

* Imagenet-Subset (Mini-Imagenet): Please manually download the on [Mini-Imagenet](https://github.com/yaoyao-liu/mini-imagenet-tools) dataset from the official websites, and place it in './dataset'.

* Tiny-Imagenet: Please manually download the on [Tiny-Imagenet](https://github.com/seshuad/IMagenet) dataset from the official websites, and place it in './dataset'.
## Launching an experiment:

For exampler, if you want to run LGA on CIFAR100 in the 10 steps setting:

Modify the path of dataset in './scripts/cifar_task_10.sh' and run the following commands.

    sh scripts/cifar_task_10.sh
  
## Citation:

If you find this code is useful to your research, please consider to cite our paper.

```
@InProceedings{Dong2023_LGA,
    author = {Dong, Jiahua and Cong, Yang and Sun, Gan and Zhang, Yulun and Schiele, Bernt and Dai, Dengxin},
    title = {No One Left Behind: Real-World Federated Class-Incremental Learning},
    booktitle = {arXiv preprint arXiv:2302.00903},
    month = {Feb.},
    year = {2023},
}
```

```
@InProceedings{dong2022federated,
    author = {Dong, Jiahua and Wang, Lixu and Fang, Zhen and Sun, Gan and Xu, Shichao and Wang, Xiao and Zhu, Qi},
    title = {Federated Class-Incremental Learning},
    booktitle = {IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month = {June},
    year = {2022},
}
```

## Contact:
If you have some questions, feel free to contact:
* **Jiahua Dong:** dongjiahua1995@gmail.com
