# Week1

## 1-2

2022/12/16

- procee mining book

## 2-1

2022/12/17

- play out, play in
- replay
- chapter 1(he said)/2(marked in the slides) in the book

## 2-2

2022/12/18

- Moores law
- volume, velocity, variety
- veracity
- what happened, why did it happen, what will happen, what is the best that can happen
- what time would you choose
- 1425 mins, process matters

2022/12/17

0000<->0500

- 10 minutes, from prehistoric to 2003
- internet of content, internet of people, internet of things, internet of places

## 2-4

2022/12/19

- process model analysis, data oriented analysis
- glue between business and IT
- same statistics but different distribution
- Tsinghua university
- people don't follow process model
- event data is not alligned with process model
- nominal, true and false don't have order
- data mining are not process centric
- end to end process models concurrency are essential for process mining

## 3-1

2022/12/20

- predictor variable, response variable
- workflow systems
- operations research
- cum laude
- entropy
- inverse of compressibility
- intermezzo
- calculate the split point enumerate so that the entropy the smallest one
- weight entropy
- information gain
- information loss
- post prunning
- chapter 3

## 3-2

2022/12/21

- root node, information gain
- before split and after split, compare the entropy
- precision and recall
- change minimal information gain to capture more outcome, but might result in overfitting
- underfitting

## 3-3

2022/12/21

- unsupervised learning
- association rule
- X implies Y
- support
- lift NX&Y/N DEVIDE NX/N TIMES NY/N
- confidence, XUY/X
- support XUY/N
- lift and correlation
- apriori
- min support, min confidence
- brute force approach
- |Z|>=2 means it has at least 2 elements
- computational problem, interpretation problem
- sequence mining, episode mining

## 4-1 reading materials

2022/12/23

- finish reading

## 4-2

2022/12/23

- instance have different attributes
- centroid
- repeatedly calculate the centroids
- iterate further no changes anymore
- random initial centroid
- K means + decision tree or association rule
- hierarchical clustering
- TBRT

## 4-3

2022/12/29

- confusion matrix
- cum laude
- TP TN FP FN
- cross validation
- concept drift

# Week2

## 1-1 Reading

2022/12/31

- ProM can convert Petri nets to other BPMN

## 1-2

2022/12/31

- play out, from model to event
- replay
- process discovery play in
- case, activity

## 2-1

2023/01/01

- 2 traffic lights
- 9 reachable markings, 6 reachable markings
- can't distinguish the right part
- non deterministic

2023/01/01

- rg, go
- reachable marking, unreachable marking
- enabling and firing
- number of token may change
- limiting factor
- atomic
- concurrently
- 8 reachable states
- interleaving semantics, there is a certain order
- 7^6
- both are enabled only one occur
- TBRT
- t3 can't be fired
- t2 at most once
- t1
- limit the reachable marking so that the remaining are safe
- make them alternate

## 2-2

2023/01/03

- reachability graph does not need to be finite
- play in
- play out
- replay can detect problem

2023/01/02

0000<->0747

- alternating
- deteministic
- transition system
- reachability graph
- multiple arc
