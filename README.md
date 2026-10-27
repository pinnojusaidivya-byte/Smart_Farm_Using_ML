 🌱 Smart Farm Using Machine Learning

 📌 Project Overview
Smart Farm Using Machine Learning is an agriculture-focused project designed to support farmers in making informed decisions using machine learning techniques.

The project currently includes two modules:
- Crop Recommendation: Recommends suitable crops based on soil nutrients and environmental conditions.
- Fertilizer Recommendation: Suggests suitable fertilizers based on soil properties, crop type, and environmental parameters.

 🎯 Objectives
- Apply machine learning to agricultural decision-making.
- Recommend suitable crops based on input parameters.
- Suggest appropriate fertilizers for different soil and crop conditions.
- Develop an accessible application for agricultural recommendations.

 🧩 Project Modules

 1. Crop Recommendation
- Uses soil nutrients: Nitrogen (N), Phosphorus (P), and Potassium (K).
- Considers temperature, humidity, pH, and rainfall.
- Includes trained classification models.
- Provides crop recommendations through a web application.

 2. Fertilizer Recommendation
- Uses soil and environmental parameters.
- Considers soil type and crop type.
- Uses a Random Forest classification approach.
- Provides fertilizer recommendations through a web application.

 🛠️ Technologies Used
- Python
- Machine Learning
- Scikit-learn
- Pandas
- NumPy
- Streamlit / [confirm framework used by each application]

 📂 Repository Structure

Smart_Farm_Using_ML/
│
├── CROP-RECOMMENDATION/
│   ├── Crop_recommendation.csv
│   ├── Crop_reccom(final).ipynb
│   ├── webapp.py
│   └── Trained model files
│
├── FERTILIZER-RECOMMENDATION/
│   ├── fertilizer_data.csv
│   ├── fertilizer_app.py
│   ├── fertilizer_model_train.py
│   └── fertilizer_model.pkl
│
└── README.md

1. Clone this repository.
2. Install the required dependencies from the respective module's `requirements.txt`.
3. Navigate to the module you want to run.
4. Run its application using the appropriate command.

 📚 Acknowledgements
We acknowledge the datasets, learning resources, and existing project references that helped us develop and customize this project.
