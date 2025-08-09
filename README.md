# SQL-IPL-Match-Bidding-App

## Industry Review 
- Pi-in-the-sky is an app which falls under industry, fantasy sports.
- Ipl falls squarely in the domain of consumption even if it is in the form of    sports and entertainment, instead of usual consumption goods.

## Tools & Technologies Used
**SQL programming skills :** 
`Common table expression` · `Derived table` · `subqueries(co-related and non-corelated)` · `joins` · `Trigggers`· 

## Tables
- IPL_User
- IPL_Stadium
- IPL_Team
- IPL_Player
- IPL_Team_players
- IPL_Tournament
- IPL_Match
- IPL_Match_Schedule
- IPL_Bidder_Details
- IPL_Bidding_Details
- IPL_Bidder_Points
- IPL_Team_Standings
 
## Data Set Description
- Pie-in-the-Sky is a mobile app that is used for bidding for IPL matches legally. Any registered user can bid for any of the IPL matches listed in it. 
- New users or bidders need to register themselves into the app by providing their mobile phone number, email id, and password. Admin will maintain the match roster and keep updating other details in the system.
- The app shows the match details which include the playing team, the venue of the match, and the current standing of the teams on the points table. 
- It will display the winner at the end of the match and update the team standings in the tournament and bidder points table. System will send updates to the bidders whenever required. It will also generate the bidders' leaderboard.


## Business Questions Discussion (Shared with the project document) 
1. Show the percentage of wins of each bidder in the order of highest to lowest percentage
- **Understanding**:  Here the list of bidder is to shown in percentage basis in descending order
2. Display the number of matches conducted at each stadium with the stadium name and city.
- **Understanding:**  Here the list of matches conducted at each stadium its name and city is to be displayed 
3. In a given stadium, what is the percentage of wins by a team which has won the toss?
- **Understanding:**  Here in the stadiums, we have to provide the percentage of wins by a team who has won the toss 
4. Show the total bids along with the bid team and team name.
- **Understanding:**  Here the total bids, bid team and team name is to be displayed 
5. Show the team id who won the match as per the win details.
- **Understanding:**  Here we have to show the team id, who has won the match as per the win details
6. Display total matches played, total matches won and total matches lost by the team along with its team name.
- **Understanding:**  Here we have to show total matches played, total matches won and total matches lost by the team along with its team name.
7. Display the bowlers for the Mumbai Indians team.
- **Understanding:**  Here we have to the bowlers for the Mumbai Indians team 
8. How many all-rounders are there in each team, Display the teams with more than 4 all-rounders in descending order.
- **Understanding:**  Here we have to list the teams with more than 4 all-rounders in descending order.
9. Write a query to get the total bidders points for each bidding status of those bidders who bid on CSK when it won the match in M. Chinnaswamy Stadium bidding year-wise. Note the total bidders’ points in descending order and the year is bidding year.
Display columns: bidding status, bid date as year, total bidder’s points
10. Extract the Bowlers and All Rounders those are in the 5 highest number of wickets.
- **Note** 
    1. use the performance_dtls column from ipl_player to get the total number of wickets
    2. Do not use the limit method because it might not give appropriate results when players have the same number of wickets
    3. Do not use joins in any cases.
    4. Display the following columns teamn_name, player_name, and player_role.
11. Show the percentage of toss wins of each bidder and display the results in descending order based on the percentage
12. Find the IPL season which has min duration and max duration.
- **Output columns should be like the below:** Tournment_ID, Tourment_name, Duration column, Duration
13. Write a query to display to calculate the total points month-wise for the 2017 bid year. 
sort the results based on total points in descending order and month-wise in ascending order.
- **Note: Display the following columns:** 1. Bidder ID, 2. Bidder Name, 3. bid date as Year, 4. bid date as Month, 5. Total points
Only use joins for the above query queries.
14. Write a query for the above question using sub queries by having the same constraints as the above question.
    - subquerys are used to get the columns of one table in the end. Here we can't get bidder_name , year(bid_date) as they 
    - all are in the different 
    - tables and thus joins are necessary. 
15. Write a query to get the top 3 and bottom 3 bidders based on the total bidding points for the 2018 bidding year.
- **Output columns should be like:**
Bidder Id, Ranks (optional), Total points, Highest_3_Bidders --> columns contains name of bidder, Lowest_3_Bidders  --> columns contains name of bidder;
16. Create two tables called Student_details and Student_details_backup.
- **Table 1:** Attributes : Student id, Student name, mail id, mobile no.	
- **Table 2:** Attributes : Student id, student name, mail id, mobile no.

Feel free to add more columns the above one is just an example schema.
Assume you are working in an Ed-tech company namely Great Learning where you will be inserting and modifying the 
details of the students in the Student details table. Every time the students changed their details like mobile number, 
You need to update their details in the student details table.  Here is one thing you should ensure whenever the 
new students' details come, you should also store them in the Student backup table so that if you modify the details in the 
student details table, you will be having the old details safely.

You need not insert the records separately into both tables rather Create a trigger in such a way that It should insert the 
details into the Student back table when you inserted the student details into the student table automatically.

## Business Questions Discussion (Identified by the students) 
- Question 1: Which teams have got the highest and the lowest no. of bids?
- Question 2: Display all the matches which are cancelled at each stadium with the stadium name, city.

## Conclusion
### Lessons learned: -
- During working on our project, we learnt how to analyse and understand the data and to get insightful inference from that data.
- Below mentioned are inferences that we found out from data :-
    - We got somewhat idea about how to predict winning team by taking Pitch condition and toss winning decision into consideration.
    - There are few stadiums where toss winning is very important as more than 60% of the time the team who won the toss also won the match.

## Domain understanding developed:-
- pi in the sky is an app which falls under industry, fantasy sports.
- ipl falls squarely in the domain of consumption even if it is in the form of sports and entertainment, instead of usual consumption goods.

##  Contributions
Suggestions, improvements, and issues are welcome. Feel free to fork the repo or raise a pull request!

## Contact
**Rasika Vispute**  
Email: rasikavispute32@gmail.com 
LinkedIn: https://www.linkedin.com/in/rasikavispute/
