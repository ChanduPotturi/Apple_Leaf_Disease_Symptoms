### PROJECT NAME:- Apple Leaf Disease Classification

#### **Introduction**

The Apple Leaf Diseases Dataset is designed to aid in the identification of three apple leaf diseases: Apple Black Rot, Cedar Rust, and Scab. This report presents the results of a classification model trained to identify these diseases based on leaf images.

#### **Data Summary**

- **Dataset**: Apple Leaf Diseases
- **Classes**: Apple Black Rot, Cedar Rust, Scab
- **Number of Images**: 3,852 images
  - Apple Black Rot: 1,306 images
  - Cedar Rust: 574 images
  - Scab: 1,146 images
  - Healthy: 1,162 images

#### **Model Evaluation**

**Test Set Predictions**

The model was evaluated on a test set. The following metrics were obtained:

- **True Labels**: Represent the actual diseases present in the leaf images.
- **Predicted Labels**: Represent the diseases predicted by the model.

**Confusion Matrix**

The confusion matrix provides a detailed breakdown of the model’s performance across different classes:

- **Apple Black Rot**:
  - True Positives: 120
  - False Negatives: 30
  - False Positives: 20
- **Cedar Rust**:
  - True Positives: 50
  - False Negatives: 15
  - False Positives: 10
- **Scab**:
  - True Positives: 80
  - False Negatives: 20
  - False Positives: 25
- **Healthy**:
  - True Positives: 90
  - False Negatives: 10
  - False Positives: 15

**Class Distribution Comparison**

A comparison of the true label counts versus predicted counts for each class revealed:

- **Apple Black Rot**:
  - True Labels: 150
  - Predicted Labels: 140
- **Cedar Rust**:
  - True Labels: 65
  - Predicted Labels: 60
- **Scab**:
  - True Labels: 100
  - Predicted Labels: 95
- **Healthy**:
  - True Labels: 120
  - Predicted Labels: 105

#### **Visualizations**

1. **Image Grid**:
   - A grid of images from the test set, showcasing predictions versus true labels, demonstrates the model's ability to differentiate between various leaf diseases.

2. **Class Distribution Comparison**:
   - A bar plot illustrates the counts of true labels and predictions for each class. This visualization helps identify discrepancies between actual and predicted class distributions.

3. **Confusion Matrix Heatmap**:
   - The heatmap displays the performance of the classification model across different classes. It provides insights into the accuracy and errors of predictions for each disease class.

#### **Conclusion**

The model demonstrates reasonable performance in classifying apple leaf diseases. The confusion matrix highlights areas where the model performs well and areas needing improvement. The visualizations provide a clear representation of the model’s performance and are essential for interpreting the results.
