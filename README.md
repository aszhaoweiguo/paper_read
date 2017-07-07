# HARD-WORKING
---------------------------------------------------
This repository show the notes about papers I read
这个仓库里是我读的paper时所理解的笔记。


#### [2017-07-05 Deep Android Malware Detection - Niall McLaughlin, etc](/papers/Deep_Android_Malware_Detection.md)
* paper title: Deep Android Malware Detection <br />
* paper authors: Niall McLaughlin, Jesus Mar tinez del Rincon, etc <br />
* paper keywords: Malware Detection, Android, Deep Learning <br />

>这篇论文使用静态操作码作为特征，CNN为模型，在实验环境下，F-sorce=0.97，在实际环境中，F-sorce=0.71。
>虽然实际环境中的效果不是特别好，但是模型训练所需要的时间相对较少，而且内存使用率上是一个常数。


#### [2017-05-24 Malware Detection with Deep Neural Network Usinig Process Behavior - Shun T., etc](/papers/Malware_Detection_with_Deep_Neural_Network_Usinig_Process_Behavior.md)
* paper title: Malware Detection with Deep Neural Network Usinig Process Behavior <br />
* paper authors: Shun Tobiyama, Yukiko Yamaguchi, Hajime Shimada, etc <br />
* paper keywords: malware infection detection, neural network, process behavior <br />

>这篇论文以进程行为作为源数据，之后使用RNN从源数据中抽取特征，并将抽取到的特征转化成特征图像，
>之后使用CNN以特征图像作为输入进行分类。使用ROC曲线作为评价标准，在最好的情况下AUC=0.96。
