# Alzheimer-s-Disease-Detection
**I. INTRODUCTION**
- This repository belongs to a research team of four high school students at the Brain Health Lab, Ho Chi Minh International University, Vietnam, under the supervision of Dr.Huong Thi Thanh Ha and Dr.Lua Thi Ngo.
- Our team members are:
  - Xuan Khoi Nguyen ([@Khoi-Nguyen-Xuan](https://github.com/Khoi-Nguyen-Xuan))
  - Tuan Anh Ngo ([@aanh1009](https://github.com/aanh1009))
  - Hoang Minh Thu Nguyen ([@noisyflowergarden](https://github.com/noisyflowergarden))
  - Phuc Pham
- Our research has **two objectives** :
1. Implement and optimize the performance of BERT in the task of Alzheimer's disease detection based on language impairment through audio transcript. The dataset we use in the research is provided by the DementiaBank.
2. Compare the perfomance of 5 BERT family models: BERT, RoBERTa, AlBERT, DistilBERT and DeBERTa for the same task based on various evaluation metrics (confusion matrix, f1, recall, precision,...)

**II. MODEL SELECTION** 

Since all of these 5 models are transformer-based architectures and are able to capture contextual relationships in text data, we want to determine which one offers the best performance and efficiency in Alzheimer's disease diagnosis. Here are some brief information about these models: 
- **BERT (Bidirectional Encoder Representations from Transformers)**: BERT is a transformer-based model that excels at capturing contextual information from text in both directions and is widely used in natural language processing tasks.
- **DistilBERT**: DistilBERT is a distilled version of BERT that retains much of BERT's performance while being computationally more efficient. 
- **ALBERT (A Lite BERT)**: ALBERT is another BERT variant designed to be more memory-efficient and faster while maintaining high performance, making it a valuable option for large-scale medical data analysis, where computational resources may be limited.
- **RoBERTa (A Robustly Optimized BERT Pretraining Approach)**: RoBERTa is an optimized variant of BERT that significantly improves pretraining techniques, potentially enhancing its performance in understanding complex medical texts and nuances in Alzheimer's disease data.
- **DeBERTa (Decoding-enhanced BERT with disentangled attention)**: DeBERTa is a BERT-based model with enhanced decoding mechanisms, enabling it to capture intricate relationships in medical text data

**III. TRAINING SETTINGS** 
- Learning rate: The learning rate for all models is 1e-5
- Epoch: The number of epochs for BERT, distilBERT and ALBERT is 10, while that of DeBERTa and RoBERTa is 20
- Batch size: The mutual number of batch size for all models is 2
. 

