# Object Detection

ubuntu 20.04 X86
pytorch 2.0.0
torchvision 0.15.1
torchaudio 2.0.1

## Install Pytorch

pip install torch==2.0.0 torchvision==0.15.1 torchaudio==2.0.1 --index-url https://download.pytorch.org/whl/cu118

## Install Dependenices

pip install -r requirements.txt

## Download Dataset

```
wget https://www.cis.upenn.edu/~jshi/ped_html/PennFudanPed.zip -P data
cd data && unzip PennFudanPed.zip
```

## Detection Frameworks

Faster R-CNN

## Notebook

- [Faster R-CNN detection](https://github.com/shadowdk3/object_detection/blob/master/notebook/pennfudanped.ipynb)

## Output

![](/ref/output.png)





