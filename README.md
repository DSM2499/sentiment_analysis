### Sentiment Analysis
## Motivation:

My drive to create this sentiment analysis model stemmed from a fascination with the power of natural language processing to decode human emotions from text. As social media continues to shape public discourse, I recognized the immense value in developing tools that can accurately interpret the sentiments expressed in tweets and other online communications.
    
This project offered an exciting opportunity to delve deep into the intricacies of text preprocessing and advanced neural network architectures, pushing the boundaries of my data science skills. By tackling the challenges of cleaning messy social media data and fine-tuning a complex model, I aimed to create a robust solution with real-world applications in market research, brand monitoring, and public opinion analysis. This endeavor not only allowed me to apply theoretical knowledge to a practical problem but also satisfied my curiosity about the intersection of linguistics and machine learning, fueling my passion for uncovering insights from unstructured data.
    
## Description:

This project demonstrates sentiment analysis using a Long Short-Term Memory (LSTM) neural network. Sentiment analysis involves determining the sentiment (positive or negative) expressed in text data. In this project, we use a dataset of Twitter data to train an LSTM model to classify tweets as positive or negative.
    
## Tools and Technologies:
- Data Processing & Analysis: Pandas, NumPy, NLTK, Regular Expressions
- Machine Learning & Deep Learning: TensorFlow, Keras, Scikit-learn
- Data Visualization: Matplotlib, Seaborn
- Auxiliary Libraries: String, Multiprocessing, Warnings
    
## Dataset:

[Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140)
    
## Dataset Description:

![Dataset Description 1](https://github.com/DSM2499/sentiment_analysis/blob/main/Sentiment%20Analysis%20Photos/Sentiment%20data%20(1).png)
  
  ![Dataset Description 2](https://github.com/DSM2499/sentiment_analysis/blob/main/Sentiment%20Analysis%20Photos/Sentiment%20data%20distribution.png)

## Results:

The model demonstrates robust performance on unseen clean data, achieving an accuracy of 74.15%. This result is promising, indicating the model's ability to generalize to new instances. However, the training accuracy plateauing at approximately 75% suggests potential overfitting, as the gap between training and test accuracy is relatively small.

![Model Results](https://github.com/DSM2499/sentiment_analysis/blob/main/Sentiment%20Analysis%20Photos/Seniment%20accuracy%20over%20epochs.png)

**To further enhance the model's performance, two primary avenues for improvement are identified:**

- **Hyperparameter Tuning:** Fine-tuning the model's hyperparameters could potentially mitigate overfitting and improve overall accuracy. This may involve adjusting learning rates, batch sizes, or the architecture of the neural network.
- **Data Quality Enhancement:** Improving the quality and quantity of the training data could lead to better model performance. This might include gathering more diverse examples, implementing advanced data augmentation techniques, or refining the data cleaning process.

These observations provide valuable insights for future iterations of the model, highlighting the iterative nature of machine learning development and the continuous opportunities for refinement in sentiment analysis tasks.
