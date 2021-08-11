# ODI-Cricket-Match-Prediction

<h2>Overview</h2>
<p>
With the advent of statistical modeling in sports, predicting the outcome of a game has been established as a fundamental problem. Cricket is one of the most popular team games in the world. Moreover cricket betting is a multi-billion dollar market. Therefore, there is a strong incentive for models that can predict the outcomes of games and beat the odds provided by bookers. The aim of this study is to investigate to what degree it is possible to predict the outcome of cricket matches.
</p>
<p>
Cricket matches are quite unpredictable. Considering only ODI matches, we will try to predict who is going to be the winner of the match, before the match begins. 
Suppose we know that there is going to be an ODI match between Team A and Team B in near future. Before the match begins, our ML model should predict which team will win the match.
</p>

<h2>Data Collection</h2>
Ball by ball records of every international ODI match is available on the web, in computer readable format. The data has been gathered from <a href="https://cricsheet.org/"><u>Cricsheet</u></a>.Entire dataset has been built from scratch and every feature has been normalised before feeding into the model. 
<br>
<h2>Feature engineering</h2>
 <img src="team_features.png" alt="team_features" width="500" height="250"> 

<h2>The Main Approach</h2>
<ul>
  <li>We experimented with various classification models like Naive Bayes, Logistic Regression, Random Forest, SVC etc.</li>  
</li>
</ul>
<h2>Results</h2>
  <ul>
 <li>Linear Regression : 67%</li>
 <li>Support Vector Classifier : 67%</li>
 <li>Gaussian Naive bayes : 57%</li>
 <li>Random Forest : 49%</li>
  </ul>
<h2>Conclusion</h2>
It is possible to predict the winner of ODI  cricket games in more than two thirds of instances. This is an improvement upon levels present in the gambling industry today and implies a potential financial opportunity. However, the overall level of accuracy is lower than that observed in many other sports and undergoes more significant fluctuations. This suggests that ODI cricket has a relatively high level of instability or randomness within it, which should come as no surprise to those familiar with the game.<br>
Of the various methods tried, the most effective classification method was a Logistic Regression model combined with significant data preprocessing, feature selection and complex hierarchical features.<br>
With regards to future work, further avenues could be explored either in the form of new algorithms  or in the form of new features. This work has focused entirely on using team  performance based statistics as features. Whereas previous investigations  use predominantly categorical features, such as ‘home team’, ‘who won the toss’ or ‘venue’ for the same task. Combining these feature types could perhaps yield performance gains, however algorithm choice would be limited to those capable of dealing with both categorical and numerical features concurrently. In addition, external data such as the weather or social media comments could be mined to provide even more features for further experimentation.

