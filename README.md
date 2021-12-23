# FeatureNet: Upsampling of Point Cloud and it’s Associated Features
---
#### Introduction 
This repository is for our paper '[FeatureNet: Upsampling of Point Cloud and it’s Associated Features](https://dl.acm.org/doi/10.1145/3415264.3425471)'. The code is modified from [PU-NET](https://github.com/yulequan/PU-Net).

#### Installation
This repository is based on Tensorflow and the TF operators from PU-NET. Refer this repository for compiling the TF operators.


#### Usage
1. Train your own model
```
python main.py --phase train
```

2. To test on existing model
```
python main.py --phase test --log_dir ../model/generator2_new6
```




