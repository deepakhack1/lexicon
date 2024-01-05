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

Replace Lexicon File:

Replace path_to_your_lexicon_file.txt in SentimentAnalysis.java with the actual path to your lexicon file.

Compile and Run:

bash
Copy code
javac Runner.java
java Runner
Output:

The sentiment scores for each text will be written to the sentiment_scores.txt file in the project directory.

File Structure
SentimentAnalysis.java: Java source code file containing the sentiment analysis logic.
path_to_your_lexicon_file.txt: Replace with your lexicon file.
sentiment_scores.txt: Output file containing sentiment scores for each text.
Contributing
Contributions are welcome! Feel free to fork the repository, make changes, and create a pull request.


![image](https://github.com/deepakhack1/lexicon/assets/24849667/d3261c06-d30e-4391-8787-976868fb3f62)

   
