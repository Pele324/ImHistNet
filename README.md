# ImHistNet: Learnable Image Histogram-based DNN

This [paper](http://ece.ubc.ca/~bisicl/papers/mahmiccai19.pdf) is proposed in MICCAI 2019. It is implemented in Caffe. The deatiled instructions of installing Caffe can be found [here](http://caffe.berkeleyvision.org/installation.html). 

## Data preparation
LMDB data format is used in this work. To generate this, there should different training, validation and testing data listing text files which should list the images as "imagename" "corresponding label":
- train_list.txt
  - image_000001.jpg 0
  - image_000002.jpg 1
  - image_000003.jpg 1
  - .......
