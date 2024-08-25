# Fact-Checking Public Health Claims

## Overview
This project focuses on fact-checking public health claims using three different models: Naive Bayes, BERT (Bidirectional Encoder Representations from Transformers), and Llama2. The notebook demonstrates data preprocessing, model training, and evaluation for each approach, aiming to explore their effectiveness in distinguishing between true and false health-related claims.

## Table of Contents
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Workflow](#workflow)
- [Models](#models)
- [License](#license)
- [Acknowledgement](#acknowledgment)

## Dataset

The dataset used for this research can be found at the following GitHub repository: [Health-Fact-Checking Dataset](https://github.com/neemakot/Health-Fact-Checking).

## Installation
To run this project, ensure you have Python installed along with the necessary libraries. You can install the required libraries using the following command:

```bash
pip install -r requirements.txt
```

Additionally, install the Black library for code formatting:

```bash
pip install black
```


## Usage
1. **Clone the repository**:
   ```bash
   git clone https://github.com/Tanujshriyan/Explainable-Automated-Fact-Checking-OF-Public-Health-Claims.git
   cd Explainable-Automated-Fact-Checking-OF-Public-Health-Claims
   ```

2. **Open the Jupyter Notebook**:
   Launch Jupyter Notebook and open the `fact_checking_model.ipynb` file.

3. **Run the Notebook**:
   Execute the cells in the notebook sequentially to preprocess the data, train the models, and evaluate their performance.

## Workflow
The workflow of this notebook is as follows:
1. Import necessary libraries and modules.
2. Load and preprocess the data.
3. Perform exploratory data analysis and visualization.
4. Conduct text preprocessing and sentiment analysis.
5. Classify using the Naive Bayes classifier.
6. Train and evaluate the BERT model.
7. Implement prompt engineering for the Llama2 model.
8. Use Markdown cells for documentation and explanation.

## Models
### 1. Naive Bayes
- A probabilistic classifier that is commonly used for text classification tasks.
- The implementation includes data preprocessing, feature extraction, model training, and evaluation.

### 2. BERT
- A transformer-based model that provides state-of-the-art results in various NLP tasks.
- The notebook includes functions for tokenization, training, and evaluation.

### 3. Llama2
- A model designed for text generation and fact-checking.
- The notebook demonstrates how to set up the tokenizer, generate responses, and process claims in batches.

## Llama2 Model Usage
To use the Llama2 model, you must obtain permission from Hugging Face. Please visit the Hugging Face website and follow their guidelines for accessing the model. Ensure you comply with their terms of use and licensing agreements.

## Acknowledgment

This project was conducted as part of the MSc in Artificial Intelligence and Data Science program at the **University of Hull**. The research presented in this repository contributed to my dissertation titled *Explainable Fact-checking Model for Public Health Claims Using BERT and Llama 2 with Prompt Engineering*, submitted in August, 2024.

For any inquiries regarding the project or research, please contact me at tanujshriyan@gmail.com.
