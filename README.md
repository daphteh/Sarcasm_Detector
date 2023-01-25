# Sarcasm_Detector
In this project, I built a Sarcasm Detector using deep learning & NLP techniques to predict whether headlines from 'The Onion' & 'The Huffington Post' are sarcastic. Deep learning & transfer learning techniques were used. 

## Supervised Prediction Task ##
* ML Logistic Regression Model --> useful for establishing baseline performance
* NNLM Model with Universal Embeddings
* BERT
* DistilBERT (Distilled BERT)

## Tools Used
 - tensorflow
 - transformers
  - sklearn

## Data Details
- 28,619 headlines
- Indicator of whether the headline is sarcastic 
- Article link

# Methodology
<details>
<summary> Step 1: Explore and split the data </summary>
 <br>
      <p>   Explore and check the data </p>
      <p>   Train-test-split</p>
</details>

<details>
<summary> Step 2: Preprocess the data (not necessary for NNLM) </summary>
      <p>   clean, strip, lowercase and tag the headlines
      <p>   Include or remove Stopwords
      <p>   Engage in feature extraction
</details>

<details>
<summary> Step 3: Run the model </summary>
<br>
      <p>   Intialize the model
      <p>   Analyze the data
</details>

<details>
<summary> Step 4: Evaluate the model </summary>
<br>
      <p>   Track its performance on precision, accuracy, F1-score
</details>

<img width="1274" alt="NLP_Preprocessing" src="https://github.com/daphteh/Sarcasm_Detector/blob/086208b4acb252047b21243473f9d3d31e77901c/Report_images/NLP_Preprocessing.png">

