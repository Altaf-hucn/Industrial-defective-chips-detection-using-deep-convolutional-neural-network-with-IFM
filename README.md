# Industrial Defective Chips Detection using Deep Convolutional Neural Network with Inverse Feature Matching Mechanism

**Paper Title**: Industrial Defective Chips Detection using Deep Convolutional Neural Network with Inverse Feature Matching Mechanism  
**Published in**: *Journal of Computational Design and Engineering*  
**DOI**: [https://doi.org/10.1093/jcde/qwae019](https://doi.org/10.1093/jcde/qwae019)  
**Online Link**: [Read the full paper here](https://academic.oup.com/jcde/article/11/3/326/7611698)

---

## Abstract

The growing demand for high-quality industrial products has led to a significant emphasis on image anomaly detection (AD). AD in industrial goods presents a formidable research challenge that demands the application of sophisticated techniques to identify and address deviations from the expected norm accurately. Manufacturers increasingly recognize the significance of employing intelligent systems to detect flaws and defects in product parts. However, industrial settings pose several challenges: diverse categories, limited abnormal samples and vagueness. Hence, there is a growing demand for advanced image AD techniques within industrial product manufacturing. In this paper, an intelligent industrial defective chips detection framework is proposed which mainly consists of three core components. First, the convolutional features of the efficient backbone model is effectively utilized to balance the computational complexity and performance of industrial resource-constrained devices. Secondly, a novel inverse feature matching followed by masking method is proposed to enhance the explanability that localizes the abnormal regions of the abnormal chips. Finally, to evaluate our proposed method a comprehensive ablation study is conducted, where different machine learning and deep learning algorithms are analysed to claim the superiority of our method. Furthermore, to help the research community, a benchmark dataset is collected from real-world industry manufacturing for defective chip detection. The empirical results from the dataset demonstrate the strength and effectiveness of the proposed model compared to the other models.
---

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-repo/defective-chip-detection.git
    ```
2. Navigate to the project directory:
    ```bash
    cd defective-chip-detection
    ```
3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

---

## Usage

1. **Data Preparation**: Place your dataset in the `data/` folder. The dataset should be structured as follows:
    ```
    data/
        train/
            normal/
            abnormal/
        test/
            normal/
            abnormal/
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

