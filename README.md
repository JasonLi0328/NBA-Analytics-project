# NBA-Analytics-project
--The aim of my project is to value NBA players. By constructing a regression model, I hope to identify undervalued and overvalued players and gain better understanding of how NBA players are valued.<br />
--The time frame of this project is from the 2005 - 2024 season. With 8332 entries and 55 attributes. <br />
--Conclusion:  <br />
1. “points per game” is the single most important stats in NBA, it alone could explain 48% of the difference in salary among players. <br />
2. 37% of variance is not captured with game related data points, my hypothesis is business related value like fan base and popularity.

## Attributes
![image](https://github.com/user-attachments/assets/2ca7ba88-c7c1-4ef9-a398-f431b3470869)
## Data exploration
![image](https://github.com/user-attachments/assets/71bbe1c8-5fc9-4ad3-a366-07115f7572e6)
![image](https://github.com/user-attachments/assets/26d12091-1b65-468f-8809-50006d69902f)
Here is a graph comparing the average of attributes between different positions. We can observe that guards have higher shooting percentage and assist, while center have higher rebounds and blocks. Since different positions have different roles in the game, I have decided to value players based on their position.
![image](https://github.com/user-attachments/assets/f0666b90-908f-4087-ab80-690d8ef787a0)
## Correlation Analysis
![image](https://github.com/user-attachments/assets/3d1b8cba-d99d-4720-b74f-afac694bfc6e)
![image](https://github.com/user-attachments/assets/88267a8b-6144-4f2f-ad0e-570611b25e06)
![image](https://github.com/user-attachments/assets/511795d8-5821-487c-9236-6dd0c2bd290c)
![image](https://github.com/user-attachments/assets/88e20fb1-a1d7-4752-b7f2-48d652670d88)

# Conclusion
“points per game” is the single most important stats in NBA, and not surprisingly, it alone could explain 48% of the difference in salary among players.
Moving forward, I plan to split the dataset between star players and role players. I also intend to try different regression models to try to improve the effectiveness of the models.
I would love to hear your suggestions! Thank you!

