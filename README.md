# E-Commerce-clothing-Classification-System-CNN-Streamlit-
AI-based clothing classification system for e-commerce using deep learning (MobileNetV2). Supports single-image prediction and batch catalog organization with a Streamlit dashboard.
This project presents an AI-based clothing classification system for e-commerce platforms using deep learning and computer vision. The system automatically classifies clothing images into product categories and organizes catalogues efficiently.
Manual product classification is time-consuming and inconsistent for large online stores. This project solves that problem using a Convolutional Neural Network (CNN) model trained on the DeepFashion dataset to automate product categorization.
The system supports both single-image classification and batch processing for large-scale e-commerce catalogues.
 
🚀 Features

•	Deep learning-based clothing classification
•	Multi-label classification support
•	Single image prediction
•	Batch image processing
•	Automatic folder organization
•	Confidence score visualization
•	Streamlit web dashboard
•	CSV report generation
•	Scalable catalog automation
 
🧠 Model Details

•	Architecture: MobileNetV2 CNN
•	Transfer Learning from ImageNet
•	Multi-label classification using Sigmoid activation
•	Binary Cross-Entropy loss
•	Optimized for lightweight deployment
The model is designed to provide high accuracy while remaining computationally efficient, making it suitable for real-world e-commerce applications.
 


📊 Dataset

The model is trained on a subset of the DeepFashion-MultiModal dataset.
Dataset characteristics:
•	~34,000+ images
•	High-resolution clothing images
•	Real-world product photos
•	Multiple clothing categories
Categories include:
•	Women's Tops
•	Women's Dresses
•	Women's Sweatshirts
•	Women's Jackets
•	Men's T-Shirts
•	Men's Shirts
 
⚙️ System Workflow
Single Image Mode
1.	Upload an image
2.	Image preprocessing (resize & normalization)
3.	CNN prediction
4.	Category output
5.	Confidence scores visualization
Batch Processing Mode
1.	Provide folder path
2.	Process all images
3.	Classify automatically
4.	Sort into category folders
5.	Generate reports
 
🖥️ Streamlit Dashboard

The project includes an interactive Streamlit dashboard with:
•	Model status indicator
•	Sensitivity (confidence threshold) control
•	Single-image classification
•	Batch catalog organizer
•	Real-time results
•	Downloadable reports
 
📈 Results

The model achieves:
•	~96% classification accuracy
•	High precision and recall
•	Fast inference speed
•	Efficient batch processing
The system significantly reduces manual effort and improves catalog consistency.
 
🛠️ Tech Stack

•	Python
•	TensorFlow / Keras
•	OpenCV
•	NumPy
•	Pandas
•	Matplotlib
•	Streamlit

  
🔮 Future Work
•	Attribute prediction (color, material, style)
•	Real-time API deployment
•	Active learning
•	Explainable AI integration
 


