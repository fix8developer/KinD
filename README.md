# KinD
> Kindling the Darkness: a Practical Low-light Image Enhancer.
> This is a Tensorflow implementation of KinD

### Requirements :sparkles:

1. Python
2. Tensorflow == 1.15.0
3. numpy, PIL
4. etc.

### Test :octocat:

- [x] First download the pre-trained checkpoints from or [google drive](https://drive.google.com/open?id=1-ljWntl7FExf6BSQtl5Mz3rMGWgnXDz4).
- [x] Put the test data in the `./test/` directory
- [x] Just run the cell (7 - Testing on Actual Data)

### Train :camel:

The original LOLdataset can be downloaded from [here](https://daooshee.github.io/BMVC2018website/). I rearrange the original LOLdataset and add several all-zero images to improve the decomposition results and restoration results. The new dataset can be download from [google drive](https://drive.google.com/open?id=1-MaOVG7ylOkmGv1K4HWWcrai01i_FeDK). Save training pairs of LOL dataset under './LOLdataset/our485/' and save evaluating pairs under './LOLdataset/eval15/'.

For training, just run cells:

- [x] 3 - Decomposition-Net Train
- [x] 4 - Adjustment-Net Train
- [x] 5 - Reflectance_Restoration-Net Train


### Reference :rocket:

* [Research paper with code](https://paperswithcode.com/paper/190504161).
* Our code partly refers to the [code](https://github.com/weichen582/RetinexNet).
