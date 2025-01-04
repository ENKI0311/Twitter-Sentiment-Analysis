

---

# Twitter Sentiment Analysis

## Overview
This project performs sentiment analysis on Twitter data using the **Llama 3.2-1B-Instruct** model. The objective is to extract structured insights from tweets by analyzing public sentiment and summarizing the results in a JSON format. The workflow is designed to be efficient, leveraging a subset of tweets for rapid analysis.

---

## Project Workflow
1. **Data Loading**: Load and preprocess Twitter training and validation datasets.
2. **Sampling**: Select a subset of 1,000 tweets from the dataset to ensure efficient analysis.
3. **Sentiment Generation**: Analyze each tweet's sentiment using the Llama 3.2-1B-Instruct model.
4. **JSON Parsing**: Parse the sentiment analysis output into a structured JSON format for easier interpretation.
5. **Result Display**: Extract and display key sentiment summaries from the JSON output.

---

## Files
- **`twitter_training.csv`**: Training dataset containing tweets.
- **`twitter_validation.csv`**: Validation dataset containing tweets.
- **`Llama_Sentiment_Analysis.ipynb`**: Jupyter Notebook with the complete workflow, including model setup, sentiment analysis, and JSON parsing.

---

## Model
The project uses **Llama 3.2-1B-Instruct** from Hugging Face's `transformers` library. This state-of-the-art language model generates text-based sentiment insights from tweet data.

---

## How to Run

### Clone the Repository
```bash
git clone <repository-url>
cd Twitter-Sentiment-Analysis
```

### Install Dependencies
Ensure you have Python 3.x installed, then run:
```bash
pip install -r requirements.txt
```

### Run the Notebook
- Open `Llama_Sentiment_Analysis.ipynb` in Jupyter Notebook, Google Colab, or a similar environment.
- Execute the cells step by step to load the data, run sentiment analysis, and parse results.

### Analyze Results
- Review the generated JSON outputs for structured sentiment insights.
- Explore the summaries extracted from the sentiment analysis.

---

## Requirements
- **Python 3.x**
- **Hugging Face Transformers**
- **PyTorch**
- **pandas**

To install all dependencies:
```bash
pip install -r requirements.txt
```

---

## Project Structure
```
Twitter-Sentiment-Analysis/
├── data/
│   ├── twitter_training.csv
│   └── twitter_validation.csv
├── Llama_Sentiment_Analysis.ipynb
├── requirements.txt
└── README.md
```

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

---

