# Sentiment Analysis using Java

This Java project performs sentiment analysis on multiple texts using a predefined lexicon. It utilizes CompletableFuture to process texts concurrently and writes the sentiment scores to an output file.

## Features

- **Sentiment Analysis:** Calculates sentiment scores for each text using a lexicon-based approach.
- **Concurrency:** Employs CompletableFuture for concurrent processing of multiple texts.
- **Output:** Writes sentiment scores for each text to an output file.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed on your machine.
- Text file containing the lexicon data in the format: `word sentiment_score` (e.g., `happy 3.0`).

### Usage

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/sentiment-analysis.git
   cd sentiment-analysis
