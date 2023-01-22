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

## 6-1 Optional

2023/01/12

0000<->0459

- fluxicon
- make process software for business uses
- 2012
- yyyy-M-d H:mm time format ProM
- https://blog.csdn.net/weixin_43719616/article/details/121977923


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


## 3-1

2023/01/06

1144<->End

- states,marking;transition,transition
- initial states, final states
- complete traces, go from initial state to final state
- incomplete trace
- finite transition system has infinitely traces
- from petri net to reachable graph to final states
- transition system use state which comprimise markings

2023/01/05

1144<->1330

- if a marking enables at least one transition, not dead marking
- live, after trigger something, only a partial is enabled to be transited
- bounded, if marking is limited with certain number of token
- safe, 1-bounded
- deadlock free, if marking enables no transition then it is dead, if there is reachable dead marking, then there is potential deadlock, [if all reachable marking enables at least one transition]
- live, after trigger something, only a partial is enabled to be transited then it is not live
- starting from a box, means the transition can always fire

2023/01/05

0729<->1144

- liveness
- a transition is live
- Petri net
- possible
- p4 is unbounded
- liveness is about transition

2023/01/05

0000<->0729

- k bounded
- unbounded point
- safeness, 1 boundedness
- deadlock
- marking is dead
- deadlock-free
- initial marking is deadlock, but bounded

## 3-2

1008<->End

2023/01/08

- option to complete implies proper completion
- short circuited petri net
- verification soundness checking
- performance analysis

0000<->1008

2023/01/07

- soundness
- WF nets
- workflow management, business process management
- BPM IT and management science
- 1732 the division of labor
- timeline
- re/design implement/configure run/adjust
- learning the process while they are running
- BPMN EPCs(SAP) Petri nets
- reachability graph, transition system
- dead lockd may indicate that a model is not a good model
- and split doesn't have corresponding join
- safe, bounded, deadlock-free, live
- anomoly
- WF-net, one source place, one sink place, from start to end
- safeness, proper completion, option to complete, absence of dead parts

## 4-1

2023/01/10

XXXX<->End

- alpha algorithm contains 8 lines
- after removing the elements, the property still holds
- transitions and places
- arcs F
- prepare the foot print matrix then apply the alpha algorithm

2023/01/09

0000<->1500

- from event log learn a process model
- loops, parallel, choice
- alpha algorithm
- order of activity within a particular case
- multiset of traces
- challenge for proces discovery
- direct succession	
- causility
- parallel
- choice
- sequence, XOR split
- followed
- model and event log agree on footprint matrix
- set??? 1000 mins

## 4-2

2023/01/13

1245<->End

- noise, incompleteness
- alpha algorithm can't generate a model with duplicate transition
- the top model describe the dominant behaviour
- idem, the same as the previous discussi n
- rediscovery criterion

2023/01/12

0641<->1245

- get some basic knowledge about how to use ProM

2023/01/12

0641<->1245

- some model can't be discovered by alpha algorithm
- silent transition
- region based model
- TBRT, how to use ProM


2023/01/11

0000<->0641

- limitations
- implicit places
- remove them doesn't affect the process model
- unable to deal with loops
- 0330 mins
- loops of length 2
- different event log discover the same model
- multiple transition with the same label is not allowed for a WF net

## 5-1

2023/01/14

0500<->End

- verification techniques, comformance checking
- pompom, remove activities that are in frequent
- inductive miner animation
- replay an reality
- fuzzy miner
- animate event log in fuzzy instance
- social network miner
- case id, event, timestamp + other attributes
- filter logic

2023/01/13

0000<->0500

- fuzzy model
- ProM package manager
- xes

# Week 3
## 1-1 

2023/01/16

0000<->End

- is the process model a correct reflection of the real process
- venn diagram to describe confusion matrix
- event log only shows fraction of possible traces
- replay fitness= TP'/TP'+FN'
- fitness simplicity precision generalization
- underfitting model
- occam's razor
- overfitting model
- do not fit
- in underfitting case, you should remove some possibilities
- 5 example is not enough to say the generalization is good
- representational bias

## 1-2

2023/01/18

0938<->End

- indirect dependency
- duplicate activities

2023/01/17

0000<->1000

- desire line
- metaphor
- the model doesn't allow the behaviour, but it happended anyway, is it outliner
- build an althernative model, is it overfitting
- modeling language 1, modeling language 2
- plethora of notations
- the choice of language will influence the outcome
- use transition system it is difficult to describe concurrency

## 1-3

2023/01/19

0000<->End

- UML activity diagram
- deferred choice
- or join
- EPCs event driven process chains
- OR paradox

## 1-4 Reading

2023/01/20

- middleware
- inflate
- spaghetti, lasagna

## 2-1

2023/01/20

0000<->0600

- dependency graphs and causal nets
- nodes activities, arcs causal dependencies
- arcs be annotated with frequencies or confenditialities
- causal footprint
- from footprint to a dependency graph
- remove the places and get a dependency graph
- fuzzy model, dependency graph
- heuristics
