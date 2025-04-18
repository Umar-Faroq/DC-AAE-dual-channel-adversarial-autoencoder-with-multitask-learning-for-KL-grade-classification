# DC-AAE-dual-channel-adversarial-autoencoder-with-multitask-learning-for-KL-grade-classification

Knee osteoarthritis (OA) is a frequent musculoskeletal disorder that leads to physical disability in older adults. Manual OA assessment is performed via visual inspection, which is highly subjective as it suffers from moderate to high inter-observer variability. Many deep learning-based techniques have been proposed to address this issue. However, owing to the limited amount of labelled data, all existing solutions have limitations in terms of performance or the number of classes. This paper proposes a novel fully automatic Kellgren and Lawrence (KL) grade classification scheme in knee radiographs. We developed a semi-supervised multi-task learningbased approach that enables the exploitation of additional unlabelled data in an unsupervised as well as supervised manner. Specifically, we propose a dual-channel adversarial autoencoder, which is first trained in an unsupervised manner for reconstruction tasks only. To exploit the additional data in a supervised way, we propose a multi-task learning framework by introducing an auxiliary task. In particular, we use leg side identification as an auxiliary task, which allows the use of more datasets, e. g., CHECK dataset. The work demonstrates that the utilization of additional data can improve the primary task of KL-grade classification for which only limited labelled data is available. This semi-supervised learning essentially helps to improve the feature learning ability of our framework, which leads to improved performance for KL-grade classification. We rigorously evaluated our proposed model on the two largest publicly available datasets for various aspects, i.e., overall performance, the effect of additional unlabelled samples and auxiliary tasks, robustness analysis, and ablation study. The proposed model achieved the accuracy, precision, recall, and F1 score of 75.53%, 74.1%, 78.51%, and 75.34%, respectively. Furthermore, the experimental results show that the suggested model not only achieves state-of-the-art performance on two publicly available datasets but also exhibits remarkable robustness.

![image alt](https://github.com/Umar-Faroq/DC-AAE-dual-channel-adversarial-autoencoder-with-multitask-learning-for-KL-grade-classification/blob/main/Samples.PNG?raw=true)


## Overall pipeline
![image alt](https://github.com/Umar-Faroq/DC-AAE-dual-channel-adversarial-autoencoder-with-multitask-learning-for-KL-grade-classification/blob/main/Preprocessing.PNG?raw=true)

## Pipeline of the central cropping

![image alt](https://github.com/Umar-Faroq/DC-AAE-dual-channel-adversarial-autoencoder-with-multitask-learning-for-KL-grade-classification/blob/main/Central_crop.PNG?raw=true)

## The KL-Grade Classification model
![image alt]()


