**This is a possession meter for soccer/football games. **

Possession in football is defined as the fraction of game time in which a team has control of the ball. This is a major indicator of team strength and strategy in football analytics, and is hence a very important metric to be measured. Some analysts measure time elapsed whlst a team has the ball, and others prefer measuring number of passes as an indicator of posession, but either methodologies work just fine. In this notebook, timee is utilized as passing is a bit to easy to implement. 


Traditionally, ball posession belonged either to team A or team B. However, the new FIFA rules in the Qatar world cup added a new category, called_ "in-contest"_ which means that neither team have control of the ball, and instead are fighting to get it. This model is also capable of determining _in contest_ time, by measuring the position of the ball relative to either teams in each frame and comparing it to a threshold, much like how possession is also determined in the noteboko.


Model is far from perfect as it largely depends on the disparity of colors between teams, since it uses a grayscale threshold to determine the different sides of the players.


If you have any inquiries, feel free to reach out to me, I'm more than open to critique.

https://github.com/mehdikhfifi/footballplayerpossessiondetection/assets/145874140/aba0f98a-8607-46a8-8bee-fecd1f8127ca
