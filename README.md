### 运行所需要的环境

本实验在anaconda虚拟环境下运行

```
python 3.6
pillow 4.2.1
numpy 1.16
scipy 1.2.1
tensorflow-gpu 1.14.0
keras 2.25.0
h5py 2.10.0
```

#### To create the MNIST/CIFAR models:

```bash
python train_models.py
```

#### To download the inception model:

```bash
python setup_inception.py
```

#### And finally to test the attacks

```bash
python test_attack.py
```
