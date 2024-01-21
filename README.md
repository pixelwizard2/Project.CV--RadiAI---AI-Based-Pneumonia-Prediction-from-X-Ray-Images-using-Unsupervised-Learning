# Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning
X-RAY 사진 판독 AI 진단 모델 - 인공지능을 활용한 비지도 학습 기반 폐렴 예측 (Deep Learning)


Project Main Title: Utilizing Deep Learning for Pneumonia Diagnosis

Project Subtitle: AI-ization of Pneumonia Diagnosis

​

Project Overview

This project aims to develop a deep learning model that diagnoses and predicts pneumonia from human lung and chest X-ray images using artificial intelligence technology. The research focuses on unsupervised learning, a branch of machine learning, and aims to explore the effectiveness of artificial intelligence in medical image analysis by utilizing Convolutional Neural Networks (CNN) for various image types.

[ ※ Project Duration: October 16, 2023 (Total 16h) ]

​

​

Technical Approach

The project implements key steps using Python and the following libraries:

​

Data Collection: X-ray images are segmented into training, validation, and test datasets.

​

Data Visualization: The shape of the images is examined, and matplotlib is used for visual representation.

Data Preprocessing: Data normalization and label encoding are performed using OpenCV.

​

Model Construction: CNN models are built using TensorFlow and Keras, focusing on feature extraction and pattern recognition for pneumonia diagnosis.

​

Training and Evaluation: The created model is trained with the training dataset and evaluated using the validation dataset.

​

Challenges and Achievements in the Project

The biggest challenge in this project was securing high-quality data and effectively applying it to the model. Data augmentation and normalization techniques were utilized to enable the model to perform more precise predictions. The CNN model achieved considerable accuracy with the validation dataset.

​

Shortcomings in the Results

Based on the provided results, the CNN model achieved relatively high accuracy with the validation dataset, but significant observations also emerged.

(*) Fluctuating Validation Loss:
 → The validation loss (val_loss) was very high in the first and second epochs, indicating that the model was not well generalized to the validation dataset at those epochs.


Improvements and Reflections

Improvement: There was a need for more diversity and quantity in the data, and future efforts will explore a wider range of data sources. Additionally, further hyperparameter tuning is necessary to enhance the model's generalization capability.

Reflection: Witnessing the potential of artificial intelligence in medical image analysis, this research provided an opportunity to deeply consider how the fusion of technology and medicine can positively impact humanity. This research has laid the foundation for applications in high-resolution medical image restoration, real-time diagnostic systems, and medical data analysis tools. The advancements in AI technology are expected to enhance the accuracy of medical diagnoses and improve patients' quality of life.

​

Future Prospects and Goals

This project has provided a foundation for basic research on the future direction of image colorization technology. Moving forward, more data and various network structures will be experimented with to improve the model's generalization capabilities.

​

Dataset Source

Intel® AI for Future Workforce Program

​

References

Official documentation of Python, TensorFlow, Keras, OpenCV

Related academic papers and case studies in medical data analysis

