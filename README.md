# 2D Arrays Review

## Due: Fri 9/9 at 11:59 PM

- Create a program called `Arrays2DReview.java`
- Prompt the user for a filename
  - The first line will be the number of players on the team
  - The second line will be the number of statistics for each player
  - The rest of the file will be the data
- Read the data into a 2D array
- Calculate how many points each player scored
  - Normal shots are worth two points, free throws are worth one point
- Calculate how many points the team scored as a whole
- Calculate each player's free throw percentage (rounded to one decimal place)

***Example Input:***\
input.txt\
***Example contents of input.txt:***\
8\
4\
Player; Shots Attempted; Shots Made; Free Throws Attempted; Free Throws Made\
23; 10; 2; 4; 4\
13; 6; 3; 2; 1\
45; 8; 3; 3; 3\
33; 6; 0; 2; 2\
11; 2; 2; 0; 0\
25; 7; 5; 2; 1\
31; 6; 2; 3; 2\
35; 6; 4; 4; 2\
***Example Output:***\
Player 23 scored 8 points\
Player 13 scored 7 points\
Player 45 scored 9 points\
Player 33 scored 2 points\
Player 11 scored 4 points\
Player 25 scored 11 points\
Player 31 scored 6 points\
Player 35 scored 10 points\
The team scored 57 points\
Player 23 had a free throw percentage of 100.0%\
Player 13 had a free throw percentage of 50.0%\
Player 45 had a free throw percentage of 100.0%\
Player 33 had a free throw percentage of 100.0%\
Player 11 had a free throw percentage of 0.0%\
Player 25 had a free throw percentage of 50.0%\
Player 31 had a free throw percentage of 66.7%\
Player 35 had a free throw percentage of 50.0%
