# Smart Diet Device – Sections B, C & D

This project covers implementation for:

- **Section B:** Computer Vision & Food Recognition  
- **Section C:** Market Research Data Collection & Analysis  
- **Section D:** Sentiment Analysis & User Behavior Prediction  

## 🔧 Technologies Used

- Python
- TensorFlow & Keras
- OpenCV
- Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 Folder Structure

```
project/
│
├── food_dataset/                         # Image dataset for CNN training
├── smart_diet_device_B_C_D_implementation.ipynb
├── food_cnn_model.h5                     # Trained CNN model
├── food_cnn_model.keras                  # Alternate model format
├── random_forest_salt_predictor.pkl      # Trained model to predict salt levels
├── updated_food_nutrition_data.xlsx      # Nutrition data
├── smart_spoon_feedback_analyzed.xlsx    # Feedback analysis
├── smart_spoon_survey_results.xlsx       # Survey results
├── smart_spoon_sentiment.png             # Visualization
├── feedback_sentiment.png                # Sentiment analysis output
├── requirements.txt                      # Python dependencies
└── README.md                             # Project description (this file)
```

## ▶️ How to Run

1. Clone or extract the entire folder.
2. Ensure the `food_dataset` folder is in the same directory as the notebook.
3. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch the notebook:
   ```bash
   jupyter notebook smart_diet_device_B_C_D_implementation.ipynb
   ```

> ⚠️ All paths used are **relative**. Avoid changing the folder structure.

## 📌 Notes

- CNN is used to identify food types and predict salt content.
- Survey & feedback data is used for market research and sentiment insights.
- Final models are stored in `.h5`, `.keras`, and `.pkl` formats.
