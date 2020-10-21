# Reinforcement Algorithm's

_Tries set of combinations to achieve 1's and reject 0's. Can be used to solve multi armed bandit problem._

## Mainly used algo's are :-
- UCB
- Thompson Sampling

## Multi Armed Bandit Problem solution using UCB (Upper Confidence Bound) Algo :-

**Problem**

- We have d-arms 
- Each time an user connects to the webpage , that makes a round
- At each round n, we choose one ad to display to the user
- At eacch round n, ad i guess reward ri(n) belongs to {0,1} : ri(n)=1 if the user clicked on the ad i, 0 if the user didn't.
- Our goal is to minimize the total reward we get over many rounds.

**Solution**

1. At each round n, we consider two numbers for each ad i :
   - Ni(n) - Number of times the ad i was selected up to round n
   - Ri(n) - Sum of rewards of the ad i upto round n
2. From these two numbers we compute :-
   - average reward of ad i upto round n : *ri^(n) = Ri(n)/Ni(n)*
   - confidence interval *[ri^(n) - delta i(n), ri^(n) + delta i(n)] at round n with delta i(n) = sqrt(3 Log(n)/ 2 Ni(n) )*
3. We select ad i that has the maximum UCB *ri^(n) + delta i(n)*
