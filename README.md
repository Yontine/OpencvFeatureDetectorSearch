# OpencvFeatureDetectorSearch
对opencv策略模式的学习

FeatureDetetor是虚类，通过定义FeatureDetector的对象可以使用多种特征检测方法。通过create()函数调用：
任务分配：
2人：
理解FeatureDetetor虚类，并给出继承于它的子类
"FAST" – FastFeatureDetector
"STAR" – StarFeatureDetector
"SIFT" – SIFT (nonfree module)
"SURF" – SURF (nonfree module)
"ORB" – ORB
的代码解释和作用，根据策略模式画出虚类与五个子类的uml图

2人：
理解FeatureDetetor虚类，并给出继承于它的子类
"MSER" – MSER
"GFTT" – GoodFeaturesToTrackDetector
"HARRIS" – GoodFeaturesToTrackDetector with Harris detector enabled
"Dense" – DenseFeatureDetector
"SimpleBlob" – SimpleBlobDetector
的代码解释和作用，根据策略模式画出虚类与五个子类的uml图

1人：
汇总工作，汇总代码解释、作用和uml图，绘制ppt上台答辩
