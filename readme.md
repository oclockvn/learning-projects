# Projects

## 1. ✅ Github crawler console
   Crawl repos from github using github api then save the result to file
   Each repo is saved in a separate folder using owner's name. Details of file will be description of the repo.
   For example:
   ```
   > Enter your search: dotnet
   Searching for dotnet repos...
   Found 10 results. Saving to files...
   microsoft/dotnet.txt
   efcore/dotnet.txt
   ```
   Link to the repo: xxx
   
## 2. Github crawler windows form
   Similar to project 1 but display the result on windows form listview. Then check the repos to export to csv.
   ![image](https://github.com/oclockvn/learning-projects/assets/3783976/4eb316cb-f87c-41e1-ba8a-760cc4fea1fa)

## 3. ✅ Crazy timer
   You have been employed to create a program which will work out the number of 
   seconds there are in a time expressed in hours, minutes and seconds. The user enters 
   the number of hours, minute and seconds and the program then displays the number 
   of seconds equivalent to that time. The program should be used in the following way:

   Countdown Timer Calculator by Rob Miles 
   Version 1.0  
   Enter the number of hours: 3  
   Enter the number of minutes: 20  
   Enter the number of seconds: 50  
   The total number of seconds is: 12050 

   **Repo**: https://github.com/oclockvn/crazytimer

## 4. Simple ATM Software
   **Requirements:**
   This simple project will essentially create a simulation of an ATM within a Windows program. Just like an ATM, the program should have at least the following features:
   
   Checking whether an input – such as an ATM card (a debit/credit card number) – is recorded correctly
   Verifying the user by asking for a PIN
   In case of negative verification, logging out the user
   In case of positive verification, showing multiple options, including cash availability, the previous five transactions, and cash withdrawal
   Giving the user the ability to withdraw up to $1,000 worth of cash in one transaction, with total transactions limited to ten per day.
   For a more complicated program, include the ability to register a new PIN and mobile number, a detailed bank statement, and a “fast” cash withdrawal system for quickly withdrawing $20, $50, or $100.
   
   **Expectation**
   - Write a windows form app for the ATM above
   - Save (Read/write) the data to file

   **Wireframe**
   [Visily-Export_16-01-2024_03-17.pdf](https://github.com/oclockvn/learning-projects/files/13947204/Visily-Export_16-01-2024_03-17.pdf)

   **Hint**
   - Use bank.json for data source 
   [bank.json](https://github.com/oclockvn/learning-projects/files/13947239/bank.json)
   - use JsonDeserialize/JsonSerialize

## 5. Film Library

You all know and love IMDB, so how about making a little film library database of your own? This will be a desktop app that stores data about movies you own/love/want to watch. The app should be able to:

- Store data on a new movie
- Retrieve data on a movie that exists in the library
- Include search functionality and the ability to edit entries

You can use Microsoft SQL Server for the database and Visual Studio for the front end. What other features can you think of adding? Maybe you could make it pull data from IMDB to populate your applications. Maybe it could pull images, movie posters, and trailers from the web.

**Technical**
- Use httpclient to fetch data from https://www.omdbapi.com/
- Use entity framework to store data to sqlserver db
- Use dependency injection to manage dependencies
- Use interface

**Wireframe** 
[movie-proj-design.pdf](https://github.com/oclockvn/learning-projects/files/14011914/movie-proj-design.pdf)
