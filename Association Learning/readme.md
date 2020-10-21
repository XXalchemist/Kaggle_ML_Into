# Association rule based learning

_Used to find association between multiple products or goods. ex :- Market analytics etc_

## Two main algo's :-
- Apriori
- Eclat (needs only support, can be used to find how often multiple things occurs together)

## Important terms 

*Support (M)* = # users doing M  / # total M 

*Confidence(M1->M2)* = # users doing M1 and M2 / # users doing only M1

*Lift(M1->M2)* = confidence(M1->M2) / Support (M2)

## Steps For Apriori

1. set a minimum support and confidence
2. take all the subsets in transactions having higher suppot than minimum support
3. take all the rules of three subsets having higher confidence than minimum confidence
4. sort the rule by decreasing lift


## Steps For Eclat

1. set a minimum support
2. take all the subsets in transactions having higher support than minimum support
3. sort these subsets by decreasing support