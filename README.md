## Sentiment Analysis README

## Overview

This project involves a simple rule-based sentiment analysis algorithm implemented using pure Python. The analysis is performed on Amazon.com reviews for cell phones and accessories. The goal is to determine the sentiment (positive, negative, or neutral) of each review based on textual data.

## Project Structure

- `data/` : Contains the input JSON file with Amazon reviews.
- `scripts/` : Contains the Python scripts for data processing, thematic analysis, and sentiment analysis.
- `output/` : Contains the final output text file with reviews and their corresponding sentiment.

## Files

- `data/reviews.json` : Input data file containing Amazon reviews.
- `scripts/data_preprocessing.py` : Script for loading and preprocessing the data.
- `scripts/thematic_analysis.py` : Script for performing thematic analysis on the reviews.
- `scripts/sentiment_analysis.py` : Script for performing sentiment analysis using the rule-based algorithm.
- `output/sentiment_output.txt` : Final output file with each review and its determined sentiment.

## Installation

To run this project, you need Python installed on your machine. No external libraries are required as the implementation uses built-in Python modules.

## Usage

1. **Data Loading & Preprocessing**

   - Read and parse the JSON data into a suitable Python data structure.
   - Filter the dataset to retain only the necessary columns.
   - Preprocess the text by removing punctuation and stop words.

2. **Thematic Analysis**

   - Identify key phrases or words commonly found in positive and negative reviews.
   - Use basic frequency analysis or more advanced methods to distinguish between good and bad reviews based on ratings.

3. **Sentiment Analysis**

   - Design a rule-based sentiment analysis algorithm.
   - Define rules or heuristics to assess the sentiment of a review by analyzing the review text.
   - Assign weights to commonly used words and accumulate these weights based on their frequency in the review text.
   - Establish a threshold to categorize each review as positive, negative, or neutral.

4. **Storage**

   - Save the end result in a text file, putting the review text next to its sentiment.

## Example

Below is a simplified example of how to run the scripts:

```bash
python scripts/data_preprocessing.py
python scripts/thematic_analysis.py
python scripts/sentiment_analysis.py
```
The final output will be saved in output/sentiment_output.txt.

## Contribution
Feel free to contribute to this project by opening issues or submitting pull requests. Please ensure that your contributions adhere to the project's coding standards and practices.

## License
This project is licensed under the MIT License. See the `LICENSE file` for details.

## Acknowledgements
Special thanks to the authors of the resources used for creating the rule-based sentiment analysis algorithm. Further information on rule-based sentiment analysis can be found at: https://vtiya.medium.com/rule-base-sentiment-analysis-adfad898470b.
