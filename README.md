This repository contains a Python script that calculates Rouge scores to evaluate the quality of automatic summaries by comparing them with gold standard summaries. Both the auto summaries and the gold summaries are stored in separate directories, and the script matches them by filename. For each matching pair, the script uses the Rouge metric to calculate the F-scores for Rouge-1, Rouge-2, and Rouge-L, providing an evaluation of how similar the auto summary is to its corresponding gold summary. The results, which include the F-scores for each matched pair, are saved in a CSV file for easy analysis. This tool is helpful for automatic text summarization tasks, providing quantitative insight into the performance of summarization algorithms.
