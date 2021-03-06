# Deep Stacked Multi-patch Hierarchical Network for Image Deblurring
Pytorch Implementation of CVPR19 "[Deep Stacked Multi-patch Hierarchical Network for Image Deblurring](https://arxiv.org/pdf/1904.03468.pdf)" <br/>

![Pipeline of DMPHN](./docs/dmphn.png)

Please download GoPro dataset into './datas'. <br/>
https://drive.google.com/file/d/1H0PIXvJH4c40pk7ou6nAwoxuR4Qh_Sa2/view

GoPro Pretrained models are stored in './checkpoints'. 

__Requires.__
```
pytorch-0.4.1
numpy
scipy
```

__For model training, run following commands.__

```
python xxx.py -b 6
```


__For model testing, copy test samples into './test_samples', then run following commands.__

```
python xxx_test.py
```
## Citation
If you think this work is useful for your research, please cite the following paper.

```
@InProceedings{Zhang_2019_CVPR,
author = {Zhang, Hongguang and Dai, Yuchao and Li, Hongdong and Koniusz, Piotr},
title = {Deep Stacked Hierarchical Multi-Patch Network for Image Deblurring},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2019}
}
```
