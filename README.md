# voice_assistant
ResNet架构下的语音助手
## 我们主要的构想是通过ResNet残差神经网络训练一个能够实现以下功能的语音助手

（1）首先说一下这个项目的初衷，随着语音助手的普及，同声翻译等人工智能语音助手的出现，市面上的语音助手数不胜数，
但是这些语音助手大多数都是基于百度，讯飞等做好的语音助手API直接调用构建的，我们想利用神经网络强大的学习能力自己构建和训练语音助手模型于是就有了RNN语音助手的想法

（2）主要实现功能
    1.能够区分环境音和人声音
    2.能够区分不同人说的不同的话
    3.能够处理大批量的语音
    4.能够不断学习人声
    
