# NFL Score Regression
#### Project 4 for EECS 731

Data for NFL games could be found at 

https://github.com/fivethirtyeight/nfl-elo-game  <br>



Part I: Data Preparation and Overview  <br>

  * Load all three data sets into panda data frames and get general infomations about their data shape

  * Shows totla game played by each team 

  

Part II: Regression models

  * Set score for team 1 as regressand;
    Set features 'elo1','elo2','elo_prob1','score2','total' as regressor
    
  * Set data training ratio as 0.8

  * Linear regression model
  
  * Linear SVM regresion model  
  
  * Neural Netword model

    > Set learning rate as 0.2 and 0.1
    
  * Random Forest model





Discussion

   * Linear regression model gives the most accurate predition among all models

   * Different learning rate setting for Neural Network model will lead to a big difference on the prediction results


More details could be found in code comments.
