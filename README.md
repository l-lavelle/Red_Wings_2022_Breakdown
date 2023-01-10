# Red_Wings_2022_Breakdown
Analysis of Beginning of 2022-2023 Red Wings Season

The following analysis looks at Red Wings data for in-season games from 10-14-22 to 12-31-22. I used the nhl public api to scrape data for the analysis. There are 4 jupyter notebooks broken down by concept.
1. **Scraping Game ID**: Using nhl api to find all the game ids for the Red Wings games 
2. **Creating and Cleaning Dataframe**: scraping choosen variables, related to shots, from 35 games used in the analysis and cleaning dataframe 
3. **Red Wings Analysis**: Transforming data to analyzing Red Wings offense and defense 
4. **Individual Game Shots**: Plots the goals, shots, and missed shots of both teams for each game 

**Analysis Overview**
* Red Wings percentage of shots made was 10.7%. Goalie save percentage was 89.4%.  
* Average number of shots taken per game: 
  + Red Wings: 30
  + Opponet: 32

* Types of Shots: 
  + Both Red Wings and opponets had similar percentages for the different type of shot
  + Wrist shot was the most common type (53% Red Wings, 54% opponets)
  + The next highest type of shots were: 
      + Snap shot: 17% 
      + Slap shot: 15% Red Wings, 12% opponets
      + Backhand 7% Red Wings, 8% opponets
