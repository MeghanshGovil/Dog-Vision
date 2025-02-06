# Dog Vision 🐶📷

Dog Vision is a deep learning-based image classification project that predicts dog breeds from images. The model is trained using TensorFlow and Keras, leveraging a convolutional neural network (CNN) architecture.

## 📌 Features

- Classifies dog images into different breeds.
- Uses transfer learning for better accuracy.
- Supports custom image predictions.
- Google Drive integration for dataset storage.

## 🛠 Setup Instructions

### 1️⃣ Clone the Repository

```sh
git clone https://github.com/your-username/Dog-Vision.git
cd Dog-Vision
```

### 2️⃣ Install Dependencies

```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook

Launch Jupyter Notebook and open `Dog_Vision.ipynb`:

```sh
jupyter notebook
```

## 📂 Repository Structure

```
Dog-Vision/
│── Dog_Vision.ipynb         # Main notebook for training & inference
│── README.md                # Project description & setup
│── requirements.txt         # Dependencies
│── data/                    # Folder for dataset (if needed)
│── models/                  # Folder for trained models
│── src/                     # Source code (if applicable)
│── utils/                   # Helper functions
│── .gitignore               # Ignore unnecessary files
```

## 🚀 Usage

### Train the Model

Run the notebook cells to train the model. Ensure your dataset is properly structured and stored in the `data/` folder.

### Make Predictions

Upload custom images and use the model to predict the dog breed:

```python
custom_preds = loaded_full_model.predict(custom_data)
```

## 📜 License

This project is open-source and available under the MIT License.

---

🔗 **Contributors:** Meghansh Govil

