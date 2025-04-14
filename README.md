# Register Variation in Lexical Diversity and Part-of-Speech Distribution

This project investigates **register variation** by analyzing **lexical diversity** and **part-of-speech (POS) distribution** in two different types of texts: **scientific abstracts** and **newspaper articles**. It compares these two registers using Python-based text processing and visualization to reveal how different language contexts affect word choice and grammatical structures.

## Abstract

Scientific abstracts and newspaper articles serve different communicative goals and show significant linguistic variation. Using Type-Token Ratio (TTR) and POS analysis, this research reveals that:

- **Scientific abstracts** use more **technical and specific vocabulary**, reflected in lower lexical diversity.
- **Newspaper articles** employ **broader vocabulary** with higher lexical diversity and a more balanced distribution of verbs and nouns.

These differences align with **Halliday’s Register Theory**, emphasizing that language adapts based on **field, tenor, and mode**.

## Tools & Libraries Used

- Python 3
- spaCy
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Files in This Repository

| File Name | Description |
|-----------|-------------|
| `Computer Modelling - Scientific Abstracts.ipynb` | POS tagging & lexical diversity analysis of scientific abstracts |
| `Computer Modelling - Newspaper Articles.ipynb` | POS tagging & lexical diversity analysis of newspaper articles |
| `Computer Modelling - Scientific Abstracts and Newspaper Articles TTR Comparison.ipynb` | Combined TTR analysis and comparative visualization |
| `Register Variation in Lexical Diversity and Part-of-Speech Distribution.pdf` | Full research paper detailing methodology, theory, analysis, and results |

## Key Results

- **TTR**:  
  - Newspaper articles: **0.3418**  
  - Scientific abstracts: **0.1492**

- **POS Distribution**:
  - Scientific texts: Higher frequency of **nouns** and **adjectives**
  - Newspapers: More balanced use of **nouns** and **verbs**

These findings reflect register-based differences in communicative purpose and structure.

## How to Run the Notebooks

1. Clone this repository or download the `.ipynb` files.
2. Open the notebooks using Jupyter Notebook or Google Colab.
3. Make sure the required libraries are installed:

```bash
pip install spacy pandas matplotlib seaborn
python -m spacy download en_core_web_sm

