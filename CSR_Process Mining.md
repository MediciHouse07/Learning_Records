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

2023/03/30

0000<->0400

- TBR reachability graph


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

## 4-2 Week 2

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

2023/03/20

0400<->End

- no false positive, precision is 1; no false negative, recall is 1
- challenges for applying recall and precision in measuing the model
- 4 forces
- different example of evaluating the quality of a model
- underfitting model, too general
- precision and read the precision from the petri net
- no unobserved event will happen in the results model predicted, that is good precision
- generalization can be analogied by recall
- modeling language provides a bias
- the challenge comes from you only know what has happened, and the result model predicted
- replay_fitness=TP'/TP'+FN', comformance checking, if recall is 1 then replay_fitness is 1, model captured everything in the event log

2023/03/16

0000<->0400

- different angle in measuring the quality of a process model
- venn diagram
- recall TP/TP+FN
- precision TP/TP+FP

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

2023/03/30

- TBR transition system vs petri net
- Workflow nets, BPMN
- choose(m,n), factorial(n)
- discover process is guided by bias
- WF-nets with unique labels
- TBR WF-nets
- no indirect dependencies

2023/03/22

0800<->0900

- optional, how to read it, something can be skipped
- silent, duplicate steps, need to go back to review the previous chapters

2023/03/21

0000<->0800

- metaphor
- desire line
- representational bias
- suppose modeling language is not circle
- it impact the search space
- transition system difficult to capture concurrency
- worklow nets, transition system, BPMN, petri nets
- a notation that allows concurrency

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

2023/01/21

0000<->End

- dependency graphs, causal structure of the model
- fuzzy models can be viewed as dependency graph
- causal nets
- remove obligation, create obligation
- silent transitions
- relating C nets to WF nets
- valid binding sequences
- output binding input binding
- declarative
- by the nature of the net


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

## 2-2

2023/01/23

0600<->End

- sequence pattern
- Xor pattern
- dependency matrix

2023/01/22

0000<->1500

- counting direct succession
- dependency measure
- times(dependency measure)
- threshold for including or not including a causality
- loop pattern

## 2-3

2023/01/25

0000<->End

- input binding is just a set
- refinement
- 1500 approach 2, finite number
- heuristic miner proM
- TBRT?

2023/01/24

0000<->1100

- C net
- from dependency graph to C net
- that one can consider
- TBRT
- takes windows before A and also to the output side
- input binding, b,c 5 times, it is not about types of input binding

## 3-1

2023/01/27

0000<->End

- state, past future and past future
- last event, next event
- past horizon 2 sequence abstraction, set abstraction
- preprocessing, postprocessing
- improve diamond structure
- discover concurrency
- generalize the behivour
- state based regions

0000<->0940

2023/01/26

- state based regions
- from event log to transition system
- multiset abstraction
- TBRT
- alpha algorithm has a lot of limits, so this week is about what other advanced algorithm that can be used that don't have those limits

## 3-2

2023/04/05

0000<->0500

- transition system, convert it to petri net
- then concurrency is discovered
- state based region
- one initial state, one final state can be constructed artificially
- combination of region is a region

# 3.3

2023/12/08

- OMG standard
- UML EPCs
- soundness
- many potential deadlocks
- and split and join
- or split or join
- potential deadlocks
- acbe abce are all valid traces
- vicious cycle paradox

# 3.4

2023/12/09

- footprint
- possible binding
- only describe possible path
- c net can be transformed to petri net
- declarative semantic
