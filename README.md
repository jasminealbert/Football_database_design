# Football Database Design
## Creating a database of a company's football league's results

### Table of contents
- [Scenario](#Scenario)
- [Creating the database](#Creating-the-database)
- [Testing the database](#Testing-the-database)
- [Author Info](#author-info)


# Scenario

Our company organised a football tournament and requested a database be produced to easily find the team, organisation, players, fixtures and results. We had the dates and results of each game in the tournament, where each team plays each other twice, home and away. The following gives further information on the task:
- There are 4 teams in the tournament
- There are players from 8 organisations participating which may play for any of the 4 teams
- Standard points for football tournaments apply: 3 points for a win, 1 for a draw, 0 for a loss
- There are 3 pitches where the games took place

[Back To The Top](#Football-Database_Design)

# Creating the database

The following entity relationship (ER) diagram was used to create the database in Postgres. This is in third normal form.

![image](https://user-images.githubusercontent.com/116348107/215105913-9bec81e5-d5f8-4007-89ca-1bfd23d21f3a.png)

As seen, there are multiple separate tables in this diagram. The data for each table was manually inputted to CSVs and then imported into pgAdmin. 

[Back To The Top](#Football-Database_Design)

# Testing the database

From this, many tests were performed using SQL to show the data was inputted correctly and the separate tables can be joined. An example of this is shown below.

![image](https://user-images.githubusercontent.com/116348107/215107184-05c9ddde-208c-4cf7-be8b-65a953d415cd.png)

[Back To The Top](#Football-Database_Design)

## Author Info

- LinkedIn - [Jasmine Albert](https://www.linkedin.com/in/jasmine-albert-99029b207/)

[Back To The Top](#Football-Database_Design)
