# Word Frequency Analysis Using Zipf's Law

This Python script analyzes the word frequency distribution of a given text file and visualizes the results using Zipf's law. 
Zipf's law is a rule that states that in many languages the frequency of any word is inversely proportional to its rank in the frequency table. 

## Features
- Reads from a text file
- counts the word frequencies
- generates a plot to visualize the distribution of word frequencies

## Requirements
- Python 3.x
- matplotlib
- collections
- re

![Capture](https://github.com/user-attachments/assets/b7eb71db-fc34-44cd-8239-ba819af508b1)

## Usage

1. Clone repository
```
git clone https://github.com/William2716057/zipfsLaw.git
```
2. Prepare your input text file (sample.txt or any .txt file) in the project directory.
3. Run script
```
python3 zipflaw.py
```
### Script Explanation:
- read_file(file_path): Reads and returns the content of a specified text file.
- count_word_frequencies(text): Processes the text to count how many times each word appears and returns a Counter object.
- plot_zipf(word_counts): Generates and displays a log-log plot of the word frequencies according to Zipf's law.

### Notes
- The script converts all text to lowercase and uses regular expressions to extract words.
- The matplotlib library is used for visualization.
- The top 30 most frequent words will be labeled on the x-axis of the plot.
