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
## REX 2 2022/10/28
## REX 1 2022/08/23

## JMP 2 2022/09/10
## JMP 1 2022/08/23

3600<->4600

2023/07/15

- maximize social surplus
- linearly time auction
- single item auction
- other auction as good as above
- lots of goods, not identical
- can we have those properties simultaneously

2023/07/13

2000<->3500

- wanky notation
- game designer knows what is the return

2022/10/28

5000<->End

- can't immediately use vickery auction
- the higher the slop the more the value
- click through rate
- adviser cares about click through
- vi times alphaj
- solve the allocation problem automatically, even though we don't know their evaluation, run as if we knew their evaluation
- xi = CTR of i gets assigned
- poly time, linear time
- pick winner couple with correct payment, joint
- solve the problem by dealing with them individually
- dependent on one is true
- next best
- assign jth highest bidder the jth slot

2022/10/27

3500<->5000

- vickery auction, 1 DSIC(bidding true value, gurantee non neg utility), 2  maximize the social surplus(one precondition is we don't know the people's true evaluation), 3 poly time
- overarching
- maybe the idea is to not to let them bid less than their evaluation
- bid higher is not good for individual, it can only harm others, if only think about individual's own utility, bid their evaluation is the minimum effort to pay to gain the goods, then why bid more?
- 1 which advertiser will be shown, 2 in which order, 3 what they are going to pay

2022/10/26

2000<->3500

- minimum amount to beat other competitors
- 2nd price = vickery auction
- easy to predict what would happen, easy to know what to do
- every bidder has an obvious(DS) strategy
- guranteed to maximaize the player i 's utility
- first price 2500 mins, has a lot to think, thus make the problem more complex
- 2600 mins, why vickery auction is great
- vi-B
- first price auction will be vi minus Bi
- 3230 mins, end of proof
- 2nd price auction, truth telling bidder gets non negative utility
- pays something that is less then the winner's evaluation
- under this auction, you may want to tell the truth because it maximizes your utility
- what if i didn't win, if i bidd higher than vi, utility is still 0, if I did win, if I bidd higher than vi, utility is still vi minus B, then why don't say bid higher than or equal than vi is the solution, TBRT

2022/10/14

1000<->2000

- non trivial
- slip of paper
- 1 your name; 2 your birthday; 3 evaluation mm+dd times .1 means maximum 4.3; 4 evaluation - bid is the payoff; 5 first price auction
- the next topic is second price vickery auction

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

## REX 2 2022/11/06
## REX 1 2022/09/10
## JMP 2 2022/09/02

2022/11/06

6500<->End

- the lowest bid that makes you the highest AKA second highest bid
- trughful bid, over bid, under bid
- also think about monotune
- if lower bid, there is risk that not bid you wanted thing, thus lead you to under bid in the showed in the class

2022/11/05

5000<->6500

- 5500 mins, if x is not monotune, then x is not implementable
- no jump point proof, sitting on different lines
- jump in p at the = z times jump p in x at t
- 10130 mins, doesn't follow
- next step is verification

2022/11/04

3500<->5000

- evaluation is the only unknown
- single item auction, n bidders, n+1 way of allocation
- if the prize has k coppies
- the amount you bid and the payment you need to do is not neccessarily the same
- monotune
- the inequalities make overbidding and underbidding both can give a value that is less then truely bidding
- z is bidding 4200 mins in this thought experiment

2022/11/02

2500<->3500

- if implementable then exist a payment DSIC
- if bid is 0, payment is 0
- myerson's lemma 3 points
- randomize auction, determinstic auction

2022/11/01

2500<->10300

- sponsor search auction is monotune
- allocation rule to be implementable, allocation rule to be monotune
- first tool in mechanism design
- part 1 an allocation rule x is implementable<->whether or not it is monotune
- part 2 in this case, exist unique payment st (x,p) is DSIC
- (bi)=0 lead to pib=0
- part 3 p is given by an explicit formula
- there is an awesome auction for sponsored search
- 4056 mins
- xi(z,b-1),pi(z,b-1)
- x(z) the amount you get
- 4500 mins suppose 0<=z<=y, truth bid z and false bid y
- sandwich
- 2 assumption can be thought of 2 player, under DSIC, it can derive a sandwich
- piecewise constant
- take the limit and let y to approach z
- 2 cases, jump case and no jump case
- 10226 formula is derived
- to do, verify it can work

2022/10/31

1000<->2500

- defn 1800 mins
- an allocation rule x is implementable if exist a payment P such that (x,p) is DSIC
- defn 2 2150 mins
- an allocation rule is monotune, if every i, every b-i, the amount of stuff I get holding everyone fix is non decreasing in its bid z, the higher you bid, the more stuff you get
- if winner is the second highest, it is not monotune

2022/10/30

0000<->1000

- one slot per bidder, one bidder per slot


2022/10/29

0000<->1500

- vickery auction satisfies 3 properties which are orthognal to each other
- second price auction solve the problem as if designer know the individual's evaluation
- greedy algorithm
- simgle parameter auction
- only unknown vi value per unit of good
- xi amount of stuff everybody gets
- allocation rule + payment rule
- x(b), P(b)
- 1300 mins, all the notations
- Pi(b) belongs to [0, bi * Xi(b)], upper bound is to ensure non negative utility for truthful bidders

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
