# ValueBall

I've been playing fantasy football since 2014. Each year, however, I would always become frustrated with the top analysts' preseason projections as they never seemed to be accurate by the end of the season. Their preseason projections would always closely mirror the final player rankings from the previous year, relying almost entirely on recency bias instead of statistical projections. In 2020, I decided to create a better way to project fantasy football performance using a spreadsheet to achieve the following goals:

1. Target players who are being undervalued ✅
2. Trade players who are being overvalued ⛔️
3. Finally beat my friends in fantasy football 😎

# Case Study - 2019 NFL Season

Matt Bowden is an ESPN staff writer. The following table compares his 2019 preseason wide reciever fantasy rankings to the 2019 final wide reciever fantasy rankings at the end of the season.

<br>
<img width="468" alt="Screenshot 2023-09-26 at 4 43 43 PM" src="https://github.com/MSaperstein22/ValueBall/assets/109482908/24ea4dbf-500b-4fcd-9511-a79a146c8ab0">
<br>
<br>

9 players who Bowden suggested would finish the season in the top 20 did not achieve that feat. Additionally, 3 other recievers who Bowden predicted would make the top 20 did so but they performed worse in the rankings than Bowden predicted. This shows how the analysts' preseason projections for wide recievers can be very inaccurate.

# Purpose
My attitude when playing fantasy football has always been if a wide reciever gets more targets, there is a greater chance that he will get more yards and touchdowns and score more points. Logically, this makes sense. The first step to recievers gaining yards and touchdowns is by getting receptions. And every new reception is a new chance to accumulate yards and score a touchdown.

In fantasy football, however, targets are not accounted for in the scoring. As a result, this statistic is often overlooked by even the most experienced fantasy football managers. **I needed to create a way to factor in targets along with all of the other typical stats to better value recievers based on their most recent performance.**

# Spreadsheet
In my original spreadsheet, I assigned each target a value of 0.74 points. I chose this value because it is more than the points given for one reciving yard (0.1 points), but less than the value for a reception in a PPR league (1 point). This is somewhat subjective, however, I chose to weigh the point value of each target to be closer to the point value of a reception than the point value of 1 recieving yard. This is because targets should be factored into our scoring in an influential way, but at the end of the day, a reception is more valuable than a target (in both PPR and non-PPR leagues) because it allows a player to gain points. This is true because recieving yards are accounted for in fantasy football scoring but targets are not.

By adding up the average points from targets, average points from yards, and average points from TDs per game, each player receives a new, original score. This score gives us a better view of how to value wide recievers because it takes into account a player's current number of targets. By my main mantra, this integrates the probability for a wide reciever scoring more points in the future into the new score. This spreadsheet could then highlight players who are currently recieving a ton of targets yet are not currently scoring the most yards or touchdowns in fantasy. These players are important to value highly because they are primed to score more yards and touchdowns in the future, yet might currently be undervalued.

I then ranked the recievers according to my scoring and compared that to the actual non-PPR fantasy scoring. The difference here is key: if the box is green and has a higher number, it means the player is being undervalued (he's recieving many targets but not yet scoring touchdowns) and you should buy him ASAP because there's a high chance he will score touchdowns in the future. If the box is red and has a higher number, it means the player is being overvalued (he's probably touchdown dependent and does not recieve many targets) and you should probably try to sell high because he's not being thrown the ball enough to have a high chance to score touchdowns in the future. By looking at this spreadsheet, I was able to sell some of my players high to other teams last year and trade for and add players who were being undervalued according to my analytics system.

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
