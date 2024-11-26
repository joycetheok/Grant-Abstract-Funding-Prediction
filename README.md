# Predicting Research Funding from Grant Proposal Abstracts
 
Hello and welcome to the Git repository

## Directory

- data:  the folder that contains all the .csv files.
    - data chunks:  grants.csv but in chunks.
    - misc:  unneeded stuff.
    - raw data:  the folder that contains the raw import from the CIHR website
        - `CA.US-Social.csv` a .csv file that contains the direct import of the grants as appears on the CIHR website, for Social Sciences and in the Canadian/US regions.
    - `applids.csv` a .csv file that contains only the applIDs of the grants, which was used to access the grants links.
    - `grants.csv` a .csv file that contains all the scraped grants.  Includes title, contributors, abstracts, etc. and includes English, French and a small amount of unknown language/empty abstract languages.
    - `english_grants.csv` grants.csv but with only English entries. **We will be using this .csv file primarily**.

The following scripts are in this repo:
- Joyce's
    - `code.ipynb`
    - `language_filtering.ipynb`
- Unu's
    - `LDA-category.ipynb`
    - `tfidf-category.ipynb`
    - `lda3.ipynb`

## Instructions