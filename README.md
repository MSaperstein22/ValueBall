# ValueBall

I've been playing fantasy football since 2014. Each year, however, I would always become frustrated with the top analysts' preseason projections as they never seemed to be accurate by the end of the season. Their preseason projections would always closely mirror the final player rankings from the previous year, relying almost entirely on recency bias instead of statistical projections. In 2020, I decided to create a better way to project fantasy football performance using a spreadsheet to achieve the following goals:

1. Target players who are being undervalued ✅
2. Trade players who are being overvalued ⛔️
3. Finally beat my friends in fantasy football 😎

# Explanation
My attitude when playing fantasy football has always been if a wide reciever gets more targets, there is a greater chance that he will get more yards and touchdowns and score more points. Logically, this makes sense. The first step to recievers gaining yards and touchdowns is by getting receptions. And every new reception is a new chance to accumulate yards and score a touchdown.

In fantasy football, however, targets are not accounted for in the scoring. As a result, this statistic is often overlooked by even the most experienced fantasy football managers. **I needed to create a way to factor in targets along with all of the other typical stats to better value recievers based on their most recent performance.**

# Spreadsheet
In my original spreadsheet, I assigned each target a value of 0.74 points. I chose this value because it is close to the points a wide reciver would score for picking up a first down (each reciving yard is worth 0.1 points so this value is equivalent to 7.4 yards), but less than the value for a reception in a PPR league (1 point). By adding up the average points from targets, average points from yards, and average points from TDs per game, each player receives a new, original score. This score gives us a better view of how to value wide recievers because it takes into account the probability of a wide reciever scoring more points in the future. This spreadsheet would be able to highlight players who are currently recieving a ton of targets yet are not currently scoring the most yards or touchdowns in fantasy. These players are important to value highly because they are primed to score more yards and touchdowns in the future.

I then ranked the WRs according to my scoring and compared that to the actual non-ppr fantasy scoring. The difference here is key: if the box is green and has a higher number, it means the player is being undervalued and you should buy him ASAP. If the box is red and has a higher number, it means the player is being overvalued, he's probably touchdown dependent, and you should probably try to sell high. By looking at this spreadsheet, I was able to sell some of my players high to other teams last year and trade for and add players who were being undervalued according to my analytics system.

The spreadsheet is automatically updated with the most recent data from the current NFL season. Access it using the following link: https://docs.google.com/spreadsheets/d/1kpf9QdxtBV0tafUXUwOGLNR5V8OyPvUlc23D0oR21vI/edit?usp=sharing

Below are some screenshots of the spreadsheet after Week 3 of the 2023 NFL season.

## Top Stats ##
<img width="335" alt="Screenshot 2023-09-26 at 4 08 49 PM" src="https://github.com/MSaperstein22/ValueBall/assets/109482908/13c28421-e21e-4cf8-98c1-a95eed384479">


<br>

## Buy Lows ##
<img width="334" alt="Screenshot 2023-09-26 at 4 09 02 PM" src="https://github.com/MSaperstein22/ValueBall/assets/109482908/ad8b8f33-8521-480e-89ac-2b90ade3e575">
<br>

## Sell Highs ##
<img width="335" alt="Screenshot 2023-09-26 at 4 09 13 PM" src="https://github.com/MSaperstein22/ValueBall/assets/109482908/ae520571-57ea-44b7-be46-2838c0a0a00a">

# Impact
