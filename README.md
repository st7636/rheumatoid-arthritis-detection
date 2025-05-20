# rheumatoid-arthritis-detection
This project aims to detect Rheumatoid Arthritis (RA) from X-ray images using deep learning techniques. The model classifies images as healthy or rheumatoid, and for RA cases, it further predicts the stage of the disease: Doubtful, Mild, Moderate, or Severe.
Problem Statement
Rheumatoid Arthritis is a chronic inflammatory disorder that can cause joint damage and disability if not detected early. Manual detection is time-consuming and subjective. This project provides an automated diagnostic tool using deep learning to assist radiologists and doctors.
📁 Project Structure
rheumatoid-arthritis-detection/
├── datasets/
│   ├── healthy/
│   └── rheumatoid/
├── model/
│   └── vgg16_ra_classifier.h5
├── rheumatoid_detection.ipynb
├── app_interface.py
├── requirements.txt
└── README.md
 Model Used
VGG16 (Pretrained on ImageNet and fine-tuned)
Input size: 224x224
Image preprocessing: CLAHE for contrast enhancement
Accuracy: ~90% (Test accuracy between 80-90%)
📊 Evaluation Metrics
Accuracy
Precision
Recall
F1-score
🛠 Tools & Technologies
Python
TensorFlow / Keras
OpenCV
Jupyter Notebook
Streamlit (for the application interface)
🖼 Sample Output
Upload an X-ray → Model predicts: Rheumatoid - Stage: Moderate

📌 Future Scope
Expand to include more imaging modalities

Integrate with clinical EHR systems

Improve multi-stage accuracy with larger datasets
