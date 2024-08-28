# Human Action Recognition (HAR) Using Key Point Detection and MobileNetV2

##  Aim

The objective of this research is to create a resilient and effective Human Action Recognition (HAR) system that precisely detects and categorizes human activities from images by using key point detection and the MobileNetV2 deep learning architecture. The system will utilize the Alpha Pose model for accurate identification of specific landmarks on the human body and MobileNetV2 for efficient extraction and categorization of features. The project's goal is to achieve high precision in action recognition while maintaining computational efficiency, enabling the system to be deployed in real-time applications across different settings.

##  Objectives of the Project

- **Literature Review:** Perform an extensive examination of current studies on Human Action Recognition (HAR), focusing on identifying major obstacles and evaluating the efficacy of deep learning models, specifically MobileNetV2, in this domain.
- **Framework & Model Integration:** Develop a Python-based framework that integrates the Alpha Pose model for precise key point identification and employs the MobileNetV2 architecture to enhance the accuracy of the action recognition system. The goal of this integration is to provide a unified system that accurately identifies and categorizes human behaviors captured in images.
- **Performance Evaluation:** Assess the performance of the developed model by comparing it with other state-of-the-art models using standard evaluation metrics to determine its accuracy, efficiency, and robustness in identifying human actions.
- **Documentation and Reporting:** Produce a comprehensive report detailing the methodology, experimental setup, results, and conclusions. This report should provide valuable insights into the model development process, including challenges encountered and potential areas for future research.

##  Research Questions

- How can key point detection accuracy be optimized when integrated with MobileNetV2 for human action recognition?
- How does the integration of temporal information from key point sequences improve the action recognition capabilities of a MobileNetV2-based model?

## Methodology

The system will be built using the following steps:

1. **Data Collection:** Images of people performing various actions will be collected or sourced from an appropriate dataset.
2. **Key Point Detection:** Using the Alpha Pose model, key points on the human body (such as joints) will be detected and extracted from the images.
3. **Feature Extraction:** The MobileNetV2 architecture will be employed to extract features from the images, focusing on the key points identified by the Alpha Pose model.
4. **Model Training:** The extracted features will be used to train a deep learning model to recognize and categorize human actions.
5. **Performance Evaluation:** The model will be evaluated against other models using metrics such as accuracy and efficiency.

## How to Run the Code

### Prerequisites

Ensure you have the following packages installed:

- Python 3.11
- TensorFlow
- OpenCV
- Mediapipe
- Numpy
- Pandas
- Matplotlib
- TQDM

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/human-action-recognition.git
   cd human-action-recognition
2. Install the above libraries 
3. Open Jupyter notebook in the cloned location and run finalcode file
