# Naver Shopping Review Sentiment Classifier

This project aims to classify sentiment in Naver Shopping review data using a deep learning model with a Gated Recurrent Unit (GRU) network. The model categorizes the sentiment of reviews as either positive or negative.

## 🌟 Key Features

- **Data Preprocessing:** Clean and prepare Naver Shopping review data.
- **GRU-Based Model:** Implement a GRU-based text classification model.
- **Model Training & Evaluation:** Train the model and evaluate its performance.

## 🛠 Technologies Used

- **Python**
- **PyTorch**
- **Transformers** (Hugging Face)
- **pandas**
- **scikit-learn**

## 📦 Dataset

The project utilizes the Naver Shopping review dataset, which includes review texts and corresponding ratings.

## 🏗 Model Architecture

- **Embedding Layer:** Converts words into dense vectors.
- **Bidirectional GRU Layer:** Processes text sequences in both directions.
- **Fully Connected Layer:** Produces the final sentiment classification.

## 🚀 Installation

To install the required libraries, run:
```bash
pip install torch torchvision torchaudio transformers pandas scikit-learn
```
## 🚀 Usage

1. **Download and Preprocess Data:** Obtain and clean the dataset.
2. **Create Dataset & DataLoader:** Prepare the data for training.
3. **Initialize the Model:** Set up the GRU classifier.
4. **Train the Model:** Fit the model to the training data.
5. **Evaluate the Model:** Assess performance on the test set.

## 🧩 Main Components

- **`NaverShoppingDataset`**: Custom dataset class for handling review data.
- **`GRUClassifier`**: GRU-based text classification model.
- **`train_epoch`**: Function to train the model for one epoch.
- **`eval_model`**: Function to evaluate the model's performance.

## 📊 Performance

The model's accuracy and loss on the test set will be reported to evaluate its effectiveness.
