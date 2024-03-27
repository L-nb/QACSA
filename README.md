# QA-style ACSA


## General Introduction
This repository contains the data of the paper QAGCN:Aspect Category Sentiment Analysis Towards
Question-Answering with Graph Convolutional Networks

**QACSA** is a large-scale QA-style Chinese dataset for the Aspect Category Sentiment Analysis (ACSA). 


The QACSA dataset is collected from three domains of ordinary users on two major online-to-offline (O2O) e-commerce platforms, 
[Jingdong](https://www.jingdong.com/) and [Taobao](https://www.taobao.com/), comprising 30,000 QA pairs.


## Data Statistics
![image](https://github.com/L-nb/QACSA/tree/main/Data_Statistics.png)



## Data Label
The sentiment polarity over the aspect category is labeled as 1(Positive), 0(Neutral), −1(Negative)


## Read File

  ```
  import pandas as pd
  
  data = pd.read_csv(file_path)
  ```


## Contact
Naibo Liu: liunaibo@dlmu.edu.cn

Yijia Zhang: zhangyijia@dlmu.edu.cn

Mingyu Lu: lumingyu@dlmu.edu.cn


