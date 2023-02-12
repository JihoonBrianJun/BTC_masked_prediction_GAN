# BTC_masked_prediction_GAN
This repository contains the code and data for the project conducted during the SNU 2021-Winter Semester <Field application of IoT,AI,Big Data 1> course.

Presentation materials can be found in http://gece.snu.ac.kr/gecexe/index.php?mid=gece_lms&category=51919&document_srl=62210.

This project aims to use the GAN(Generative Adversarial Network) model to predict the masked value of 1-minute BTC price change direction, given the 1-minute price and volume data of the previous 19 minutes. (i.e., predict the shaded part within the image below)

<img width="231" alt="image" src="https://user-images.githubusercontent.com/88704958/218301049-19c00174-df4e-4d73-bc65-1f6238ec5131.png">
Model was trained and tested by the December 2021 BTC-USDT data downloaded from Binance (https://www.binance.com/en/landing/data).

Training was conducted on the GPU server provided by the course instructors, and took approiximately 2000 seconds.

At the ending of the training process, Discrimintor loss was -1.164(theoretically -ln4 is optimal), and Generator loss was -0.697(therotically -ln2 is optimal).

Model testing was done by the following process.

1. ㄴㄴ
2. ㄴㄴ


