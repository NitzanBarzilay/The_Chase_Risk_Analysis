# The_Chase_Risk_Analysis
This repository contains an analysis of the participants in 3 seasons of the Israeli TV game show "The Chase", based on data from Kaggle (https://www.kaggle.com/thomaskonstantin/the-chasegame-show-israel-episode-data) with our manual additions (see at the end of this file).
This project's goal was to assess the influence of the participant's experience of success in the game's first (fast) round, on the amount of risk they choose to take in the round that follows.

### The game "The Chase"
The game operates as follows - each player plays against "the chaser" - a player with wide general knowledge. On the first round of the game ("the fast round"), the player gets one minute to answer correctly as many questions as possible, and they are rewarded with 5K ILS for each correct answer. At the end of this round, The player has to choose the amount of money to gamble on the second round. They have 3 choices (see image below) - the exact amount they gained in the first round, a much larger amount or a much smaller amount. This choice affects not only the player's potential monetary gain but also the difficulty level of the second round - the higher the amount, the higher the difficulty. 

![image](https://user-images.githubusercontent.com/36603609/147443179-04551c98-d3af-42ed-99a8-bc09e726c67e.png)

In the project we defined these 3 possible choices as 3 levels of risk - high, meduim and low. We aim to analyze the effect of the level of success a player had in the first round of the game (defined directly by the ammount of money in ILS they gained) on the amount of risk they chose to take in the second round. 

For more specific definitions and more details in the attached research proposal in Hebrew (if you are interested in information in English feel free to contact me by Email).

### What this Project Conatins
We publish here the Jupyter notebook that contains the pre-proccessing that was performed as well as many visualizations of the data - mainly segmentation by gender, age, and order in the game (first / second / third / fourth player) and their effect on risk taking. 

### Our Additional Features
This repository also contains the data itself (downloaded from kaggle with our addition - the features p_i_j with i in (1,2,3) and j in (high, middle, low, neutral) that represents the amount of incouragment the i'th player got from the other players in their group to take the j'th amount of risk. The number in each of these features represents the amount of players in the group (out of a maximum of 3) that enncoureged the current player to take that amount of risk (where "neutral" represents no clear encouregment for a specific amount of risk). If the players in the group were not asked by the host to express their opinion, this was marked by an "-1". This data was collected manually by watching all 3 seacons of the show and trying to quantify the opinions of the players. These features were also visualized. 

This project was done as a part of "Neuropsychiatry - Cognition of Mental Disorders" course at the Hebrew University of Jerusalem in the fall semester of 2021. 
The preliminary research and the data collection were done by Ido Klainer, Yuval Ziv, Jonathan Kimelfeld, Keren Ben-Arie and Eytan Hodara, and the analysis and visualization was performed by Nitzan Barzilay.
