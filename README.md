# Corpus Description
The corpus is composed of 20 pieces of news about culture from [Chinadaily](https://www.chinadaily.com.cn/culture), the largest English portal in China. The selected news covers many aspects, including art, books, film, heritage, and music, which were released in 2023.

# Target Audience and Intended Use
The target audience can include linguistic researchers, NLP professionals, language learners, media outlets, and those who are interested in Chinese culture. From an academic perspective, the corpus can analyze language patterns, linguistic styles, and dialogues. News media can understand how Chinadaily covers cultural events by analyzing the angles, stances, and language choices of the coverage. Language learners can take it as a teaching resource to learn Chinese, understand Chinese culture, and improve their reading and writing skills.

# Text Selection Criteria
The selected texts are specifically focused on cultural news to align with the intended purpose of the corpus. A diverse range of cultural topics to capture the breadth of cultural events and developments in China are included.

# Data Collection Process
The first step is to clearly define the objectives of the corpus and the specific scope of cultural news. Then the primary source for cultural news on Chinadaily is identified, the official website. 20 news is downloaded by web scraping and saved as txt files.

# Cleaning Steps
With Python, text cleaning is completed. The special characters, punctuation marks, and numbers are removed, with only the text content kept. All letters in the text are converted to lowercase to ensure that the case does not affect subsequent text analysis. Besides, stop words are removed, and lemmatization is achieved. Texts are tokenized for further analysis.

# Format
The CSV file includes columns of the filename, the name of the original text file, the document, the original text, preprocessed text, tokens, lemmas, and parts of speech.
