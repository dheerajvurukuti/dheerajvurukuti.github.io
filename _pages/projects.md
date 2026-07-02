---
title: "Projects"
layout: archive
permalink: /projects/
author_profile: false
---

### Transformer-Based Malware Detection

A separate research experiment extending the uncertainty-aware theme from my thesis, this time using a Transformer architecture applied to Smali bytecode from the Androzoo dataset, testing whether attention-based models could match or surpass the DKL approach on Android malware classification.

- Developed a **BERT-based model** on Smali code achieving an **AUT score of 0.92**, surpassing baseline methods
- Implemented **selective prediction** to issue confident predictions only, reducing incorrect classifications
- Applied **active learning** to focus on uncertain samples, improving performance while minimizing labeled data requirements
- Used **conformal prediction** to provide statistically valid confidence intervals for security-critical decisions
- Evaluated against concept drift with retraining strategies to maintain accuracy as data distributions evolved

---

### Real-Time Object Detection iOS App &nbsp;[[code]](https://github.com/dheerajvurukuti/Object_Detector_iOS_App/tree/main/Object%20Detector/Object%20Detector) [[demo]](https://github.com/dheerajvurukuti/Object_Detector_iOS_App/blob/main/Object_Detection.pptx)

An iOS app built to explore on-device ML inference with CoreML and SwiftUI, combining real-time camera-based object detection with Firebase-backed authentication and session logging. All inference runs locally on-device with no image data sent to external servers.

- Built with **Xcode**, **Swift**, and **SwiftUI** with a clean, intuitive interface
- Integrated a pre-trained **ResNet model** via **Core ML** for smooth, responsive on-device object detection
- Implemented **Google Firebase** authentication with email/password and Google Sign-In
- Used **Firebase Firestore** to store user-specific detection logs and session history

---

### Human Activity Recognition &nbsp;[[code]](https://github.com/dheerajvurukuti/Human_Activity_Recognition_using_LSTM-CNN/blob/main/Human_Activity_Recognition_using_LSTM-CNN.ipynb) [[pdf]](https://github.com/dheerajvurukuti/Human_Activity_Recognition_using_LSTM-CNN/blob/main/Human_Activity_Recognition_using_LSTM-CNN.pdf)

A study in spatiotemporal modeling using a hybrid CNN-LSTM architecture to classify human activities from video frames. CNNs capture spatial features per frame while LSTMs model the temporal sequence across frames, achieving a confidence score of **89.8%**.

- Designed a **CNN-LSTM hybrid** to capture both spatial appearance and temporal dynamics across video sequences
- Demonstrated that the hybrid model outperforms traditional ML approaches in extracting activity features
- Visualized predictions using YouTube video frames

---

<!--
### Exploratory and Predictive Analysis of Health Outcomes &nbsp;[[code]](https://github.com/dheerajvurukuti/Exploratory-and-Predictive-Analysis-of-Health-Outcomes-Coronary-Heart-Disease-and-Diabetes/blob/main/Exploratory%20and%20Predictive%20Analysis%20of%20Health%20Outcomes.ipynb) [[pdf]](https://github.com/dheerajvurukuti/Exploratory-and-Predictive-Analysis-of-Health-Outcomes-Coronary-Heart-Disease-and-Diabetes/blob/main/Exploratory%20and%20Predictive%20Analysis%20of%20Health%20Outcomes.pdf)

- Conducted exploratory and predictive analytics to uncover insights about **Coronary Heart Disease (CHD)** and **Diabetes** using ML techniques.
- Applied **five distinct algorithms** to predict susceptibility based on features like age, gender, and BMI using diverse demographic and health datasets.
- Achieved a **cross-validation score of 85.7%**.

---

### Virtual Painter &nbsp;[[code]](https://github.com/dheerajvurukuti/VIRTUAL-PAINTER-USING-OPENCV/tree/main/VIRTUAL%20PAINTER%20USING%20OPENCV%20code) [[pdf]](https://github.com/dheerajvurukuti/VIRTUAL-PAINTER-USING-OPENCV/blob/main/VIRTUAL%20PAINTER%20USING%20OPENCV.pdf)

- Developed an interactive painting application controlled entirely by **hand gestures via webcam**.
- Implemented using **OpenCV** and **MediaPipe** for real-time hand tracking, object detection, and skeletal tracking.

---

### Stock Recommendation System &nbsp;[[code]](https://github.com/dheerajvurukuti/Stock_Recommendation/blob/main/Stock_Recommendation_code.py) [[pdf]](https://github.com/dheerajvurukuti/Stock_Recommendation/blob/main/Stock%20Recommendation%20based%20on%20Price%20Forecasting%20and%20Twitter%20Sentiment%20Analysis.pdf)

- Built a **stock recommendation engine** combining **price forecasting** and **Twitter sentiment analysis**.
- Used **Random Forest Regressor** for price prediction and **Sentiment Intensity Analyzer** to gauge market sentiment from tweets.
- Achieved a prediction **accuracy of 78.4%**.

---

### Stock Price Analysis &nbsp;[[code]](https://github.com/dheerajvurukuti/STOCK_PRICE_ANALYSIS/blob/main/stock_price_prediction.py) [[pdf]](https://github.com/dheerajvurukuti/STOCK_PRICE_ANALYSIS/blob/main/Stock%20Price%20Analysis%204%3A6%20CSSE%20B.Tech%20Project.pdf)

- Conducted time-series analysis using **Artificial Neural Networks (ANNs)** and **Recurrent Neural Networks (RNNs)** with **LSTM**.
- Evaluated model accuracy using backpropagation and standard evaluation metrics across multiple datasets.
-->
