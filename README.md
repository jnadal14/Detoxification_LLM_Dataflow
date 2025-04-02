# COLX 565 Project – Agentic Detoxification Dataflow

This repository contains the code, data, and analysis for our COLX 565 project focused on **agentic workflows for text detoxification**. The goal of this project is to explore and evaluate the effectiveness of an agentic dataflow approach to reduce toxicity in text while preserving meaning and sentiment.

## Project Structure
```plaintext
detoxification_agentic_dataflow/
├── agentic_workflow.ipynb              # Main notebook outlining the detoxification workflow
├── Annotation_Statstics_notebook.ipynb # Analysis of annotation statistics
├── Detoxification Annotations.csv      # Annotated detoxification dataset 
├── results/
│   ├── sentiment_results.csv           # Sentiment analysis results
│   └── toxicity_results.csv            # Toxicity analysis results
├── data/
│   ├── multilingual-sentiment-test-solutions.csv  # Gold standard test set for multilingual sentiment
│   └── toxic-test-solutions.csv                   # Gold standard test set for toxicity classification
```

## Notebooks

- **`agentic_workflow.ipynb`**  
  Implements the main detoxification pipeline using an agentic approach. This notebook demonstrates how individual "agents" are tasked with evaluating and transforming toxic text while maintaining sentiment and meaning.

- **`Annotation_Statstics_notebook.ipynb`**  
  Explores the annotated dataset using summary statistics and visualizations.

## Dataset

- `Detoxification Annotations.csv`: Contains original and annotated sentences along with toxicity/sentiment labels and annotator agreement.
- `multilingual-sentiment-test-solutions.csv`: Ground-truth data for evaluating multilingual sentiment analysis.
- `toxic-test-solutions.csv`: Ground-truth data for evaluating toxicity classification accuracy.

## Results

- `sentiment_results.csv`: Sentiment scores pre- and post-detoxification.
- `toxicity_results.csv`: Classification metrics evaluating detoxification success.

## Getting Started

To run the project locally:

```bash
git clone https://github.com/your_username/detoxification_agentic_dataflow.git
cd detoxification_agentic_dataflow
jupyter lab