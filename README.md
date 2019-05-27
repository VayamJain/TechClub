# Questions

## Q.1) Suppose that Gammastack is organizing a Corporate Premier League (cricket). **You have to design the database schema for the management of this premier league.**
- **There are multiple teams in the tournament.**
- **Each team must have 11 players.**
  - **Each team must consist of:**
  - **Exactly one wicket-keeper**
  - **Exactly one captain**
  - **At least four batsmen**
  - **At least four bowlers**
  - **A team can have one vice-captain too (optional).**
- **There should be a schedule for the tournament which defines the dates, venues and teams for the matches to be held**
- **Top four teams from the league stage would qualify for the semi-finals and the final match will be played between the winners of the semi-finals.**
- **Each team must face all the other teams at least once in the league stage.**

## So for the above case give the schema. The answer should look like this

*Table Name:*
- *column1Name: dataType || columnType*
- *column2Name: dataType || columnType* 
- *column2Name: dataType || columnType*

## For a better understanding refer the sample below.

> For putting in the schema please follow the below syntax that is for a Customer-Person example
> Let the customer table has customer's name and the product id as a foreign key of the product that the customer has bought.
> 
> While the product table has the id and name.
> 
> The customer table looks like this
> 
> 
>     | id  |  name  | productId |
>     | --- |   ---  |    ---    |
>     |  a  |    b   |     c     |
>     |  a2 |   b2   |    c2     |
>     |  a3 |   b3   |    c3     |
> 
> Your customer table in the answer should look like this:
> 
> Customer:
> - id: integer || pK
> - name: string || notNull
> - productId: integer || fK
> 
> While the product table that looks like
> 
> | id  |  name  | 
> | --- |   ---  |
> |  a  |    b   |
> |  a2 |   b2   |
> |  a3 |   b3   |
> 
> Your product table in the answer should look like this:
> 
> Product
> - id: integer || pK
> - name: string || notNull

***
***
## Q2 Little Charlie loves chocolate. He frequently goes to his favorite store, Willy Wonka’s Chocolate House, to buy them. They are having a promotion at the store where 2 wrappers of chocolate can be exchanged for one chocolate ( now that's some offer !!) So for a X amount of money that Charlie initially has, **find the _final number_ of chocolates that Charlie gets to eat considering the cost of one chocolate is 2.**

## For a better understanding please refer the example below where the initial amount of money that Charlie has is 15.

> Solution: As mentioned Charlie has Rs. 10 to spend on bars of chocolate that cost Rs. 2 each. He can turn in 2 wrappers to receive another bar. Initially, he buys 5 bars and has 5 wrappers after eating them. He turns in 4 of them, leaving him with 1, for 2 more bars. After eating those two, he has 3  wrappers, turns in 2 leaving him with 1 wrapper and his new bar. Once he eats that one, he has  2 wrappers and turns them in for another bar. After eating that one, he only has 1 wrapper, and his feast ends. Overall, he has eaten 5 + 2 + 1 + 1 = 9 bars.
> 
> **Thus 9 is the final of number of chocolates that Charlie gets to eat.**

***
***

readme.md
Displaying readme.md.
