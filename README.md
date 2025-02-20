# Sentiment Analysis on IMDb Reviews using LSTM

## 📌 Project Overview
This project focuses on **Sentiment Analysis** of IMDb movie reviews using **Long Short-Term Memory (LSTM)** networks. The model classifies reviews as **positive or negative** based on textual data, providing a deeper understanding of audience opinions.

## 🚀 Features
- **Deep Learning-based Sentiment Analysis** using LSTM
- **Text Preprocessing**: Tokenization, Padding, and Word Embeddings
- **Model Evaluation**: Accuracy, Precision, Recall, and F1-score
- **Interactive Visualization** of results


## 📊 Workflow Diagram


    +-----------------+       +------------------+          +------------------+
    |  Data Loading  | ----> |  Text Preprocessing  | ----> |  Model Training  |
    +-----------------+       +------------------+          +------------------+
                                         |        
                                         v     
                      +--------------------------------------+
                      |  Performance Evaluation & Analysis  |
                      +--------------------------------------+
                                         |
                                         v     
                            +----------------------------+
                            |  Sentiment Classification  |
                            +----------------------------+




## 📂 Dataset
- **IMDb Dataset**: Contains **50,000** movie reviews.
- Balanced dataset: **25,000** positive & **25,000** negative reviews.



## 🔧 Technologies Used
- **Programming Language**: Python 🐍
- **Deep Learning Framework**: TensorFlow, Keras
- **Libraries**: NumPy, Pandas, Matplotlib, Seaborn, NLTK, scikit-learn



## 🛠 Model Architecture
- **Embedding Layer**: Converts words into vector representations
- **LSTM Layer**: Captures long-term dependencies in text
- **Dense Layers**: Fully connected layers for classification



## 📈 Performance Metrics
- **Accuracy**: ~90%
- **Precision, Recall, F1-score**: Evaluated on test data
- **Confusion Matrix Analysis**



## 🎯 Future Enhancements
- Deploying the model as a web-based sentiment analysis tool
- Expanding to multi-class sentiment analysis (e.g., neutral reviews)
- Incorporating Transformer models like BERT for improved accuracy



## 📌 How to Run
1. Clone the repository:  
   git clone https://github.com/alimgty/Miniproject-2nd-Year---Sentimental-Analysis-on-Movie-Rating-Predictions-using-LSTM
   
2. Install dependencies:  
   pip install -r requirements.txt

3. Run the script:  
   python sentiment_analysis.py
   

---



