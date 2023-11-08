# Reflection_Removal
Using UNET to remove reflection from images. Pedagogical model, not intended to be competitive.


### Kaggle Notebook

https://www.kaggle.com/sameen53/unet-remove-reflection


### Resources Used

UNET architecture
```
@inproceedings{ronneberger2015u,
  title={U-net: Convolutional networks for biomedical image segmentation},
  author={Ronneberger, Olaf and Fischer, Philipp and Brox, Thomas},
  booktitle={Medical Image Computing and Computer-Assisted Intervention--MICCAI 2015: 18th International Conference, Munich, Germany, October 5-9, 2015, Proceedings, Part III 18},
  pages={234--241},
  year={2015},
  organization={Springer}
}
```

Syntethic Image Dataset/Generation

https://colab.research.google.com/drive/1S-ERNYh3exswYomyQR5bLCPTg0K-rj5x?usp=sharing

```
@inproceedings{zhang2018single,
  title = {Single Image Reflection Separation with Perceptual Losses},
  author = {Zhang, Xuaner and Ng, Ren and Chen, Qifeng}
  booktitle = {IEEE Conference on Computer Vision and Pattern Recognition},
  year = {2018}
}
```



### Running 'Single Image Reflection Separation with Perceptual Losses' on Colab

```
@inproceedings{zhang2018single,
  title = {Single Image Reflection Separation with Perceptual Losses},
  author = {Zhang, Xuaner and Ng, Ren and Chen, Qifeng}
  booktitle = {IEEE Conference on Computer Vision and Pattern Recognition},
  year = {2018}
}
```

### Results
```
epoch = 25
lr = 0.0003
dataset_len = 15000
on_the_fly = False
```

Input - Target - Output
![image](https://github.com/PatchworkProgrammer/Reflection_Removal_DL/assets/83033987/712b5dac-2081-4861-a4a1-94ab4b71e207)

[Model Weight](https://www.kaggle.com/datasets/sameen53/unet-model15k)
