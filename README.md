# Olympics-Ranking
In Olympics, the countries are ranked by the total number of medals won. You are given six integers G1, S1, B1, and G2, S2, B2, the number of gold, silver and bronze medals won by two different counties respectively. Determine which country is ranked better on the leaderboard. It is guaranteed that there will not be a tie between the two countries.


m=int(input())
for j in range(m):
    g1,s1,b1,g2,s2,b2,=map(int,input().split())
    if(g1+s1+b1)>(g2+s2+b2):
        print("1")
    else:
        print("2")
