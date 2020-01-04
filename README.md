# 猫狗大战
本项目会通过 Keras 搭建一个深度卷积神经网络来识别一张图片是猫还是狗，在验证集上的准确率可以达到99.8%，测试集logloss可以达到0.03810，建议使用显卡来运行该项目。
项目包含使用的第三方库：tensorflow、Keras、h5py、cv2、sklearn、matplotlib。
Preprocessing.ipynb是数据预处理代码
train.ipynb模型训练代码
数据集来自 kaggle 上的一个竞赛：[Dogs vs. Cats](https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition)，训练集有25000张，猫狗各占一半。测试集12500张，没有标定是猫还是狗。

```
➜  猫狗大战 ls train | head
cat.0.jpg
cat.1.jpg
cat.10.jpg
cat.100.jpg
cat.1000.jpg
cat.10000.jpg
cat.10001.jpg
cat.10002.jpg
cat.10003.jpg
cat.10004.jpg
➜  猫狗大战 ls test | head
1.jpg
10.jpg
100.jpg
1000.jpg
10000.jpg
10001.jpg
10002.jpg
10003.jpg
10004.jpg
10005.jpg
```
下面是训练集的一部分例子：

![](https://raw.githubusercontent.com/ypwhs/resources/master/dataset.png)







