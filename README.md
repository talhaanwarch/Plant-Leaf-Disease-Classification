# Plant-Leaf-Disease-Classification
Citrus Plant Disease Identification using Deep Learning with Multiple Transfer Learning Approaches
# Abstract
Citrus plant fruits constitute a significant part of Pakistan's agricultural fruits production. A substantial proportion of citrus fruits is destroyed every year because of different diseases. Citrus plants need to be examined manually to identify the disease prevalence. This paper proposed an in-depth learning approach to identify disease in citrus plants automatically. The dataset used comprised of a small number of citrus plant leaves divided into five categories; 4 of them are disease affected, and the fifth category includes healthy leaves. DenseNet 121 is used as a deep learning model to train the dataset. First, the model is prepared without a transfer-learning approach. Then the model is pre-trained on external data of plant leaves, ImageNet dataset, and a combination of external data and ImageNet data. Model without transfer learning failed to identify the diseases. Model pre-trained on external data resulted in an accuracy of 92%, AUC score of 98.8%, and F1-score of 95%. The model with combined pretraining resulted in an accuracy of 88% and F1-score of 88%. Pre-training on ImageNet data resulted in an accuracy of 82% and F1-score of 87%.

# Results
Following resulr can be reprouduce with the notebook 
[model_comparison_densenet121.ipynb](../master/model_comparison_densenet121.ipynb)

![Model Accuracy](https://github.com/talhaanwarch/Plant-Leaf-Disease-Classification/blob/master/Results/accuracy.png)

![Model Loss](https://github.com/talhaanwarch/Plant-Leaf-Disease-Classification/blob/master/Results/loss.png)

# Paper citations
```
@article{anwar2020citrus,
  title={Citrus Plant Disease Identification using Deep Learning with Multiple Transfer Learning Approaches},
  author={Anwar, Talha and Anwar, Hassan},
  journal={Pakistan Journal of Engineering and Technology},
  volume={3},
  number={2},
  pages={34--38},
  year={2020}
}
```


# Datset Refrence
```
dataset credit
@article{rauf2019citrus,
  title={A citrus fruits and leaves dataset for detection and classification of citrus diseases through machine learning},
  author={Rauf, Hafiz Tayyab and Saleem, Basharat Ali and Lali, M Ikram Ullah and Khan, Muhammad Attique and Sharif, Muhammad and Bukhari, Syed Ahmad Chan},
  journal={Data in brief},
  volume={26},
  pages={104340},
  year={2019},
  publisher={Elsevier}
}
```

# External Dataset link 
https://www.kaggle.com/emmarex/plantdisease

