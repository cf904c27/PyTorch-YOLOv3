# PyTorch-YOLOv3
利用PyTorch 實現 YOLOv3

## Table of Contents
- [PyTorch-YOLOv3](#pytorch-yolov3)
  * [Paper](#paper)
  * [安裝](#安裝)
  * [使用範例](#使用範例)
  * [Credit](#credit)

## Paper

[[Paper]](https://pjreddie.com/media/files/papers/YOLOv3.pdf) [[Original Implementation]](https://github.com/pjreddie/darknet)

## 安裝
    $ git clone https://github.com/cf904c27/PyTorch-YOLOv3
    $ cd PyTorch-YOLOv3/
    $ sudo pip3 install -r requirements.txt

##### 下載預訓練模型
    $ cd weights/
    $ bash download_weights.sh

## 使用範例
    $ !python3 detect.py --image_folder /content/PyTorch-YOLOv3/temp/part1
    $ 得到含有人物圖片路徑的TXT檔  img_path.txt


## Credit
```
@article{yolov3,
  title={YOLOv3: An Incremental Improvement},
  author={Redmon, Joseph and Farhadi, Ali},
  journal = {arXiv},
  year={2018}
}
```
