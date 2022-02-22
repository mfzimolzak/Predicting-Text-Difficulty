# Predicting-Text-Difficulty

The PDF file titled Predicting Text Difficulty contains the final report with only the visualizations


The source folder contains three ipynb files:
    predicting_text_difficulty_master.ipynb: contains the entirety of the code for the report along with the necessary code to create the 
    visualizations as they are in the report. (libraries: pandas, numpy, matplotlib, nltk, sklearn, collections, scipy).  If you're 
    just hoping to view the notebook (with visualizations), try this link:
    https://nbviewer.org/github/mfzimolzak/Predicting-Text-Difficulty/blob/main/source/predicting_text_difficulty_master.ipynb
    
    predicting_text_difficulty_scratch.ipynb: contains scratch work used as a basis for the code master file (libraries: pandas, numpy, matplotlib, nltk,
    sklearn, collections, scipy, pickle).
    https://nbviewer.org/github/mfzimolzak/Predicting-Text-Difficulty/blob/main/source/predicting_text_difficulty_scratch.ipynb

    visualization_scratch.ipynb: contains a few visualizations used for analysis (libraries: pandas, numpy, matplotlib).
    https://nbviewer.jupyter.org/github/mfzimolzak/NBA2010s/blob/main/Source/scrap_notebook.ipynb
    

The CSV files, briefly, are as follows:
    regular_season_2010s.csv: contains per-game box score statistics for every player for each season starting with 
    the 2010-2011 NBA season and ending with the 2019-2020 NBA season

    playoffs_2010s.csv: contains the same statistics as in player_data.csv but is limited to only playoff games – 
    data was collected but was not used in this project

    player_data.csv: contains player information such as salary, experience, height, and weight – 2020 only.  JSON 
    formatted data can be accessed with the following url:
    https://api.sportsdata.io/v3/nba/scores/json/Players?key=a3824595f2f740dbb21dd847e49ba332 

    team_data.csv: contains team information such as name, division, conference, and colors. JSON formatted data 
    can be accessed with the following url: 
    https://api.sportsdata.io/v3/nba/scores/json/teams?key=a3824595f2f740dbb21dd847e49ba332

    stadium_data.csv: contains stadium information such as name, team, location, and geographical coordinates – 
    data was collected but was not used in this project. JSON formatted data can be accessed with the following 
    link: https://api.sportsdata.io/v3/nba/scores/json/Stadiums?key=a3824595f2f740dbb21dd847e49ba332


    
Consult Source/scrap_notebook.ipynb for more information regarding the CSV data.
    

To ensure that the notebooks run correctly within Jupyter, do the following:
    1. Create a new folder in Jupyter
    2. Upload all CSV files within the newly created folder
    3. Upload the Source folder (leaving the three ipynb files as is) within the newly created folder
