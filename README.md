# 2022-基于深度学习的苹果叶病害识别研究
苹果是我国苹果主产区省份重要的经济作物，但各种病害仍是限制苹果高效生产的重要因素。传统的作物病害识别技术存在一定的局限性，而随着智慧农业的发展，深度学习在图像识别领域上表现极佳，利用深度学习对病害进行快速准确地识别成为当下研究热点。并且同一苹果叶可能存在多种病害，据此本文结合多标签分类方法与深度学习算法对苹果叶病害进行识别，在相关数据集上进行实验。主要研究内容如下：
首先，本文详细介绍了深度学习和多标签分类的理论知识，为后续的苹果叶病害识别实验如何选择合适的处理方法与算法打下基础。
其次，本文实验使用的苹果叶病害数据集总计有18632张有标注苹果叶面病害的图像，包含6种叶面状态，据此研究了模型训练前的数据预处理等对后续模型速度和鲁棒性有重要影响的因素。
最后，对数据集分别使用了MobileNetV1、MobileNetV2以及ResNet50网络模型，对它们在该数据集上的性能表现进行了分析与对比，最终ResNet50模型取得了三种模型中最高的平均F1-score值0.9006。

Apple is an important cash crop in the main apple producing provinces in China, but various diseases are still an important factor limiting the efficient production of apple. Traditional crop disease recognition technology has certain limitations, but with the development of smart agriculture, deep learning performs very well in the field of image recognition, and using deep learning to quickly and accurately identify diseases has become a current research hotspot. In addition, there may be multiple diseases in the same apple leaf. Therefore, this paper combines multi-label classification method and deep learning algorithm to identify apple leaf diseases and conduct experiment on relevant data sets. The main research contents are as follows:
First, this paper introduces the theoretical knowledge of deep learning and multi-label classification in detail, which lays a foundation for how to choose appropriate treatment methods and algorithms.
Secondly, there are a total of 18,632 images of apple leaf disease data set, including 6 leaf states. Accordingly, the factors such as data pretreatment before model training affecting the speed and robustness of the subsequent model are studied.
Finally, MobileNetV1, MobileNetV2 and ResNet50 network models were used for the dataset, and their performance on this dataset was analyzed and compared. Finally, ResNet50 model achieved the highest mean F1-score of 0.9006 among the three models.


#模型创建与训练部分的代码（最终显示的版本为ResNet50模型版本）
https://www.kaggle.com/code/jdd2022/2022jdd-research-on-apple-leaf-disease/notebook

#画图与预测部分的代码（最终显示的版本为ResNet50模型版本）
https://www.kaggle.com/jdd2022/notebook-plot2
