
2026/01/14

09:06

t5, esm2, esm2 3b, pb, ankh, taxa, text emb

10:05

Both are types of Primary Memory (also called Main Memory).

They just serve different roles:

    RAM (Random Access Memory): This is Read/Write memory. It is your "workspace." You can write new data to it and read from it constantly, but it forgets everything when the power goes out (Volatile).
    ROM (Read-Only Memory): This is Read-Only memory. It is your "reference library." It holds critical instructions that shouldn't change, and it remembers them even without power (Non-Volatile).

1303

2026/01/13

09:09

Use models trained with last year data, to predict new year result, ablation test?

09:39 mins

2026/01/12

08:43

Test why the number of rows is 80K around only

08:53

it was because of taxnomy was still from cafa6
checking if it is possible to derive matrix and frequence weight from give file

09:03

running training steps

09:13

study file differences

09:23

to test if use the same IA would bring the same YP label and YP files
understand and got a proof of data comp of this comp

09:33

cyber music 59 mins around

09:43

No, if the content of your submission file is the same, then the order of the rows will not affect the predictions or the results in Kaggle competitions.
Kaggle's evaluation process typically involves comparing the predicted values in your submission file against the true values from the test set (for example, using metrics like accuracy, RMSE, etc.). As long as the predicted values for each test instance are correctly aligned with their respective IDs (or indices), the order of the rows in the file doesn't matter.
However, there are some important considerations:


Correct Format: Ensure that the structure of the file matches the format expected by the competition (e.g., columns in the right order, headers present if required).


ID Matching: If the IDs (or indexes) are out of order or mismatched with the corresponding predicted values, it would lead to incorrect predictions, even though the predicted values themselves are correct.


File Integrity: Make sure the file is properly formatted (e.g., CSV, TSV), with no extra rows, blank spaces, or corrupted content.


In short, it's the content (the correct predictions corresponding to the correct IDs) that matters, not the order of the rows.

2026/01/11

10:52

to prepare the matrix and the freq weight

11:02



2026/01/10

09:10

Use GPU run the 3850 to 7000
Attempt to use model trained with last year applying to the new year

09:20

GPU run into error as not call GPU at every step

09:30

Moved to GPU but seems at a wrong place

09:40

Test inference model, with existing setup then try to use the embedding others created


09:50

code running successfully
need to understand the 3 categories,e.g. BPO, where is data is from test-ii ipynb

10:15


2026/01/09 Total 59 mins exploration




13:39

Downloaded the fourth solution and try to enable it

13:49

no progress

13:59

running ankh embedding now

14:09

anhk embedding is running, length is also identified

14:19

train and infer seems can work with anhk embedding only, though there was also other embedding being used
preprocess data, not sure where it was from or can it be resuable for this competition
waiting for the result from the embedding

14:38

2026/01/07

09:12

Checked second solution in last year

09:22

no output, be distracted

09:32

3rd solution, with graph, you can mimic it

09:42



09:52

10:02

I don't know it was because of a sip of coffee or what, but I was close to cry while I was reading the 4th tolution writeup, maybe because its sincere and honest
Music was 'Before the dawn'
https://www.youtube.com/watch?v=ApG2Svgk7Pc&t=5670s

10:12

2026/01/01

08:02

check if the naive embedding technically possible
realized to also check the stats for null value

08:12

still working on the same thing, got an understanding of a characteristic of the group

08:22



08:32

understand RAM size

08:42

adjust the parameter to best fit RAM

08:52


2025/12/31

12:57

understand the admin procedure of the competition

13:07

understood how the admin procedure would be managed

13:17

embed cafa6 test superset data

13:27

understand more about cafa6 competition, record are all in medici copilot

13:37

try the embedding approach for fun

13:42

25 mins out of time due to computationally heavy, and distraction from environment, searching for a headset

14:07

20251231

モノクローム this is the music flying in my mind, I didn't know the name of the music, I opened my playlist, randomly clicked one music from my playlist, to my surprise, the one was the one

KG exploration

2025/12/27

Vectorization can let your code run on parrallel compute hardware

2025/12/27

09:24

tilted to the left or tilted to the right
given state, pick action to maximize the return, with discount fator


09:34

deep reinforcement learning
s,a based Q formula, to tell it what action and state combination rewards

09:44

deep Q network
DQN
take a long time to converge


09:54

picking action randomly, aka, exploration
greedy action
exploitation
epsilon greedy policy

2025/12/26

12:45
do exam
12:55
Did another exam
13:05
Optional lab to udnerstand state value function
continuous reinforcement learning
13:15


2025/12/22

0930

Blast

1000

identify blending, understand the target again


KG exploration

2025/12/17

4509

loaded the code, asked the question to copilot

5509



0510

---


KG exploration

2510

review last time achieved, but somehow copilot disapeared from the browser

3510



5510

===>

5510<->1211 17 M exceeding
Gained full script understanding, capable of replicate last year ideas into this year
