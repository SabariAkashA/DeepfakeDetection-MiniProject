## Detecting Digital Fraud: Real-Time Multi-Model Deepfake Identification
Real-time deepfake detection system using multi-model analysis to identify digital fraud, enhancing the accuracy and reliability of content verification across media platforms.

## About
This project addresses the growing challenge of deepfake detection in digital media by developing a real-time, multi-modal system capable of identifying synthetic content. The system utilizes a ResNext Convolutional Neural Network (CNN) for frame-level feature extraction, followed by an LSTM-based Recurrent Neural Network (RNN) to analyze temporal patterns across video frames. By combining these two models, the system effectively classifies videos as either deepfake or authentic. With OpenCV for frame processing and PyTorch for training, this approach leverages state-of-the-art deep learning techniques to detect artifacts in manipulated media, enhancing digital fraud prevention in diverse applications.
## Features
1.  Instantly identifies manipulated media in video content.
2.  Combines CNN and RNN for accurate video classification.
3.  Uses ResNext CNN for detailed feature extraction.
4.  LSTM RNN detects inconsistencies across video frames.
5.  Processes frames with OpenCV for efficient analysis.
6.  Trained with PyTorch for precise and scalable deepfake detection. 

## Requirements:
* **Operating System**: Requires a 64-bit OS (Windows 10, Ubuntu 18.04 or later) compatible with deep learning frameworks.
* **Development Environment**: Python 3.8 or later is recommended for implementing the deepfake detection system.
* **Deep Learning Frameworks**: PyTorch for model training, with CUDA support for GPU acceleration if available.
* **Image Processing Libraries**: OpenCV for processing video frames and performing real-time analysis.
* **Version Control**: Git for collaborative development and version management.
* **IDE**: Visual Studio Code (VSCode) or Jupyter Notebook for code writing, debugging, and experimentation.
* **Additional Dependencies**: Includes scikit-learn, PyTorch (with GPU support), OpenCV, and any other required libraries for handling video and deep learning tasks.

## System Architecture
<img src=https://github.com/user-attachments/assets/41d92eca-1487-46ba-ad4b-68854ecceb34 width=500 height=500>

## Output
#### Output1 - Real Video:
<img src=https://github.com/user-attachments/assets/48dc1f6c-7157-4597-9603-35b06f133d1e width=500 height=500>

#### Output2 - Fake Video:
<img src=https://github.com/user-attachments/assets/18fe3c31-898b-4424-bb55-dc1e62100114 width=500 height=500>

**Detection Accuracy: 97.76180%**<br>
**Note:** These metrics can be customized based on your actual performance evaluations.


## Results and Impact
This project tackles the growing challenge of deepfake detection in digital media by developing a real-time, multi-modal system designed to identify synthetic content. The system leverages a ResNext Convolutional Neural Network (CNN) for frame-level feature extraction, followed by an LSTM-based Recurrent Neural Network (RNN) to capture and analyze temporal patterns across video frames. By combining these two advanced models, the system effectively classifies videos as either deepfake or authentic.

Utilizing OpenCV for frame processing and PyTorch for model training, this approach incorporates cutting-edge deep learning techniques to detect artifacts in manipulated media. Its application enhances digital fraud prevention, offering valuable solutions for safeguarding authenticity in various media platforms.

## Articles published / References
[1] Yuezun Li, Siwei Lyu, “ExposingDF Videos By Detecting Face Warping Artifacts,” in arXiv:1811.00656v3.

[2] Yuezun Li, Ming-Ching Chang and Siwei Lyu “Exposing AI Created Fake Videos by Detecting Eye Blinking” in arxiv. 

[3] Huy H. Nguyen , Junichi Yamagishi, and Isao Echizen “ Using capsule networks to detect forged images and videos ”. 

[4] Hyeongwoo Kim, Pablo Garrido, Ayush Tewari and Weipeng Xu “Deep Video Portraits” in arXiv:1901.02212v2.

[5] Umur Aybars Ciftci, ˙Ilke Demir, Lijun Yin “Detection of Synthetic Portrait Videos using Biological Signals” in arXiv:1901.02212v2.

