# Perceived-Emotions-Baseline

This repository includes baselines of the perceived emotion estimation. The perceived emotion estimation is also known as Affective Computing [1], which is to estimate the emotions that are expected to be evoked in viewers by visual contents.

**We welcome contributes! Feel free to submit pull requests!**

# Continuous Emotion Prediction for Image

Emotions can be described by arousal and valence (VA). Some papers also use 3 values (arousal, valence and dominance) (VAD) to describe. Continuous Emotion Prediction is to estimate the VA or VAD values

The performance of the baseline is as follows

| Model    | Dataset  | MSE     | RMSE     |
| -------- | -------- | ------- | -------- |
| Resnet50 | IAPS     | 0.01742 | 0.131648 |
| Resnet50 | CGNA [2] |         | 0.142139 |

Note that both the MSE and RMSE are calculated in the normalized score, i.e., the range of scores is [0,1].

Pretrained models can be downloaded in [this link](https://entuedu-my.sharepoint.com/:f:/g/personal/chang015_e_ntu_edu_sg/EtXLEitn_ytFvs4KaSZokS0Bbfk5TA9Um6KINHsKzqDFyA?e=SfGhKG)

# TODO

Add Discrete Emotion Classification for Images

Add Models for Videos

# Reference

[1] Zhao, Sicheng, et al. "Affective Computing for Large-scale Heterogeneous Multimedia Data: A Survey." ACM Transactions on Multimedia Computing, Communications, and Applications (TOMM) 15.3s (2019): 1-32.

[2] Kim, Hye-Rin, et al. "Building emotional machines: Recognizing image emotions through deep neural networks." IEEE Transactions on Multimedia 20.11 (2018): 2980-2992.
