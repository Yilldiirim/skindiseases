# Skin Disease Classification with Deep Learning

## Overview  
Skin diseases are among the most common health problems worldwide and can significantly reduce patients' quality of life if not diagnosed early. This study aims to evaluate the performance of deep learning models in the automatic classification of skin lesions, and we also developed an interactive Flask-based web application that allows real-time predictions.

## Dataset  
A public dataset with approximately 12,500 skin images was used, covering 11 disease classes:  
- Atopic Dermatitis  
- Basal Cell Carcinoma  
- Benign Keratosis  
- Eczema  
- Melanocytic Nevi  
- Melanoma  
- Pigmented Benign Keratosis  
- Psoriasis/Lichen Planus  
- Seborrheic Keratosis  
- Tinea  
- Wart/Molluscum

**The dataset is large and therefore not included directly in this repository. You can download it from the following link:**  
[Download Dataset from Google Drive](https://drive.google.com/drive/folders/1eeGRDOqdJXwd-doZow1pbIHSQ98TmQ2l?usp=drive_link)

## Methods  
- **Image Preprocessing:** resizing, CLAHE, histogram equalization, denoising, sharpening  
- **Data Augmentation:** applied for better generalization  
- **Transfer Learning:** architectures used include MobileNet, ResNet50, EfficientNetB3, DenseNet121, ViT, ConvNeXt  
- **Training:** optimized with Adam optimizer and categorical crossentropy loss

## Results  
- MobileNet achieved the highest test accuracy of 86%  
- Performance metrics include accuracy, precision, recall, and F1-score

## Web Application  
A user-friendly Flask-based web interface was developed where users can upload skin images and receive instant disease predictions powered by the trained model.

## Notes  
This project demonstrates the potential of deep learning methods in dermatological diagnosis and provides a foundation for clinical integration.

---

## Author  
Muhammet Yıldırım  
Contact: mhtyildirim00@gmail.com
