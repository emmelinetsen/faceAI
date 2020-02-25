CMPE 298 - Deep Learning\
Emmeline Tsen\
Jerry X. Huang\
Jie Zou(Jacky Chow)

# Facial Expression Recognition (FER) Project Proposal

# Abstract
Our project will focus on applying facial recognition on images and determining the person’s facial expression in the image. Facial recognition has been a popular topic within artificial intelligence. In addition to being able to recognize a person’s face within an image, being able to determine the person’s emotions can also be significant. It can help better understand what the person may be feeling based on the image. We will be using Convolutional Neural Networks to build a model to detect faces based on images. We plan to use images found through Google Images to train our data. The images that we will be using will have people’s faces with different emotions to represent the different labels for training. 

# Introduction
As the the rapid development of machine learning, convolutional neural network and  smart devices, facial recognition technology has shown great growth. Also the discussion on facial recognition technology never stopped in today's world. Facial Expression Recognition(FER), as an important part of face recognition technology, has received extensive attention in recent years in the field of medical, security, automatic pilot, communication, robotics, etc. Therefore in the following paragraph we will discuss the definition, algorithm, methodology, develop experiment and application deployment about the Facial Expression Recognition.  

# Related Work & Methodology 

We surveyed journal articles to gain better insight about Facial Expression Recognition (FER), and how to use Deep Learning for recognition. The literature review enabled us to know the direction and method to achieve our project.Below are four literature reviews relevant to our project topic:
 
[1] Shervin Minaee and Amirali Abdolrashidi, “Deep-Emotion: Facial Expression Recognition Using Attentional Convolutional Network.”, arXiv:1902.01019v1 [cs.CV] 4 Feb, 2019.\
This article propose a deep learning approach which is based on an attentional convolutional network and focuses on the important parts of the face. They used the approach on multiple datasets, including FER-2013,CK , FERG, and JAFFE and achieved significant improvement over previous models. We can use the visualization technique to find the important face regions for detecting different emotions which is based on the classifier’s output. We can use the concepts found in this article to find how the different emotions are sensitive to different parts of the face. Attention is an important piece for detecting facial expressions and can enable neural networks with less than 10 layers. It can achieve better results than more traditional approaches that use deeper networks.

[2] Cătălin Căleanu, “Face expression recognition: A brief overview of the last decade”,
Applied Computational Intelligence and Informatics (SACI), 2013 IEEE 8th International Symposium on, 2013.\
As an active research area over the past few decades, facial expression recognition is still challenging due to the high intra-class variation. The weak points of traditional research on machine analysis of human face expression recognition  is that most of them  still  require  manual intervention. This article summarizes some representative methods identified in the facial expression recognition research from 2003 to 2012(selected 10 papers published since 2003). Mainly includes methods such as Tree-Augmented-Naive Bayes (TAN) classifier, 2D-DCT, Local 
Binary  Patterns  (LBP) , local directional  pattern  (LDP), SVM, and geometric  features  +TAN. Huge research results in the field of  FER technology have proven their potential applications in multiple fields such as computer science, engineering, psychology, neuroscience. The article also discussed data acquisition, pre-processing,  feature extraction  and selection, and  subsequent  classification. 

[3] Sajid Ali Khan, Ayyaz Hussain and Muhammad Usman, “Facial expression recognition on real world face images using intelligent techniques: A survey”, Optik. Vol.127(15), p.6195-6203, 2016.\
In order to overcome the shortcomings of traditional facial expression recognition systems (such as LBP and WLD) on datasets obtained in predetermined laboratory environments, the article identifies different specifications and gestures used between different races and ethnicities, and further improve facial expression image classification This paper proposes that macro texture information must be stored to obtain better accuracy results. This article proposes a novel framework to recognize facial expressions with high accuracy, aiming to improve time and memory efficiency. It can store not only micro-texture information but also macro-texture information. The performance in the article is also measured using synthetic (ie, lab-based) and real-world face image datasets.


[4] Shui-Hua Wang, Preetha Phillips, Zheng-Chao Dong and Yu-Dong Zhang, “Intelligent facial emotion recognition based on stationary wavelet entropy and Jaya algorithm”, Optik. Vol.127(15), p.6195-6203, 2016.\
This article proposed a method used stationary wavelet entropy to extract features, and employed a single hidden layer feedforward neural network as the classifier.In order to  prevent the training of the classifier fall into local optimum points,they used the Jaya algorithm on over a 20-subject 700-image dataset, and  reached  96.80 ± 0.14% overall accuracy.

# Conclusion
The entire research on facial expression recognition has been developed following the development of facial recognition. The mainstream methods are from traditional manual features (LBP, LBP-TOP, etc.), shallow learning (SVM, Adaboost, etc.), and deep learning (CNN, DBN, RNN). Since 2013, there have been  many competitions for facial expression recognition, such as FER2013, EmotiW and so on. The better methods in the field of facial recognition will also be applicable to facial recognition. In our project, we propose to use CNN for facial recognition and to detect facial emotions.


# Sources

[1] https://arxiv.org/pdf/1902.01019.pdf \
[2] https://www.researchgate.net/publication/261498182_Face_expression_recognition_A_brief_overview_of_the_last_decade \
[3] https://www-sciencedirect-com.libaccess.sjlibrary.org/science/article/abs/pii/S0030402616302807 \
[4] https://www-sciencedirect-com.libaccess.sjlibrary.org/science/article/pii/S0925231217313644

Dataset:https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

API: https://azure.microsoft.com/zh-cn/services/cognitive-services/face/


