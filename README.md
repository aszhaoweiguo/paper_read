# HARD-WORKING
---------------------------------------------------
This repository show the notes about papers I read and the papers are almost about malware detection <br />
这个仓库里是我读paper时的笔记，其中的论文大多是关于恶意软件检测。


#### [2017-07-05 Deep Android Malware Detection - Niall McLaughlin, etc](/papers/Deep_Android_Malware_Detection.md)
* paper title: Deep Android Malware Detection <br />
* paper authors: Niall McLaughlin, Jesus Mar tinez del Rincon, etc <br />
* paper keywords: Malware Detection, Android, Deep Learning <br />

>这篇论文使用静态操作码作为特征，CNN为模型，在实验环境下，F-score=0.97，在实际环境中，F-score=0.71。
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


#### [2017-04-07 A multi-task learning model for malware classification with useful file access pattern from API call sequence - Xin W., etc](/papers/A_multi-task_learning_model_for_malware_classification_with_useful_file_access_pattern_from_API_call_sequence.md)
* paper title: A multi-task learning model for malware classification with useful file access pattern from API call sequence <br />
* paper authors: Xin Wang, Siu Ming Yiu <br />

>这篇论文使用API调用序列作为model的输入，使用RNN-AE作为特征的抽取，之后的Classifier和Generation不是很明白，最后的结果达到99%+，对这个结果保持观望。
感觉这个结果和数据集直接相关，个人观点，未进行实验验证。


#### [2017-03-29 DroidDetector Android Malware Characterization and Detection](/papers/DroidDetector_Android_Malware_Characterization_and_Detection.md)
* paper title: DroidDetector Android Malware Characterization and Detection <br />
* paper authors: Zhenlong Yuan, Yongqiang Lu, and Yibo Xue <br />
* paper keywords:  Android security; malware detection; characterization; deep learning; association rules mining <br />

> 本文中，我们提出将静态分析的特征与动态特征相关联分析Android应用程序，并使用深度学习DBN技巧来表征恶意软件。
DroidDetector可以实现96.76％的检测精度，优于传统机器学习技术。其中，本文中对数据的处理，特征的抽取的方面值得学习。

#### [2017-03-20 Fingerprinting Android packaging Generating DNAs for malware detection](/papers/Fingerprinting_Android_packaging_Generating_DNAs_for_malware_detection.md)
* paper title: Fingerprinting Android packaging Generating DNAs for malware detection <br />
* paper authors: ElMouatez Billah Karbab, Mourad Debbabi, Djedjiga Mouheb <br />
* paper keywords: Fingerprinting, Malware, Mobile, Android, Fuzzy hashing, Detection, Family attribution <br />

> 本文中，主要是基于静态的反编译，分析其静态特征，建立特征数据库，按照Jaccard Similarity来判断未知样本的标签及其所属家族。
虽然最后的F-score达到了94%，但是实验的数据集太少。结果展示的形式可以学习借用。
