---
abbrlink: ''
categories:
- - Python
date: '2023-11-24T02:12:19.807193+08:00'
tags:
- Python
title: cuda 11.3 笔记本-大电脑安装过程
updated: 2023-11-24T2:12:21.83+8:0
---
## 11.13环境安装

`Transformer`推荐安装环境的版本：

**Pytorch：**`1.10.0` torchtext：`0.11.0` Python：`3.7`

`3.7`版本

## cuda 11.3 笔记本-大电脑安装过程

```
 conda create -n trans371 python=3.7
 conda activate trans371
 
 conda install pytorch==1.10.0 torchvision==0.11.0 torchaudio==0.10.0 cudatoolkit=11.3 -c pytorch -c conda-forge
 # 其他配套安装
 
 
 pip install torchtext==0.11.0
 pip install spacy
 pip install pyitcast
 pip install pandas
 pip install matplotlib
 pip install AEML
 pip install tensorboard
 pip install distutils
 
 pip uninstall setuptools
 pip install setuptools==59.5.0 //需要比你之前的低 
 pip install scikit-learn
 pip install seaborn
 
 
 禁用 conda env remove --name <env_name>
 pip install -r H:\PyTorch\4StockMarketPrediction\requirements.txt\requirement.txt
 
```

`陈硕`版本

```
 conda create -n torch_chen2 python=3.8
 conda activate torch_chen2
 
 pip3 install torch==1.10.0+cu113 torchvision==0.11.1+cu113 -f https://download.pytorch.org/whl/cu113/torch_stable.html -i https://pypi.douban.com/simple
 pip install xlrd==1.2.0
 pip install xlrd==4.64.1
 cudnn-windows-x86_64-8.8.0.121_cuda12-archive.zip
 cuda_12.0.0_527.41_windows.exe
 
 
 pip install matplotlib==3.2.0 -i https://pypi.douban.com/simple/
 
 
 conda create –n py35 python=3.5
 activate py35
 
 # 设置路径
 https://blog.csdn.net/m0_67313306/article/details/124204890
 conda create -n torch1.11 python=3.8
 conda activate torch1.11
 conda install pytorch==1.8.1 torchvision==0.9.1 torchaudio==0.8.1 cudatoolkit=10.2 -c pytorch
 pip install xlrd==1.2.0
 pip install matplotlib==3.2.0 -i https://pypi.douban.com/simple/
 
 
 
 
 
 
```
