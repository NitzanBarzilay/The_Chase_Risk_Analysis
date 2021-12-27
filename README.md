# The_Chase_Risk_Analysis
Analysis of the participants in 3 seasons of the Israeli TV game show "The Chase".
This repository contains an analysis of the participants in 3 seasons of the Israeli TV game show "The Chase", done as a part of "Neuropsychiatry - Cognition of Mental Disorders" course at the Hebrew University of Jerusalem in the fall semester of 2021. 
This project's goal was to assess the influence of the participant's experience of success in the game's first (fast) round, on the amount of risk they choose to take in the round that follows (see specific definitions and more details in the attached research proposal - in Hebrew. If you are interested in information in English feel free to contact me by Email).

We publish here the Jupyter notebook that contains the pre-proccessing that was performed as well as many visualizations of the data - mainly segmentation by gender, age, and order in the game (first / second / third / fourth player) and their effect on risk taking. 

This repository also contains the data itself (downloaded from https://www.kaggle.com/thomaskonstantin/the-chasegame-show-israel-episode-data) with our addition - the features p_i_j with i in (1,2,3) and j in (high, middle, low) that represents the amount of incouragment the i'th player got from the other players in their group to take the j'th amount of risk. The number in each of these features represents the amount of players in the group (out of a maximum of 3) that enncoureged the current player to take that amount of risk. If the players in the group were not asked by the host to express their opinion, this was marked by an "X". This data was collected manually by watching all 3 seacons of the show and trying to quantify the opinions of the players. These features were also visualized. 


