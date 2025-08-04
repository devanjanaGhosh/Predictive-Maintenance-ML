# 🔧 Predictive Maintenance of Industrial Machinery

This project aims to predict potential machine failures in industrial settings using real-time sensor data and machine learning, enabling proactive maintenance and minimizing operational disruptions.

## 📌 Problem Statement

Traditional reactive maintenance leads to unexpected machinery breakdowns, costly downtime, and inefficiencies. This project predicts failures like tool wear, overheating, and power failure using predictive analytics to shift industries toward proactive, condition-based maintenance.

## 🚀 Proposed Solution

A cloud-based machine learning system built using IBM Watson Studio and AutoAI to automate model selection, training, evaluation, and deployment. The trained model is deployed as a REST API for real-time predictions.

## 🛠️ Tech Stack

- **Platform**: IBM Cloud Lite, IBM Watson Studio
- **ML Tool**: AutoAI (Snap Random Forest Classifier)
- **Languages/Libraries**: Python, Pandas, Scikit-learn, Matplotlib
- **Deployment**: REST API on IBM Cloud
- **Dataset**: [Kaggle - Machine Predictive Maintenance](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)

## 📈 Model Performance

- **Algorithm**: Snap Random Forest Classifier
- **Accuracy**: 99.7% (Holdout score)
- **Evaluation**: Confusion matrix, ROC curves, precision-recall analysis

## ⚙️ System Workflow

1. **Data Collection** – Sensor data (temperature, torque, speed, etc.)
2. **Preprocessing** – Null handling, normalization, feature selection
3. **Model Training** – AutoAI selected best model automatically
4. **Deployment** – REST API for real-time predictions
5. **Monitoring** – Predict failure type and confidence score

## ✅ Results

- Highly accurate model with strong generalization
- Real-time alerts via REST API
- Easy integration with dashboards and monitoring tools

## 🔮 Future Scope

- Use LSTM/GRU for time-series failure prediction
- Deploy models on edge devices for low-latency response
- Integrate multimodal data (sound, image) for deeper diagnostics
- Develop real-time dashboards on IBM Cloud

## 📚 References

- Kaggle Dataset: [Predictive Maintenance](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
- [IBM Watson Studio Docs](https://cloud.ibm.com/docs/watson-studio)
- [AutoAI Overview](https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/autoai-overview.html)
