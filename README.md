# Simple and Complex Sentences Dataset

This repository contains a dataset of 8,000 sentences which is a subset sourced from [this](https://cs.pomona.edu/~dkauchak/simplification/) Simple Wikipedia and English Wikipedia dataset. The dataset is split into two categories: 4,000 simple sentences and 4,000 complex sentences. Each sentence is annotated with various shallow features. The extraction was conducted through a python script using the [textstat](https://pypi.org/project/textstat/) library.

## Dataset Description

### Structure

The dataset includes the following columns for each sentence:

1. **Sentence**: The original sentence.
2. **Flesch Reading Ease**: A readability formula using total words sentences and syllables to asses difficulty in grade levels.
3. **Flesch-Kincaid Grade**: A readability formula similar to Flesch Reading Ease.
4. **SMOG Index**: Estimates the years of education needed to understand a piece of writing.
5. **Gunning Fog**: A grade formula to assess the minimum grade a person should be to understand the text.
6. **Coleman-Liau Index**: A readability index that relies on letters per word and returns a grade score.
7. **Automated Readability Index**: A readability formula using characters per word as well as words per sentence.
8. **Dale-Chall Readability Score**: A readability formula that relies on a list of 3,000 familiar words.
9. **Linsear Write Formula**: A readability formula with more of an algorithmic approach.
10. **Spache Readability**: A readability formula that uses a specific word list for measuring readability.
11. **McAlpine EFLAW**: A formula focusing on the number of miniwords and length of sentences designed to return a score more represenative of L2-readers.
12. **Reading Time**: Estimated reading time in seconds.
13. **Syllable Count**: Total number of syllables in the sentence.
14. **Monosyllabic Count**: Number of single-syllable words.
15. **Polysyllabic Count**: Number of words with 3 or more syllables.
16. **Word Count**: Total number of words in the sentence.
17. **Mini Word Count**: Count of words with 3 or fewer characters.
18. **Difficult Words**: Number of words that are not among the 3,000 most common words.
19. **School Grade**: Estimated school grade level required to understand the sentence.
20. **Complexity**: Classification of the sentence as either simple or complex.

#### More info about each feature extracted can be found [here](https://pypi.org/project/textstat/).

#### The delimiter used in the CSV is the asterisk "*".

### Usage

The dataset is useful for various natural language processing (NLP) tasks such as text simplification, readability assessment, and educational research. Researchers and developers can leverage this dataset to train and evaluate models aimed at distinguishing between simple and complex sentences or to develop tools for improving text accessibility.

## Contact

For any questions or issues regarding the dataset, feel free to create an issue in the repository.
