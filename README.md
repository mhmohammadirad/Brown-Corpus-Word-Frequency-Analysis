# Brown-Corpus-Word-Frequency-Analysis
UniversityOfOulu/NLP/Lab1

This notebook analyzes word frequency using the **Brown Corpus** and includes several visualizations. 

### Requirements
Make sure you have these libraries installed:
- `nltk`
- `matplotlib`
- `beautifulsoup4`
- `requests`

Install them with:
```bash
pip install nltk matplotlib beautifulsoup4 requests
```

## How to Run
1. Clone the repo and run the notebook.
2. The necessary NLTK datasets will download automatically.
3. Outputs, including frequency data and visualizations, will be generated.

## Key Features

1. **Word Frequency Analysis**: Analyzes word frequency from the Brown Corpus and saves it in `word_freq.txt`.

2. **Visualizations**: Generates charts for:
   - 30 Most Frequent Words ![Most Frequent Words](Q3.png)
   - 30 Least Frequent Words
   - Word Length vs Frequency ![Word Length vs Frequency](Q4.png)

3. **Modal Verbs Analysis**: No. Words vs No. Characters in Modal Sentences ![Modal Verbs Analysis](Q5.png)

4. **Stopwords Analysis**: Relationships between stopwords and words and characters in a sentence ![Stopwords Analysis - Words](Q61.png) ![Stopwords Analysis - Characters](Q62.png)

5. **Web Tokenization**: Tokenizes content from a webpage and saves the results in `web_output.txt`.