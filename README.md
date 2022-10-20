# xml2txt
easy function for yolo training annotation format, change the xml annotations to txt annotations.（将xml格式文件转为txt文件，用于YOLO的训练）

	### demo

**Before the demo, make sure that you have python in your environment**

```
git clone https://github.com/ZhaXionghui/xml2txt.git

cd xml2txt
python xml2txt.py
```

after that you can get a train.txt and a val.txt,also with the image and labels folders in .\xml2txt\VOCdevkit, labels folder in .\xml2txt\VOCdevkit\VOC2007



use for yourself just focus on the parameters in xml2txt.py 

like:

```
# 类别名
classes = ['head']

# 训练集和验证集的比例
TRAIN_RATIO = 0.8
```

you can go to the root path of yolo and quickly use the function for later training. 
