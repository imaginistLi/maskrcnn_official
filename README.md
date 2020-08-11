# MaskRcnn PyTorch Torchvision 官方教程
官网链接：[torchvision maskrcnn](https://pytorch.org/tutorials/intermediate/torchvision_tutorial.html?highlight=torchvision)
## requirement
> 我的系统是Ubuntu18.04

安装pycocotools
```
pip install cython
pip install -U 'git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI'
```
下载示例数据集并解压
```
# download the Penn-Fudan dataset
wget https://www.cis.upenn.edu/~jshi/ped_html/PennFudanPed.zip .
# extract it in the current folder
unzip PennFudanPed.zip
```
最后用jupyter notebook运行[demo.ipynb](./demo.ipynb)就可以了
