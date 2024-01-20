# BookTrends Corpus

# Corpus Overview
This corpus covers book information extracted from the Goodreads website, primarily covering book titles and descriptions. The data is derived from two primary sources, the list of "Best Books Ever" and the New York Times' 100 Notable Books of 2023 on the Goodreads platform. The corpus also includes additional metadata like authors, average ratings, and the first five genres of every book to provide insights into different aspects of the books and reading preferences. 

## Target Audience and Purpose
The target audience includes researchers and online readers. This corpus is applicable for literary trend analysis, cross-genre analysis, and assisting readers in selecting books of interest.

## Comparative Analysis
By comparing the lists of "Best Books Ever" and the New York Times' "100 Notable Books of 2023," users can explore the following areas:

1. **Emerging Trends:** Identify frequently occurring words in book descriptions or genres to recognize emerging trends in the literary domain.

2. **Author Influence:** Highlight authors with multiple books in the lists to understand their impact on the literary landscape.

3. **Genre Preferences:** Analyze which genres dominate the lists, aiding publishers and authors in understanding lasting literary impacts.

4. **Cross-Genre Analysis:** Explore the presence of cross-genre books to identify trends toward interdisciplinary literary creations.

## Data Collection
Data is primarily sourced from the Goodreads website, specifically the "Best Books Ever" list and the New York Times' "100 Notable Books of 2023" on Goodreads. The top 20 books from each list were selected, collecting titles, descriptions, authors, average ratings, and the first five genre labels for those books.

## Collection Process
Web scraping was employed using Python, spaCy, and BeautifulSoup libraries to parse web pages and extract relevant information. The collected data was saved in text format within a data directory and a single CSV file for comprehensive access.

## Cleaning and Preprocessing
Text extracted from web pages underwent cleaning and organization to ensure data consistency. Annotations and comments were added to the code for enhanced readability.

## File Format
The corpus includes a data directory with text files and a single CSV file. Columns in the CSV file include:

- Title
- Author
- Avg Rating
- Genre
- Description
- Tokens
- Lemmas
- Parts of Speech
- Source
- Rank

## Quality Check
An initial quality check was performed to ensure data consistency with the content on the source web pages.

## Additional Information
Due to the limited sample size, it is recommended to integrate other data sources for more comprehensive analysis and insights. For specific analytical purposes, combining this dataset with additional information will provide a more holistic perspective.

