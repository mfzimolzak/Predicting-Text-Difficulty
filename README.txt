The PDF file titled Predicting Text Difficulty contains the final report with only the visualizations.


The source folder contains three ipynb files:
    predicting_text_difficulty_master.ipynb: contains the entirety of the code for the report along with the necessary code to create the 
    visualizations as they are in the report. (libraries: pandas, numpy, matplotlib, nltk, sklearn, collections, scipy).  If you're just hoping to view the
    notebook (with visualizations), try this link:
    https://nbviewer.org/github/mfzimolzak/Predicting-Text-Difficulty/blob/main/source/predicting_text_difficulty_master.ipynb
    
    predicting_text_difficulty_scratch.ipynb: contains scratch work used as a basis for the code master file (libraries: pandas, numpy, matplotlib, nltk,
    sklearn, collections, scipy, pickle).
    https://nbviewer.org/github/mfzimolzak/Predicting-Text-Difficulty/blob/main/source/predicting_text_difficulty_scratch.ipynb

    visualization_scratch.ipynb: contains a few visualizations used for analysis (libraries: pandas, numpy, matplotlib).
    https://nbviewer.jupyter.org/github/mfzimolzak/NBA2010s/blob/main/Source/scrap_notebook.ipynb
    

The data.zip file contains three files that were used in analysis:
    WikiLarge_Train.csv: roughly 400k sentences in string format from an assortment of Wikipedia articles with labels.  0 indicates that a sentence does not need
    to be simplified while 1 indicates that a sentence does need to be simplified.
    
    dale_chall.txt:  This is the Dale Chall 3000 Word List, which is one definition of words that are considered "basic" English.  A summary is at
    https://www.readabilityformulas.com/articles/dale-chall-readability-word-list.php
    
    AoA_51715_words.csv:  This file contains "Age of Acquisition" (AoA) estimates for about 51k English words, which refers to the approximate age (in years)
    when a word was learned. Early words, being more basic, have lower average AoA.  The main columns you will be interested in (utilized in the project) are
    "Word" and "AoA_Kup_lem" but the others may be useful too.
    
    The file contains these columns:
    Word :: The word in question
    Alternative.spelling :: if the Word may be spelled frequently in another form	
    Freq_pm	:: Freq of the Word in general English (larger -> more common)
    Dom_PoS_SUBTLEX	:: Dominant part of speech in general usage
    Nletters :: number of letters 
    Nphon :: number of phonemes
    Nsyll :: number of syllables
    Lemma_highest_PoS :: the "lemmatized" or "root" form of the word (in the dominant part of speech. e.g. The root form of the verb "abates" is "abate".
    AoA_Kup	:: The AoA from a previous study by Kuperman et al.
    Perc_known :: Percent of people who knew the word in the Kuperman et al. study
    AoA_Kup_lem :: Estimated AoA based on Kuperman et al. study lemmatized words. THIS IS THE MAIN COLUMN OF INTEREST.
    Perc_known_lem	:: Estimated percentage of people who would know this form of the word in the Kuperman study.
    AoA_Bird_lem :: AoA reported in previous study by Bird (2001) 
    AoA_Bristol_lem	:: AoA reported in previous study from Bristol Univ. (2006)
    AoA_Cort_lem :: AoA reported in previous study by Cortese & Khanna (2008)
    AoA_Schock :: AoA reported in previous study by Schock (2012)

    Original source : http://crr.ugent.be/archives/806  
    
To ensure that the notebooks run correctly within Jupyter, do the following:
    1. Create a new folder in Jupyter
    2. Upload all files in the source folder and the data.zip file to the folder.  Each individual file should fall in the root folder.
