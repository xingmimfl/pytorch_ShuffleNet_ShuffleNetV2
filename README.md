# ShuffleNet with PyTorch
**Note:** This project is pytorch implementation of [ShuffleNet](https://arxiv.org/abs/1707.01083).

### Performance

Trained on ImageNet with groups=3, get Prec@1 67.898% and Prec@5 87.994%. During the training, I
set batch_size=256, learning_rate=0.1 which decayed every 30 epoch by 10. 


### Training on ImageNet

```bash
python main -b 256 $Imagenetdir
```

License: MIT license (MIT)
