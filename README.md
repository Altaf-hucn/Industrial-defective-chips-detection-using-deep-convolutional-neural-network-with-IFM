# Industrial Defective Chips Detection using Deep Convolutional Neural Network with Inverse Feature Matching Mechanism

**Paper Title**: Industrial Defective Chips Detection using Deep Convolutional Neural Network with Inverse Feature Matching Mechanism  
**Published in**: *Journal of Computational Design and Engineering*  
**DOI**: [https://doi.org/10.1093/jcde/qwae019](https://doi.org/10.1093/jcde/qwae019)  

---
## Abstract

The growing demand for high-quality industrial products has led to a significant emphasis on image anomaly detection (AD). Anomaly detection in industrial goods presents a formidable research challenge that demands the application of sophisticated techniques to identify and address deviations from the expected norm accurately. Manufacturers increasingly recognize the significance of employing intelligent systems to detect flaws and defects in product parts. However, industrial settings pose several challenges: diverse categories, limited abnormal samples, and vagueness. Hence, there is a growing demand for advanced image anomaly detection techniques within industrial product manufacturing. In this paper, an intelligent industrial defective chips detection framework is proposed which mainly consists of three core components. First, the convolutional features of the efficient backbone model are effectively utilized to balance the computational complexity and performance of industrial resource-constrained devices. Secondly, a novel inverse feature matching followed by masking method is proposed to enhance the explainability that localizes the abnormal regions of the abnormal chips. Finally, to evaluate our proposed method a comprehensive ablation study is conducted, where different machine learning and deep learning algorithms are analyzed to claim the superiority of our method. Furthermore, to help the research community, a benchmark dataset is collected from real-world industry manufacturing for defective chip detection. The empirical results from the dataset demonstrate the strength and effectiveness of the proposed model compared to the other models.

## 📂 Repository Files

```text
├── GridCame_Training.py     # Training script
├── GridCame_Testing.py      # Testing and evaluation script
└── README.md                # Project documentation
```
The dataset used in this study was collected from real-world industrial manufacturing environments.

### Dataset Access
To acquire the dataset, please send a request to:

📧 altafh3797.com

### Dataset Organization

Arrange the dataset in the following structure:

```text
dataset/
├── normal/
└── abnormal/
```

- `normal/` contains non-defective chip images.
- `abnormal/` contains defective chip images.
