# Industrial Defective Chips Detection using Deep Convolutional Neural Network with Inverse Feature Matching Mechanism

**Paper Title**: Industrial Defective Chips Detection using Deep Convolutional Neural Network with Inverse Feature Matching Mechanism  
**Published in**: *Journal of Computational Design and Engineering*  
**DOI**: [https://doi.org/10.1093/jcde/qwae019](https://doi.org/10.1093/jcde/qwae019)  

---
## Abstract

The growing demand for high-quality industrial products has led to a significant emphasis on image anomaly detection (AD). AD in industrial goods presents a formidable research challenge that demands sophisticated techniques to accurately identify and address deviations from the expected norm. Manufacturers increasingly recognize the importance of employing intelligent systems to detect flaws and defects in product parts.

However, industrial settings pose several challenges such as diverse categories, limited abnormal samples, and vagueness in anomalies. Hence, there is a growing demand for advanced image AD techniques within industrial product manufacturing.

In this paper, we propose an intelligent industrial defective chips detection framework consisting of three core components:

1. **Efficient Backbone Model**: Utilization of convolutional features from an efficient backbone model to balance computational complexity and performance for industrial resource-constrained devices.
2. **Inverse Feature Matching with Masking**: A novel inverse feature matching followed by a masking method is introduced to enhance explainability, localizing abnormal regions in defective chips.
3. **Comprehensive Ablation Study**: Different machine learning and deep learning algorithms are analyzed to demonstrate the superiority of the proposed method.

Additionally, a benchmark dataset collected from real-world industrial manufacturing for defective chip detection is provided. The empirical results demonstrate the effectiveness of the proposed model compared to other methods.

---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Altaf-hucn/Industrial-defective-chips-detection-using-deep-convolutional-neural-network-with-IFM.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Industrial-defective-chips-detection-using-deep-convolutional-neural-network-with-IFM
    ```
3. Install the required dependencies:
    ```bash
    pip install tensorflow-gpu==2.4.0 and tensorflow-estimator==2.4.0 
    ```

---

## Usage

1. **Data Preparation**: Place your dataset in the `data/` folder. The dataset should be structured as follows:
    ```
    Data/
        Train/
            Abnormal/
            Normal/
        Test/
            Abnormal/
            Normal/
    ```

2. **Training the Model**:
    ```bash
    python train.py --config config.yaml
    ```

3. **Evaluating the Model**:
    ```bash
    python evaluate.py --model model.pth --data data/test
    ```

---

## Dataset

A benchmark dataset for defective chip detection, collected from real-world industrial manufacturing, is available for research purposes. Please refer to the paper for details on how to access the dataset.

---

## Results

The results from our proposed method show a significant improvement in detecting defective chips compared to other machine learning and deep learning techniques. The ablation study confirms the effectiveness of each core component.

### Example Results

| Model                        | Accuracy | Precision | Recall  |
|------------------------------|----------|-----------|---------|
| Our Model (Proposed)          | 98.5%    | 97.2%     | 98.0%   |
| CNN Baseline                  | 93.1%    | 90.3%     | 92.0%   |
| SVM + Feature Extraction      | 85.6%    | 83.5%     | 84.2%   |

---

## Citation

If you find this repository useful in your research, please cite our paper:

