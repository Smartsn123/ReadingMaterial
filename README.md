# ReadingMaterial

##  ML Techniques 

### DeepLearning Model Compression
   *  https://drive.google.com/file/d/1FuXMcE1ozRGvH9IFaqaNRG3hz_mjSd1W/view


------------------------------------------------------------------------------------------------------------------------------------------------------------------
##  NLP 

### MultiLingual Models
   * **A Look at MultiLingual Models**: https://peltarion.com/blog/data-science/a-deep-dive-into-multilingual-nlp-models

### About transformers
   *  **About transformers**: http://jalammar.github.io/illustrated-transformer/
   *  **Attentions in transformers/ self attention** : https://towardsdatascience.com/attn-illustrated-attention-5ec4ad276ee3
   
   
### BERT Illustrated
   * http://jalammar.github.io/illustrated-bert/
   * https://colab.research.google.com/github/tensorflow/tpu/blob/master/tools/colab/bert_finetuning_with_cloud_tpus.ipynb

#### Questions:
  * BERT vs  general vord vector generation algorithms
  * Does BERT needs pertaining  when context changes ?

  * Does BERT needs pertaining  when context changes ?
  * Has it learn to get output from Input context only or the context which it learnt for word ?
  * What is LABEL leak in BERT how do you solve it ? 
       ( Unidirectional training,)
       (Masking 15 % word in the  training INPUT, increasing the training time)

    



### BERT2DNN
BERT Distillation with Massive Unlabeled Data for Online E-Commerce Search - Relevance has significant impact on user experience and business profit for e-commerce search platform. In this work, they propose a data-driven framework for search relevance prediction, by distilling knowledge from BERT and related multi-layer Transformer teacher models into simple feed-forward networks with large amount of unlabeled data.

 * Paper https://lnkd.in/gE3zAGe
 * GitHub https://lnkd.in/geKCtKY

The distillation process produces a student model that recovers more than 97% test accuracy of teacher models on new queries, at a serving cost that's several magnitude lower (latency 150x lower than BERT-Base and 15x lower than the most efficient BERT variant, TinyBERT).

The applications of temperature rescaling and teacher model stacking further boost model accuracy, without increasing the student model complexity.

#### Authors
Yunjiang Jiang, Yue Shang, Ziyang Liu, Hongwei Shen, Yun Xiao, Wei Xiong, Sulong Xu, Weipeng Yan, Di Jin

--------------------------------------------------------------------------------------------------------------------------------------------------------------------
