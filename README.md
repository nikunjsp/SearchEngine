
# Search Engine Project

This project was developed as a final project for the Advanced Computing Concepts (COMP8547) course under the guidance of **Professor Dr. Mahdi Firoozjaei**. The search engine incorporates multiple core features designed to perform efficient web searches, text operations, and page ranking.

---

## Project Overview

### What is a Search Engine?

A search engine is a software system designed to carry out web searches, which means searching the web for information specified by the user in the form of keywords or phrases.

### Incorporated Features

The search engine includes the following key components:

1. **Web Crawler**: Automates the process of visiting and indexing web pages.
2. **Regular Expression**: Allows pattern matching within text, enhancing search capabilities.
3. **Spell Checker**: Detects and corrects misspelled words using a dictionary.
4. **Word Completion**: Suggests words based on user input.
5. **Inverted Index**: Structures data to facilitate quick full-text searches.
6. **Frequency Counter**: Calculates the frequency of words in documents.
7. **Page Ranking**: Ranks pages based on word frequency and relevance.

---

## Feature Details

### Web Crawler
The web crawler navigates through web pages, extracting content and storing it for indexing.

### Regular Expression
This feature enables text pattern matching using Java’s `java.util.regex` package. It includes:
- `Pattern` Class: Defines search patterns.
- `Matcher` Class: Matches patterns in text.
- `PatternSyntaxException` Class: Handles syntax errors in patterns.

### Spell Checker
Utilizes a dictionary and `trie` data structure to correct spelling errors by comparing words against a predefined list.

### Word Completion
Suggests possible words based on partial user input, improving search accuracy and user experience.

### Inverted Index
An inverted index allows fast searches at the expense of greater storage needs, commonly used in document retrieval systems.

### Frequency Counter
Counts occurrences of words in a document to help prioritize and rank content relevance.

### Page Ranking
Ranks web pages by analyzing word frequency, providing users with the most relevant results.

---

## Future Scope

Future developments for the search engine include:
- **Web and Mobile Applications**: Expanding to a web-based and Android app interface.
- **User History Tracking**: Storing user search history to improve personalized page ranking.
- **Enhanced Regex Options**: Adding more options for customized search patterns.
- **Improved GUI**: Creating a user-friendly interface to enhance the user experience.

---


## References

The following resources were referenced in the development of this project:
- [Wikipedia - Search Engine](https://en.wikipedia.org/wiki/Search_engine)
- [Wikipedia - Web Crawler](https://en.wikipedia.org/wiki/Web_crawler)
- [Cloudflare - What is a Web Crawler](https://www.cloudflare.com/en-ca/learning/bots/what-is-a-web-crawler/)
- [Medium - Keyword Extraction](https://medium.com/nerd-for-tech/keyword-extraction-applications-and-tools-193ff7758cc7)
- [Towards Data Science - Keyword Extraction with BERT](https://towardsdatascience.com/keyword-extraction-with-bert-724efca412ea)
- [SEMrush - PageRank](https://www.semrush.com/blog/pagerank/)

---

Thank you for reviewing our project!
