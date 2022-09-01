# Relationship Extraction from the Withcer book series using Selenium, Spacy, and NetworkX
---
## Methodology
Web scraping was performed on the Witcher Books Fandom page to extract all characters within the series. The book text was scraped from [this](https://github.com/dworschak/Witcher) repository. Spacy was used to analyze the book text and extract characters which would then be checked against the scraped character list from the web. A rolling window was used to analyze relationships in the text where relationships where established whenever characters apaeared together within the winodow. When more than two characters appeared within the window, each character is assumed to have a relationship with all other characters in the window. Analysis was then performed and visualzations were created. 
![network](https://raw.githubusercontent.com/DannyAlas/NLP-Witcher-Character-Relationships/main/img/network.png)
