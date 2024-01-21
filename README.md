# Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning
X-RAY 사진 판독 AI 진단 모델 - 인공지능을 활용한 비지도 학습 기반 폐렴 예측 (Deep Learning)


![x-ray](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/6a5407c3-54c9-465d-8523-4d39c2c8e482)
​

## 1. Project Overview (프로젝트 개요)

This project aims to develop a deep learning model that diagnoses and predicts pneumonia from human lung and chest X-ray images using artificial intelligence technology. The research focuses on unsupervised learning, a branch of machine learning, and aims to explore the effectiveness of artificial intelligence in medical image analysis by utilizing Convolutional Neural Networks (CNN) for various image types.

**※ Project Duration: October 16, 2023 (Total 16h)**

​

## 2. Technical Approach (기술적 접근법)

The project implements key steps using Python and the following libraries:


**(1) Data Collection:** X-ray images are segmented into training, validation, and test datasets.

​![1](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/14db077b-6b0b-4365-b6d6-dbddf33ca00e)


**(2) Data Visualization:** The shape of the images is examined, and matplotlib is used for visual representation.

**(3) Data Preprocessing:** Data normalization and label encoding are performed using OpenCV.

![2](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/a5041267-cdbc-4489-9ea3-46e17d1681bd)
​

**(4) Model Construction:** CNN models are built using TensorFlow and Keras, focusing on feature extraction and pattern recognition for pneumonia diagnosis.

​![3](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/b25af4e7-a094-4ae9-82e3-505ef5fa0a39)


**(5) Training and Evaluation:** The created model is trained with the training dataset and evaluated using the validation dataset.

​![4](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/797fe782-4a20-4a5c-95e0-1f31607aa646)




## 3. Challenges and Achievements in the Project (도전과 성과)

The biggest challenge in this project was securing high-quality data and effectively applying it to the model. Data augmentation and normalization techniques were utilized to enable the model to perform more precise predictions. The CNN model achieved considerable accuracy with the validation dataset.

![5](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/e0e393ef-7d95-45c7-a619-645889acf21c)

​
## 4. Shortcomings in the Results (결과에서dml 아쉬운 점)

Based on the provided results, the CNN model achieved relatively high accuracy with the validation dataset, but significant observations also emerged.

**(*) Fluctuating Validation Loss:**
 **→** The validation loss (val_loss) was very high in the first and second epochs, indicating that the model was not well generalized to the validation dataset at those epochs.



## 5. Improvements and Reflections (개선사항 및 느낀점)

- **Improvement:** There was a need for more diversity and quantity in the data, and future efforts will explore a wider range of data sources. Additionally, further hyperparameter tuning is necessary to enhance the model's generalization capability.

- **Reflection:** Witnessing the potential of artificial intelligence in medical image analysis, this research provided an opportunity to deeply consider how the fusion of technology and medicine can positively impact humanity. This research has laid the foundation for applications in high-resolution medical image restoration, real-time diagnostic systems, and medical data analysis tools. The advancements in AI technology are expected to enhance the accuracy of medical diagnoses and improve patients' quality of life.

​![6](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/fe9b3f4f-b6b9-4a4c-9601-67b10fc4cff4)




## 6. Future Prospects and Goals (향후 전망 및 목표)

This project has provided a foundation for basic research on the future direction of image colorization technology. Moving forward, more data and various network structures will be experimented with to improve the model's generalization capabilities.

​
## 7. Dataset Source (데이터셋 출처 자료)

Intel® AI for Future Workforce Program

​![사진](https://github.com/pixelwizard2/Project.CV--RadiAI---AI-Based-Pneumonia-Prediction-from-X-Ray-Images-using-Unsupervised-Learning/assets/138272416/8e05f593-337e-48ae-aa5a-5076736a94c9)


## 8. References (참고자료)

- Official documentation of Python, TensorFlow, Keras, OpenCV

- Related academic papers and case studies in medical data analysis

