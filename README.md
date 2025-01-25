🩻 AI-Powered X-Ray Diagnosis Using CNN + RNN
This project integrates Convolutional Neural Networks (CNNs) for feature extraction and Recurrent Neural Networks (RNNs) for medical text generation to enable automated X-ray disease diagnosis. It utilizes Grad-CAM for explainability and Gradio for an intuitive web-based interface.

🚀 Key Features
✅ Upload X-ray images for automated disease detection
✅ Utilizes EfficientNetB0 (CNN) for feature extraction
✅ Implements LSTM (RNN) to generate medical impressions
✅ Integrates Grad-CAM for visual model explainability
✅ Provides bounding boxes for detected abnormalities
✅ User-friendly Gradio interface for interactive testing

📂 Dataset Information
This project uses the Indiana University Chest X-ray Dataset, which contains chest X-rays paired with radiology reports.

🔗 Dataset Link:
Kaggle - Indiana University Chest X-rays

🔍 Model Architecture
The system follows this structured pipeline:

Feature Extraction (CNN): Extracts important X-ray features
Disease Classification: Identifies abnormalities in the X-ray
Grad-CAM: Highlights critical regions influencing model decisions
Caption Generation (RNN): Generates medical text impressions
Superimposed Output: Displays Grad-CAM overlays for clarity
Results Display: Provides diagnosis, heatmap, and report
🎯 Evaluation Metrics
📊 The performance of the system is measured using:
✅ CNN Disease Classification Accuracy
✅ BLEU Score for RNN-based Captioning
✅ Grad-CAM Visual Analysis for Interpretability

🖼 Expected Output
Original X-ray Image
Grad-CAM Heatmap (Visualization of Focus Areas)
Superimposed X-ray (Highlighting Detected Regions)
Prediction Status (Example: "Atelectasis Detected ⚠️")
Generated Medical Impression (Text Summary)

🤝 Contributors
Mughilan KP – AI & ML Developer
Angelin Celena – AI & ML Enthusiast

🛠 Future Scope & Enhancements
🔹 Enhance accuracy using pre-trained transformers (BERT, ViT)
🔹 Deploy the model as a real-time cloud-based web app
🔹 Improve multi-class disease detection capabilities
🔹 Explore GAN-based X-ray data augmentation
