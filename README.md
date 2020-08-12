# Representative Graph Neural Network(ECCV2020)

Implementation for "Representative Graph Neural Network"


## News
The RepGraph layer is around 17 times smaller in computation complexity and over 5 times faster than Non-local with a 256x128 input.

On the semantic segmentation task, we achieve 45.8% mean IoU on ADE20K val set, 53.9% mIoU on PASCAL-Context, and 81.5% mIoU on Cityscapes.

On the object detection/segmentation task, we achieve 39.6 AP^box (vs. 39.0 of NL) and 36.0 AP^mask (vs. 35.5 of NL).

## Citation
Please consider citing the RepGraph in your publications if it helps your research.

```
@inproceedings{Yu-ECCV-RepGraph-2020,
  title={Representative Graph Neural Network},
  author={Yu, Changqian and Liu, Yifan and Gao, Changxin and Shen, Chunhua and Sang, Nong},
  booktitle={Proceedings of the European Conference on Computer Vision (ECCV)},
  year={2020},
}
```
