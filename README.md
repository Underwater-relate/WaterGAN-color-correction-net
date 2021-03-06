# Caffe Underwater-color-correction
**This is a modified version of [caffe-SegNet](https://github.com/alexgkendall/caffe-segnet/blob/segnet-cleaned) which supports the architecture of underwater color correction network for [WaterGAN](https://github.com/kskin/WaterGAN).**

This network module provide end-to-end color correction for underwater images, as described in **WaterGAN: Unsupervised Generative Network to Enable Real-time Color Correction of Monocular Underwater Images**(https://arxiv.org/abs/1702.07392)

### Dataset

1) MHL test tank dataset:  [MHL.tar.gz](http://www.umich.edu/~dropopen/MHL.tar.gz)
2) Jamaica field dataset: [Jamaica.tar.gz](http://www.umich.edu/~dropda/Jamaica.tar.gz)
### Model Zoo
1) MHL test tank  [color-net](http://www.umich.edu/~dropopen/color-correction-mhl.caffemodel.zip)  [depth-net](http://www.umich.edu/~dropopen/depth-estimation-mhl.caffemodel.zip)

1) Jamaica Port Royal [color-net](http://www.umich.edu/~dropopen/color-correction-jamaica.caffemodel.zip)  [depth-net](http://www.umich.edu/~dropopen/depth-estimation-jamaica.caffemodel.zip)

1) Lizard Island [color-net](http://www.umich.edu/~dropopen/color-correction-lizard-island.caffemodel.zip)  [depth-net](http://www.umich.edu/~dropopen/depth-estimation-lizard.caffemodel.zip)



### Net specification
### Training

## Publications
```
@article{li2017watergan,
    author    = {Jie Li, Katherine A. Skinner, Ryan M. Eustice and
               Matthew Johnson{-}Roberson},
  title     = {WaterGAN: Unsupervised Generative Network to Enable Real-time Color
               Correction of Monocular Underwater Images},
  journal   = {CoRR},
  volume    = {abs/1702.07392},
  year      = {2017},
  url       = {http://arxiv.org/abs/1702.07392},
  timestamp = {Wed, 01 Mar 2017 14:26:00 +0100},
  biburl    = {http://dblp.uni-trier.de/rec/bib/journals/corr/LiSEJ17},
  bibsource = {dblp computer science bibliography, http://dblp.org}
}
```
## License

This extension to the Caffe library is released under a creative commons license which allows for personal and research use only. For a commercial license please contact the authors. You can view a license summary here:
http://creativecommons.org/licenses/by-nc/4.0/
