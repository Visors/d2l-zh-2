# 深度学习入门（TensorFlow 版本）

本项目是对 [d2l-ai/d2l-zh](https://github.com/d2l-ai/d2l-zh) 项目的学习，旨在实现其 TensorFlow 版本的内容和每小节练习。

## 项目结构

```
深度学习入门/
├── tensorflow/
│ ├── img/ # 图片资源
│ ├── d2l.bib # 参考文献
│ ├── setup.py # 项目设置文件
│ ├── index.ipynb # 项目索引
│ ├── chapter_preface/ # 前言章节
│ ├── chapter_installation/ # 安装章节
│ ├── chapter_introduction/ # 介绍章节
│ ├── chapter_preliminaries/ # 基础知识章节
│ ├── chapter_optimization/ # 优化章节
│ ├── chapter_linear-networks/ # 线性网络章节
│ ├── chapter_multilayer-perceptrons/ # 多层感知机章节
│ ├── chapter_convolutional-neural-networks/ # 卷积神经网络章节
│ ├── chapter_recurrent-neural-networks/ # 循环神经网络章节
│ ├── chapter_attention-mechanisms/ # 注意力机制章节
│ ├── chapter_natural-language-processing-pretraining/ # 自然语言处理预训练章节
│ ├── chapter_natural-language-processing-applications/ # 自然语言处理应用章节
│ └── chapter_appendix-tools-for-deep-learning/ # 深度学习工具附录
└── README.md # 项目说明文件
```

## 注意事项

由于本人的运行环境是在运行Docker镜像tensorflow/tensorflow:latest-jupyter的容器中，并未严格遵照本书正文所给出的方法安装环境，导致Python包的版本可能有差异，进而在运行时出现了一些编译问题，我已通过修改代码的方式解决了这些问题。

尽管本项目内容上传时所有notebook内容都可以正常运行，但随着时间的推移和包版本的迭代，未来可能还会有新的问题，如果读者在运行时遇到问题，可以尝试按照最新的语法和标准修改代码。

通常来说，**我会将原书出现问题的代码部分加上注释，并在注释后写上我修正的代码**。对于修正的代码或原代码中难解的部分，我也加上了少量的注释。

