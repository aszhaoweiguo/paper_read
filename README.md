# HARD-WORKING
---------------------------------------------------
This repository show the notes about papers I read and the papers are almost about malware detection <br />
这个仓库里是我读paper时的笔记，其中的论文大多是关于恶意软件检测。


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


#### [2017-04-19 Malware Classification with Recurrent Networks - Rasvan P., etc](/papers/Malware_Classification_with_Recurrent_Networks.md)
* paper title: Malware Classification with Recurrent Networks <br />
* paper authors: Rasvan Pascanu, Jack W.Stokes, Hermineh Sanossian, Mady Marinescu, Anil Thomas <br />
* paper keywords: Malware Classification, Recurrent Neural Network, Deep Learning <br />

>这篇论文使用ESN作为循环模型进行特征抽取，Max-Pooling做非线性抽样，logistic回归做最后的分类；这样的混合模型达到最好的效果。
>相对标准的混合三元模型，本文提出的这个混合模型的true positive rate=98.3% & false positive rate=0.1%。

#### [2017-04-12 Efficient Dynamic Malware Analysis Based on Network Behavior Using Deep Learning - Toshiki S., etc](/papers/Efficient_Dynamic_Malware_Analysis_Based_on_Network_Behavior_Using_Deep_Learning.md)
* paper title: Efficient Dynamic Malware Analysis Based on Network Behavior Using Deep Learning <br />
* paper authors: Toshiki Shibahara, Taakeshi Yagi, Mitsuaki Akiyama, etc <br />

>这篇论文基于网络行为来确定是否应暂停动态分析的方法，使用RNN模型，在对29,562个恶意软件样本的评估中，提出的方法将分析时间缩短了67.1％，
Precision=0.976, Recall=0.962, F-measure=0.969。
