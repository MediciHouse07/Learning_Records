# Lecture 1
## REX 1 2022/08/04

2022/08/04

5331<->End

- interactability critique
- np completeness

2022/08/02

2033<->5331

- no luxury to design a game from scratch, more on understanding existing game or improve it
- price of anarchy
- dominant strategy is a weak assumption
- every bimatrix game has a NE

2022/08/02:

0000<->1500

- allignment between participant want and designer want
- assume best effort from all team and all matches
- 2033 mins killer apps

2022/05/16:
finished,
0000<->2300
0123 mins, autonomous;
0400 mins, round robin;
0957 mins, much better, believed much better;
1500 mins, tournament;
this course is more close to computer science, I can still learn it when I tend to like computer science, sometimes I do like that. And, because I will feel excited when I learn econ wise of game theory or incentive theory, so I guess I will put myself close to that direction, hope that I can find a balance between the two.

# Lecture 2
## REX 1 2022/08/23

## JMP 2 2022/09/10
## JMP 1 2022/08/23

2022/10/05

0000<->1000

- nevertheless
- private evaluation, who win, how much they pay
- maximaze social surplus, DSIC
- quasilinear utility, losing = 0 utility, utility of wining = evaluation minus price
- vi minus p
- 0526 mins sealed bid auctions
- each bidder submit a bid to the auction designer
- suppose you don't need to pay, you write as high you can bid
- bidder's behaviour will be changed if the price logic differs
- no discourage from overbidding
- 0933 mins first price auction

2022/09/10

5000 <->End

- click through rate is to quantify the slot's difference, alpha
- alpha is not dependent on the occupation
- 5700 mins, till here is assumptions setup
- bidder has private evaluation, vi, vi times alpha j
- till 5900 mins, is about assumption
- Desired 1. DSIC auction
- 2. maximize social surplus
- fraction of the click player get, xi, is the CTR of the slot i get assigned
- for the bidder that didn't get slot, xi is 0
- poly time to gurantee the algorithm running on real time
- one bidder can only get one slot
- assume DSIC, how to assign slots


2022/08/23: Jump way of reviewing

4832<->End

- one slot, is single item auction
- goods are not the same, goods here are slots
- above 2 makes it different with single item auction, if it is a single item auction, you can use second price auction
- alpha, probability of clicking the j's slot
- CTR
- vi time alpha j, unless alpha is 100% otherwise it can't reflect advertizer's valuation, because they care about click
- which advertizr to pick, which order they should be on, what price they should pay
- DSIC auction
- xi is the CTR of the slot i get assigned
- subject to feasibility, one advertizer per slot
- 10300 mins question about one bidder get more than one slot
- he will continue to talk this topic in the next lecture
- decide who wins, decide the winner to pay
- it has to be a joint activity
- 11100 mins answer to step 1

2022/08/23

6000<->End

- report your true value is DS
- v i alpha i
- maximize social surplus
- poly time
- 10700 mins no voice
- 10830 mins voice back

2022/08/22

4500<->6000

- collusion
- 4743 sponsor search auction
- sponsor links, organic search results
- bid on keyword
- single item auction
- slots are the sponsor list
- click through rate

2022/08/21

3000<->4500

- only two things are possible
- vi and B, vi-B
- second price auction is no regret
- every honest bidder gets non negtative utility
- 1.dominant strategy, incentive compatible DSIC, claim 1 + claim 2
- 2. Vickrey auction is awesome, social surplus = SIGMA vixi

2022/08/20

0000<->1500

- give the person who evaluate the price of it the most, and that end up with people just write the highest number
- name birthday, evaluation = mm + dd) times .10, mine is 2 D, the most is 4.3 USD
- no need to pay the price you evaluate can be a useful method of weighing people for a job

1500<->3000

- that is evaluation, not price, OK price is also a depends thing
- what if the 1 1 people bid it then sell it to a 12 31 people, this would end up with better off for two person
- no need to pay is definitely equal to people running for a job
- ebay is not first price auction
- ebay pay the second highest bid
- sealed bid auction
- designer to predict what would happen
- second bid auction would result in vi=bi, each bidders true price is revealed, that is also a dominant strategy
- b_minus i
- is utility is maximized by bidding vi
- B = max bj j<>i

2022/08/05

0000<->1500

- single item auctions
- sealed bid auction
- not to discourage the incentive to overbidding
- sealed bid, first price auction

# Lecture 3

## REX 1 2022/09/10
## JMP 2 2022/09/02

2022/09/10:

0000<->End

- now it is time to think about how to get DSIC
- greedy algorithm
- single parameter means vi is the only unknown
- feasible allocations
- xi set is the amount of stuff everybody gets
- allocation rule, who wins, how much to pay, payment rule
- x(b) belongs to X set, p(b), they are all vectors
- x is slot j for player i
- 1500 mins, followed till this minute
- bound ensure non negative utility for truthful bidders, this step is still based on truthful bidder
- 1700 mins, till here is some extra or more specific setup
- 1830 mins, allocaiton rule is implementable if
- first price rule is not implementable
- monotune
- second definition, an allocation rule is monotune, the higher you bid, the more you get
- single bid auction is monotune
- 2700 mins, seems go to another case now...
- design space
- if allocation rule exist, then it is about payment rule
- myerson's lemma
- assign good to the highest bidder, unique, talking about allocation rule, it is the only one
- thus, the left thing is payment rule
- greedy algorithm
- 3400 mins punch line
- coupling means (x,p) 4800 mins example
- fix i b minus i(other's bid)
- 4230 mins
- designate
- 5500 mins, if not monotune, the inequality fails
- jump is x(y) minus x(z)
- p is changing at every single point
- y and z getting closer, z times jump = payment jump
- jump in p of z = z times jump in x at z
- 10230 mins, payment formula is derived
- 10700 mins, sort proved the second price is the best one
- 10830 mins, proof by picture
- sponsored search auction is an application of myerson's lemma

2022/09/02

0000<->2000

- vixi(b)-pi(b)
- non negative utility

1500<->2200

- didn't follow

2022/08/25

0000<->1500

- 3 orthognal property are satisfied in vbk rule
- vi is value per unit of goods
- one parameter means only vi is unknown
- pick who wins is allocation rule, pay how much is payment rule
- utility = vi times xi(b) minus pi(b)

# Lecture 4

2022/10/03

0000<->0700

- meyerson's lemma application
- who wins, how much they should pay
- need to double check meyerson's lemma and the previous 2 lectures
