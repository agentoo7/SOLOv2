# SOLOv2
The code is an unofficial pytorch implementation of [SOLOv2: Dynamic, Faster and Stronger](https://arxiv.org/abs/2003.10152)


## Install
Please check [SOLOv1](https://github.com/WXinlong/SOLO/blob/master/docs/INSTALL.md) for installation instructions.

## Training
Follows the same way as SOLOv1.

single GPU: 
```
python tools/train.py configs/solov2/solov2_r101_3x.py
```
multi GPU (for example 8): 
```
./tools/dist_train.sh configs/solov2/solov2_r101_3x.py 8
```

## Results(Model is still in training, will update result once finished.)
4 epoch AP: 0.281

<img src="AP.jpg">

## Visualization（1 epoch)

<img src="solov2.png" width="2000">
