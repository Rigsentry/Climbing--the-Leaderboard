# Climbing the Leaderboard
An arcade game player wants to climb to the top of the leaderboard and track their ranking. The game uses Dense Ranking, so its leaderboard works like this:

The player with the highest score is ranked number **1** on the leaderboard.
Players who have equal scores receive the same ranking number, and the next player(s) receive the immediately following ranking number.

**Example**
```
ranked=[100, 90, 90, 80]
player=[70, 80, 105]
```
The ranked players will have ranks **1**, **2**, **2**, and **3**, respectively. If the player's scores are **70**, **80**, and **105**, their rankings after each game are **4**, **3**,  and **1**. Return **[4,3,1]**.

## Function Description

Complete the climbingLeaderboard function in the editor below.

climbingLeaderboard has the following parameter(s):

* int ranked[n]: the leaderboard scores
* int player[m]: the player's scores
## Returns

int[m]: the player's rank after each new score
## Input Format

Two list of ints
* The firs list contains the existing leaderboard scores in **descending** order.
* The second list contains the player's scores in **ascending** order.
```
public static List<int> climbingLeaderboard(List<int> ranked, List<int> player)
{

}
```
## Constraints
* The existing leaderboard input is in descending order.
* The player's scores input is in ascending order.

## Test Case #1
```
Input
[100 100 50 40 40 20 10]
[5 25 50 120]
Output
[6 4 2 1]
```
## Test Case #2
```
Input
[100 90 90 80 75 60]
[50 65 77 90 102]
Output
[6 5 4 2 1]
```


