# Report

**小组成员**：韩伟东、张泽洋、罗昆、杨荣键

[TOC]

## 1 数据集介绍

我们使用的是**MNIST数据集**，MNIST数据集来自美国国家标准与技术研究所，National Institute of Standards and Technology (NIST)。**训练集**（training set）由来自 250 个不同人手写的数字构成, 其中50%是高中学生，50%来自人口普查局（the Census Bureau）的工作人员。**测试集**（test set）也是同样比例的手写数字数据。

其中包含60000个训练数据和10000个测试数据，举例如下：

![举例2](./举例2.png)![举例3](./举例3.png)

![举例4](./举例4.png)![举例1](./举例1.png)



## 2 网络结构

![模型结构1](./模型结构1.jpg)

其中模型参数：

- Batch size: 64

- Learning rate: 0.01

- Optimizer: SGD

- Iterration: 10 * ( 60000 / 64 )

- Epoch: 10

- Loss fuction: cross entropy loss

- 评价指标: acc



## 3 结果展示

![loss_acc](./loss_acc.jpg)

*横坐标为epoch，纵坐标为acc。*

### 图片识别结果

**预测为0**：

![预测为：0](./预测为：0.png)

**预测为1**：

![预测为：1](./预测为：1.png)