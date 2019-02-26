# Tensorflow Tutorial
根据实验室以及个人理解制作的Tensorflow的小教程

基于Tensorflow 1.8

以图像超分辨率任务为例来入手Tensorflow，配套代码：•[https://](https://github.com/linchuming/ImageSR-Tensorflow)[github.com/linchuming/ImageSR-Tensorflow](https://github.com/linchuming/ImageSR-Tensorflow)



### 包含内容

- 基于tf.data.Dataset使用TFRecords或者Generator进行训练数据读取
- 基于tf.layers进行模型构建
- 模型训练以及测试，利用tensorboard查看训练过程
- 如何基于funetuning进行分类器训练
- Tensorflow常见的一些操作（其他）：例如变量复用，常用的loss设计，并行训练等等
- 模型保存导出以及如何使用C++进行模型调用