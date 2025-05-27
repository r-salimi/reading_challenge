# Word Analysis Project (Quera CodeCup 7 – Data Science)

This project is a solution to one of the problems from the **Quera CodeCup 7 – Data Science** competition. The task involves basic text analysis and manipulation using **Python** and **pandas**.

---

##  Objective

Analyze a dataset of words (provided in a CSV file) to extract specific statistical and structural insights.

---

##  Tools and Technologies

- Python 3
- pandas
- collections (Counter)

---

##  Dataset

- Input: `words.csv`  
- Structure: A single-column CSV file with one word per row under the column name `words`.

---

##  Tasks Performed

1. **Count the Most Frequent Words**  
   - Combined all words and used `Counter` to find the **top 5 most frequent** words in the dataset.

2. **Find the Longest Word Starting with "q"**  
   - Filtered all words beginning with the character `q`.
   - Retrieved the word with the **maximum length**.

3. **Identify Unique 8-Character Words**  
   - Extracted all words with exactly 8 characters.
   - Filtered the ones that **appear only once** in the dataset.
   - Sorted the result alphabetically and returned the **first five**.


