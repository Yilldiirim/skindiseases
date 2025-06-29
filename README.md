# skindiseases
Skin Disease Classification with Deep Learning
Deep Learning-based Automatic Diagnosis of Skin Lesions
 
📌 Overview
Skin diseases are among the most common health problems worldwide and can significantly reduce patients' quality of life if not diagnosed early.
In this study, we aimed to evaluate the performance of deep learning models in the automatic classification of skin lesions, and we also developed an interactive Flask-based web application that allows real-time predictions.
 
🗂 Dataset
Public dataset with ~12,500 skin images
11 disease classes:
Atopic Dermatitis, Basal Cell Carcinoma, Benign Keratosis, Eczema, Melanocytic Nevi, Melanoma, Pigmented Benign Keratosis, Psoriasis/Lichen Planus, Seborrheic Keratosis, Tinea, and Wart/Molluscum.

⚙️ Methods
Image Preprocessing: resizing, CLAHE, histogram equalization, denoising, sharpening
Data Augmentation: applied for better generalization
Transfer Learning: used architectures such as MobileNet, ResNet50, EfficientNetB3, DenseNet121, ViT, ConvNeXt
Training: optimized with Adam optimizer and categorical crossentropy

📊 Results
MobileNet achieved the highest test accuracy with 86%
Performance evaluated with accuracy, precision, recall, and F1-score

🌐 Web Application
We built a user-friendly Flask-based web interface where users can upload skin images and receive instant disease predictions powered by the trained model.

 
📄 Notes
This project demonstrates the potential of deep learning methods in dermatological diagnosis and provides a foundation for clinical integration.



Author
Muhammet Yıldırım
 Contact: mhtyildirim00@gmail.com
