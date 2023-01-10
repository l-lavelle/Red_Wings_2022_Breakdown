# Red_Wings_2022_Breakdown
Analysis of Beginning of 2022-2023 Red Wings Season

The following analysis looks at Red Wings data for in-season games from 10-14-22 to 12-31-22. I used the nhl public api to scrape data for the analysis. There are 4 jupyter notebooks broken down by concept.
1. **Scraping Game ID**: Using nhl api to find all the game ids for the Red Wings games 
2. **Creating and Cleaning Dataframe**: scraping chosen variables, related to shots, from 35 games used in the analysis and cleaning dataframe 
3. **Red Wings Analysis**: Transforming data to analyze Red Wings offense and defense 
4. **Individual Game Shots**: Plots the goals, shots, and missed shots of both teams for each game 

**Analysis Overview**
* Red Wings percentage of shots made was 10.7%. Goalie save percentage was 89.4%.  
* Average number of shots taken per game: 
  + Red Wings: 30
  + Opponent: 32
* Types of Shots: 
  + Both Red Wings and opponents had similar percentages for the different type of shot
  + Wrist shot was the most common type (53% Red Wings, 54% opponents)
  + The next highest type of shots were: 
      + Snap shot: 17% 
      + Slap shot: 15% Red Wings, 12% opponents
      + Backhand 7% Red Wings, 8% opponents
* Types of Goals: 
  + The majority of goals for the Red Wings were scored using following types of shots: 
      + Wrist shot: 45 goals, percentage made: 8.4%
      + Snap shot: 25 goals, percentage made: 14%
      + Slap shot: 15 goals, percentage made: 9.9%
      + Tip in: 12 goals, percentage made: 19%
      
      
*Surprising  to find that although the vast majority of shots were wrist shots the amount of goals scored wasn't significantly higher than the other categories. In the future it would be interesting to see if the type of shot was impacted by ice rink coordinates. 
* Strength on Goal: 
  + Again both the Red Wings and opponents had similar percentages for the team stregnth on goal 
  + Red Wings: 
      + Even: 74%
      + Power play: 24%
      + Short-handed: 2%
  + Opponent:
      + Even: 75%
      + Power play: 20%
      + Short-handed: 5%


 *These values are as expected with high percentage scored when team stregnth was even. Almost a quarter during power play which even though is a short amount of time gives the team and advantage. There are a small percent of goals when short handed due to the disadvantage in player stregnth. 
 
 ![image](https://user-images.githubusercontent.com/117859017/211636021-15649bab-51c0-4889-a146-63932db71f06.png)
 
 ![image](https://user-images.githubusercontent.com/117859017/211636112-1d3e4df7-b9c2-4036-9b46-e3cb41a2afe2.png)

![image](https://user-images.githubusercontent.com/117859017/211636174-ac315b14-82eb-4c9c-9822-d37f1e50a358.png)

![image](https://user-images.githubusercontent.com/117859017/211636210-68b6091a-6992-44b9-b360-6313eab26343.png)
