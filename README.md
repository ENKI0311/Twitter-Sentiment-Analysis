## Twitter Sentiment Analysis

## Overview
This project performs sentiment analysis on Twitter data using the **Llama 3.2-1B-Instruct** model. The goal is to generate structured insights from tweets by analyzing public sentiment and summarizing results in a JSON format.

## Project Workflow

1. **Data Loading**: Twitter training and validation datasets are loaded and pre-processed.
2. **Sampling**: A subset of 1,000 tweets is selected from the larger dataset to ensure efficient analysis.
3. **Sentiment Generation**: Each tweet is analyzed using the Llama 3.2-1B-Instruct model to generate sentiment responses.
4. **JSON Parsing**: The generated responses are parsed into structured JSON format for easy consumption and further analysis.
5. **Result Display**: Key sentiment summaries are extracted and displayed from the JSON output.

## Files
- `twitter_training.csv`: The training dataset of tweets.
- `twitter_validation.csv`: The validation dataset of tweets.
- `Llama_Sentiment_Analysis.ipynb`: The notebook that contains the full workflow, including model setup, sentiment generation, and JSON parsing.
  
## Model
The project utilizes **Llama 3.2-1B-Instruct** from Hugging Face's `transformers` library. The model generates text-based sentiment insights from the tweet data.

## How to Run

1. Clone the repository:
    ```bash
    git clone <repository-url>
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook `Llama_Sentiment_Analysis.ipynb` on Google Colab or your local machine (with a compatible GPU).
4. Analyze the sentiment results and explore the structured JSON outputs.

## Requirements
- Python 3.x
- Hugging Face `transformers`
- PyTorch
- pandas

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
