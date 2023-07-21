<img src="https://github.com/Yassine-Squalli-Houssaini/A-Novel-Text-Mining-Approach-Based-on-TF-IDF-and-Support-Vector-Machine-for-News-Classification/assets/127676452/fb0cc3dd-9c6f-4924-bf67-667d21d53d42" width="3000">
<br>
<br>


## Project Objective
The objective of this study is to classify news articles into different groups based on TF-IDF (Term Frequency-Inverse Document Frequency) features, focusing specifically on data from the BBC and the 20 Newsgroups dataset.

## Description of Datasets:
The 20 Newsgroups dataset is a widely used dataset in natural language processing and machine learning. It consists of approximately 20,000 documents from 20 different discussion groups.

The BBC dataset, on the other hand, is a collection of press articles from the British Broadcasting Corporation (BBC) website. It is organized into different thematic categories.

## The proposed approach will be as follows:
1. Text preprocessing
2. Train/test split
3. Feature extraction based on TF-IDF
4. Classification using SVM (Support Vector Machine)
5. Comparison with the results of the reference model

## Work Details:
TF-IDF (Term Frequency-Inverse Document Frequency) is a statistical measure that evaluates the importance of a term in a document relative to a corpus. It assigns a high weight to terms that are frequent in the document and rare in the entire corpus. This highlights distinctive and important terms.

SVM (Support Vector Machine) is a supervised learning algorithm used for classification. It seeks to find a hyperplane that best separates the different classes. It is effective even with non-linearly separable data through the use of kernel functions.

By using TF-IDF to extract document features and SVM for classification, we obtain a system capable of classifying documents based on their important characteristics. TF-IDF captures semantic aspects, and SVM finds the best separation between classes.

## Evaluation Metrics:

To assess the performance we employed several evaluation metrics, including:

- **Accuracy:** The percentage of correctly classified news articles by the model.
- **Precision:** The proportion of true positive predictions out of all positive predictions made by the model.
- **Recall:** The proportion of true positive predictions out of all actual positive instances in the dataset.
- **F1 Score:** A metric that combines precision and recall to provide a balanced evaluation of the model's performance.

## Comparison between Model Results and Reference Model:

In this project, we have compared the results obtained from our generated model with those of a reference model. The purpose of this comparison was to evaluate the performance and effectiveness of our approach for news article classification using TF-IDF features and SVM.
## Approach:

1. **Generated Model:** Our generated model followed the steps outlined in the previous section. It involved text preprocessing, train/test split, feature extraction using TF-IDF, and classification using SVM.

2. **Reference Model:** The reference model served as a benchmark for comparison. 


## For The BBC dataset:

<img width="364" alt="Screenshot 2023-07-21 at 18 18 03" src="https://github.com/Yassine-Squalli-Houssaini/A-Novel-Text-Mining-Approach-Based-on-TF-IDF-and-Support-Vector-Machine-for-News-Classification/assets/127676452/c9d3ccc7-6589-4c7f-a622-4a72f7cdacdd">




## For The 20 Newsgroups dataset:

<img width="430" alt="Screenshot 2023-07-21 at 18 20 16" src="https://github.com/Yassine-Squalli-Houssaini/A-Novel-Text-Mining-Approach-Based-on-TF-IDF-and-Support-Vector-Machine-for-News-Classification/assets/127676452/93b5b00a-0746-40f9-b19c-055b6b00e639">


<img width="285" alt="Screenshot 2023-07-15 at 01 12 03" src="https://github.com/Yassine-Squalli-Houssaini/A-Novel-Text-Mining-Approach-Based-on-TF-IDF-and-Support-Vector-Machine-for-News-Classification/assets/127676452/88300fec-a6ab-41c6-8d35-3c86c9924bc0">

## Critique of the Work
The described approach does not take into account other more recent and advanced techniques that have emerged in the field of natural language processing, such as deep neural networks or knowledge transfer from pre-trained models. The use of these more modern approaches could improve classification performance and allow for better capturing of semantics and contextual relationships in the documents. Therefore, while the TF-IDF and SVM-based approach is commonly used, it may have limitations in terms of semantic representation and sensitivity to parameters.

## Conclusion
In conclusion, the results obtained for both datasets (BBC and 20 Newsgroups) demonstrate a very high accuracy of the classification model. This indicates that the model is capable of accurately predicting the classes of the test data. High accuracy is a positive indicator of the model's performance and attests to its effectiveness in the classification task. These results reinforce confidence in the use of the model for prediction and classification tasks.




