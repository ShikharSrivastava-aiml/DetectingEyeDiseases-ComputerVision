Abstract— The classification of eye diseases, including Normal, Diabetic Retinopathy, Cataract, and Glaucoma, plays a crucial role in early diagnosis and treatment planning. This study presents a comprehensive approach to automate the classification process using image processing, machine learning, and deep learning techniques. Various features are extracted from the images, including entropy, moments, and region properties, to characterize different aspects of the eye conditions. Machine learning algorithms such as Random Forest classifier, Logistic Regression, and multilayer perceptron models are employed to predict the class labels based on the extracted features.
Furthermore, deep learning models, particularly two Convolutional Neural Network (ResNet – 18 and a customized CNN), are applied directly to the image data for classification. The effectiveness of different methods is assessed in terms of accuracy, sensitivity, and specificity, providing valuable insights into the performance of each approach. The proposed system not only facilitates accurate classification of eye diseases but also holds potential for aiding healthcare professionals in identifying infected cells promptly, which can significantly impact disease management and patient outcomes. This research contributes to the advancement of machine learning and deep learning techniques in medical image analysis, offering a promising avenue for early disease detection and intervention.

I. INTRODUCTION

This study addresses the crucial task of classifying various eye conditions using a multifaceted approach that integrates image processing, machine learning, and deep neural networks. The dataset under consideration consists of a diverse collection of retinal images, encompassing classes such as Normal, Diabetic Retinopathy, Cataract, and Glaucoma, each comprising approximately 1000 images.
The proposed system begins by converting the RGB retinal images into 2-dimensional grayscale representations to facilitate the subsequent feature extraction process. Utilizing a range of filters, including but not limited to those for Entropy, Shannon-Entropy, moments, and region properties, the system extracts rich and discriminative features from the retinal images. This feature extraction stage is pivotal in capturing relevant information pertinent to the different eye conditions present in the dataset. Subsequently, these extracted features are harnessed within the framework of various machine learning algorithms, including Random Forest, Logistic Regression, and multi-layer perceptron models, for binary classification. Leveraging the distinctive characteristics of each algorithm, the system endeavors to discern patterns within the feature space that delineate the different eye conditions with a high degree of accuracy.
Notably, the system attains commendable performance metrics, achieving accuracy rates of 82.86%, 79.68%, and 83.26% for the Random Forest, Logistic Regression, and multi-layer perceptron model, respectively. Furthermore, to enhance the classification prowess, a Convolutional Neural Network Res-Net 18 is incorporated, yielding an accuracy of 84.20% and a custom-CNN yielding an accuracy of 94.31% in classifying the retinal images. The system's utility extends to providing valuable insights into the presence of eye conditions within the retinal images, thereby facilitating early disease detection and diagnosis. This automated approach, which seamlessly integrates image processing techniques with sophisticated machine learning algorithms, represents a significant advancement in the realm of ophthalmological diagnostics.
Moreover, owing to its portability and user-friendly design, the proposed system holds promise for widespread deployment in healthcare settings, offering clinicians and medical practitioners a reliable and efficient tool for expeditious and accurate diagnosis of various eye
2 diseases. Thus, the amalgamation of image processing, artificial intelligence, and machine learning techniques presents a compelling solution to the intricate task of eye condition classification, with profound implications for improving patient care and treatment outcomes in the field of ophthalmology.

Figure 1
Deployment of Model on a Web Applicalication which correctly predicts the input image as an eye infected with Cataract.

![image](https://github.com/user-attachments/assets/e3121c49-7d68-4552-b12c-49d5544fe1a8)

Figure 2
Deployment of Model on a Web Applicalication which correctly predicts the input image as an eye infected with Glaucoma.

![image](https://github.com/user-attachments/assets/851629d6-3153-4f37-b917-c1f31a369cc4)

