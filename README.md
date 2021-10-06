# Virtual Stock Market Game

This repository contains a virtual stock market game that allows users to compete with their friends to see who can make the most money in the stock market in a given period of time. It was built with an Agile scrum team of four (Russell Himes, Grace Malles, and Alison Walker) as a final capstone project at [Tech Elevator's 14 week coding bootcamp](https://www.techelevator.com/aptitude-test-referred?mbsy_source=183cf48e-9fe1-484e-a967-fd43e3c4fb34&mbsy_exp=Mon%2C+01+Jul+2024+17%3A08%3A30+GMT&campaignid=36038&mbsy=3s6sdT). The project uses Java and Spring Boot on the back end and Vue.js on the front end. We used Finnhub API for real-time stock data and ECharts library to display data.

## Features

The game was built based around the following user stories.

### MVP:
<ol>
  <li>Register: As a Player, I can register with the system so that I can log in and play.</li>
  <li>Login: As a Player, I can login so that I can play.</li>
  <li>Create Game: As a Player, I can create a new game and I will assigned as the Organizer for that game. A game will have an end date when the game will finish and a name.</li>
  <li>Invite Players to Game: As an Organizer, I can invite existing Players into my game. They will be given an initial $100,000 to invest.</li>
   <li>View Games: As a Player, I can see a list of all my current games.</li>
   <li>See Leaderboard: As a Player, I can see the running total of the portfolio value of all the other players in this game.</li>
   <li>Buy a Stock: As a Player, I can buy a stock. I can specify the trade in dollars or in shares.</li>
   <li>Sell a Stock: As a Player, I can sell a stock. The value of the trade will be added to my available cash immediately.</li>
   <li>See Stocks: As a Player, I can see my available cash and the status of all of my current stocks.</li>
   <li>Game End: When the game end date is reached, the system will sell all outstanding stock balances for all the Players in the game and prevent anymore trades from happening. The winner is the Player with the most cash.</li>
</ol>

### Bonus Features:
<ol>
  <li>Search for Stocks: As a Player, I can search for and research stocks on the site so that I can pick a good one to buy.</li>  
  <li>Countdown Timer: As a Player, I can see a timer that displays the time remaining in the game.</li>  
  <li>See Trades: As a Player, I can see all of the trades that I’ve done in the game.</li>  
  <li>Visualizations: As a Player, I can see on a graph how my investments are doing and how my cash has changed over time.</li>  
</ol>
