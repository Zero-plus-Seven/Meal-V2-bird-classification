# Meal-V2-bird-classification
In this project I have shown:
- 下载和提取数据集
- 使用transforms加载数据集,并对数据集进行划分
- 计算数据集其均值并进行预处理、归一化、可视化
- defining a ResNet model
- defining the ResNet blocks
- loading a pre-trained model MEAL V2
- loading pre-trained model parameters into the defined model
- 定义一个类在一定范围内寻找最优学习率lr
- discriminative fine-tuning
- 使用One-cycle learning rate schedulers
- 训练模型，实现约80％的TOP-1准确性，并且在数据集中具有200个类别的〜95％的前5个准确性，每个类别只有60个示例
- 使用T-SNE在较低维度中可视化数据分类结果，可视化filters和学习到的特征
- 绘制ROC曲线和PR曲线等对模型进行评价
- 使用Tensorboard对模型结构和训练过程进行可视化
