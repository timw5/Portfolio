# Welcome to My Portfolio
<br/>

## My name is Tim Williams, I am a student at Weber State University pursuing a Bachelors degree in Computer Science, with a minor in Mathematics. 
## I am currently working as a Data Engineer at Marketstar.
<br/> <br/>
# Projects:
<br></br>
<hr>

## [Hangman](https://github.com/timw5/sliceofbread.epizy)
>>I Built this project using only php, and HTML. It has a login system connected to an azure sql database, and stores passwords salted, and hashed using sha-256. Below is a screenshot of the game itself. I use PHP's session storage to store relevant session information for each user. I implemented "Kanye.Rest" API to display kanye west quotes after each guess. Once you reach your last guess, I used the Dictionary.com api to display the definition of the word to guess.
[Click here](https://sliceofbread.epizy.com/Hangman/Login.php) to try the game
<br><br/>
![Hangman](/Assets/Hangman.png)
<br><br/>
>>
<br><br/>
<hr>
<br><br/>

## [Banking App](https://github.com/timw5/BankingApp)
>> This application simulates a banking application the database used is an azure sql server instance. It has a login system, and stores passwords salted, and hashed using sha-256. I store all application data in a database.<br><br/>
>>The application is built with RazorPages, C# on the back end, and razor(.cshtml) on the front end, with javascript. To manage the database instance within razorpages, I implemented Entity Framework. Below is a screenshot of the application. 
<br><br/>
![BankingApp](/Assets/banking.png)
<br><br/>
>>
<br><br/>
<hr>
<br><br/>


## [Stock Investing App](https://github.com/timw5/StockTradingApp)
>> This application simulates trading on the stock market, I used the Yahoo Finance api to get one years worth of stock data and stored it in an Azure SQL database. I used python, pandas, and sql alchemy as a small pipeline to get the stock information for all tickers on the s&p 500. The application is created using RazorPages, and Entity Framework. A user starts out with $10,000, on a random day in the last year. The user can then select a stock, and I use plottly to show the trend of the stock price for each day up until the random day selected. The user can then invest an amount, I provide 3 different input options to choose from, a number input box, a slider, and a pie chart. once a User makes a purchase the app fast forwards a week. The user can then choose to invest again in the same stock, hold for a week, choose a different stock to invest in, or quit. This continues until the user quits, or the current date is reached. 
<br><br/>
![StockInvestingApp](/Assets/Stocks.png)
<br><br/>
>>
<br><br/>
<hr>
<br><br/>


## [Multiplayer Boggle Game](https://github.com/timw5/Boggle)
>>This is application is a 2 player boggle game. It can support multiple games simultaneously, but only 2 users can play a game together at any given time. It is implemented using .Net Blazor, Azure signalR, websockets, Azure Sql Server, and hosted as an Azure WebApp. I use Python, pandas, and sql alchemy to create a small pipeline to download ~300,000 words in the english language, and store them in a database, and I created an AzureSignalR instance that supports web sockets. I implemented the DBContext for Entity Framework using a Factory design pattern and a context manager to prevent memory leaks, A context instance is created when it is needed, and deleted when it is done being used. I created a SignalR Hub that manages the user connections, and games being played. A user can create a game, and the hub will generate a random password. Another user can then join that game instance using the password, once both users have accepted, the boggle game will start. I fill a board with ~40% vowels, and the rest constants, displayed in a 4x4 grid. The user then tries to guess as many words as possible in 30 seconds, but each letter of the word must be adjacent to the current character selected. Each word entered is compared to the words stored in the database, and gets a certain number of points if the word is valid, depending on how many characters are in the word. After 30 seconds the game ends, and both word lists for each user, and scores are displayed. 
<br><br/>
![BoggleGame](/Assets/boggle.png)
<br><br/>



