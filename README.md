Scientists must research others’ work to advance their careers, but researchers contribute thousands of documents to their fields each year.  In 2018, the astrophysics section (astro-ph) of the scientific archive arXiv received over 14,000 submissions.  Although astro-ph is subdivided into six categories, the groupings are fuzzy with many subjects straddling multiple categories.  Scientists at Marshall Space Flight Center have bemoaned the amount of time they must spend searching arXiv to uncover previous research in a new area.

This project uses natural language processing (NLP) techniques over a selection of arXiv abstracts to return related articles.  I’ll demonstrate how TFIDF and document similarity power my search.


Project documents:
1.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/reports/C2%20Project%20Proposal.pdf'>Project Proposal</a>
2.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/reports/C2%20Milestones%201.pdf'>Project Milestones 1</a>
3.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/reports/C2%20Milestones%202.pdf'>Project Milestones 2</a>
4.  <a href=''></a>

Project code:
1.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/notebooks/ArXiv_cleaning.ipynb'>Data Cleaning</a>
2.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/notebooks/ArXiv_EDA.ipynb'>Exploratory Data Analysis</a>
3.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/notebooks/ArXiv_modeling.ipynb'>Modeling</a>

Project data:
1.  <a href=''></a>
2.  <a href=''></a>
3.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/data/astro_yourtestdata_1k.csv'>Sample</a> - (This is a sample of 1000 records from arXiv that can be used to test the notebooks.)

Supplementals:
1.  <a href='https://github.com/OhThatMisty/astro_categories/blob/master/notebooks/ArXiv_data_usertest.ipynb'>Data Retrieval</a> - (This is the same code that I used to download the data, but the number of articles and max downloads were both changed to 1000 (max number of articles is 2000) so that the code will either work or not.  The package used, arxivpy, doesn't offer feedback when arXiv returns a blank feed.)
