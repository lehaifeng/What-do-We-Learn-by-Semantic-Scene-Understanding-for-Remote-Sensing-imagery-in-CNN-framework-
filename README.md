# What-do-We-Learn-by-Semantic-Scene-Understanding-for-Remote-Sensing-imagery-in-CNN-framework-

* ### `Paper will come soon,thank you for your attention.`

Introduction
 we focus on the task of remote sensing scene recognition, revealing the differences between sensing scene and natural scene recognitions based on DCNN, standing on it to explore the pattern as DCNN identifies the remote sensing scene. The main contributions of our work are as follows:
	We analyzing how the depth of network and the scale of receptive field influence the performance of remote sensing scene understanding tasks, and reveal that using the same fixed depth and scale CNN network for all the types of scene understanding resulting in limited performance. Based on these findings, we suggest that addressing this scale bias from different complexity scene is critical to improve remote sensing scene understanding performance。This finding also inspires us designing a scale-specific network architectures may be a better way for remote sensing image understanding.
 We demonstrate the importance of joint multi-objective semantic support for fine-grained remote sensing scene understanding by analyzing the response of class activation maps in CNNs. This finds shows that Scene and object recognition are two closed related visual tasks, and solve these tasks in an integrated fashion may be a better way for remote sensing image understanding.
----
Experiment settings
 you need to install 'caffe','cuda'and assure you have matlab for caffe.
 if you do not install the platform,visit* [http://caffe.berkeleyvision.org/installation.htmle](http://caffe.berkeleyvision.org/installation.html)
----
Model
 we perform experiments in three ways:[multi-depth CNNs],contains series of alexnets and vgg-nets;[multi-scle CNNs],contains googlenet with different of receiptive fields;[feature visualization of CAMs],a extended version of googlenet.
 all of models are trainde with lr=0.001,lr_policy is SGD,and momentum=0.9.
 
