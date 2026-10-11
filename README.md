# Python---Survey-Feedback-Analyzer
A Python-based analytical tool built to process, clean, and extract insights from customer survey feedback. This project demonstrates core Python programming concepts using fundamental data structures without relying on external libraries like Pandas.

📑 Table of Contents
Features

Dataset Structure

How It Works

Getting Started

Sample Output

Key Python Concepts Used

✨ Features
Interactive Data Entry: Dynamically add new feedback entries with auto-incrementing serial numbers (S_No) and input validation for ratings (1–5).

Automated Text Cleaning: Normalizes feedback text by:

Converting text to lowercase

Stripping punctuation (., ,, !, ?)

Collapsing multiple spaces into a single space

Word Count Insights: Uses custom functions to calculate exact word frequencies across feedback entries (e.g., "good", "poor", "excellent").

Statistical Metrics: Computes overall average customer ratings.

Text Analysis:

Identifies the longest feedback comment based on word count.

Extracts a deduplicated list of unique vocabulary used across all entries.

Data Sorting (Optional Feature): Ranks customer feedback entries from highest to lowest rating using zip() and sorted().

🗂️ Dataset Structure
The project stores survey responses using a dictionary of lists:

Python
feedback_data = {
    'S_No': [1, 2, 3, ...],
    'Name': ['Ravi', 'Meera', 'Sam', ...],
    'Feedback': ['Very GOOD Service!!!', 'poor support, not happy ', ...],
    'Rating': [5, 2, 5, ...]
}
