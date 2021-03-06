## 1. 为什么需要机器学习策略？

机器学习是很多重要应用的基础，包括网页搜索、垃圾邮件分类、语音识别、商品推荐等等。假设你和你的团队正在开发一项机器学习相关的应用，并且想实现项目的快速迭代。本书介绍的内容将会为你提供帮助。

例子：创立一个关于猫咪图片的创业公司

假设你正在建立一个新的公司，该公司将为爱猫人士提供丰富的猫咪图片。

![](https://raw.githubusercontent.com/AlbertHG/Machine-Learning-Yearning-Chinese-ver/master/md_images/0.jpg)

其中的一个潮流的方法就是：使用神经网络(Neural Network)搭建的计算机视觉系统(Computer Vision System)来检测图片中的猫。

但，很不幸的是，系统的学习算法准确率(Accuracy)并不尽如人意，因此，你在改进算法的过程中必须承担来自各个方面的巨大压力，那么，具体怎么办呢？

你的团队有很多改善算法点子，例如：

- 获取更多的数据：收集更多有关猫咪的图片；
- 收集更加多元化的训练集。比如，处在不同位置的猫咪的图片、有不同颜色的猫咪的图片、来自相机不同的参数拍摄出来的猫咪的图片……
- 通过跑更多轮数的梯度下降(Gradient Descent)迭代，延长网络的训练时间；
- 尝试更大规模的神经网络，比如设置更多的层数、隐藏单元、参数等；
- 尝试较小规模的神经网络；
- 尝试在网络加入正则化(Regularization)（例如L2正则化）；
- 改变神经网络的结构（比如改变激活函数(Activation Function)、隐藏单元(Hidden Units)的数量等等）
- ……

如果选择了正确的优化方向，你将实现一个领先业界的猫咪图库平台，然后带领你的公司走向巅峰。但是如果你的优化措施选择并不好，大概率你会浪费掉数个月的时间，结果依旧没有改善。你将如何继续呢？

本书将会告诉你怎么做！大多数的机器学习问题都会留下一些线索，这些线索则会告诉你什么是有用的尝试，什么是徒劳的。学会理解这些暴露出来的线索能够节省你数月甚至上年的开发时间。