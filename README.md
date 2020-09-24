# UMSL-1320-Introduction-to-Probability-and-Statistics

Math 1320 Project Fall 2016
Objectives:

1. To practice statistical analysis on real data
2. To practice using R/R-studio
3. To practice interpreting R output and drawing conclusions
4. To practice writing report

Description: This project provides three dataset for you to analyze. Please first read the background
information of the datasets and find out the questions that researchers wanted to answer in these three
cases. Then carry out a thorough statistical analysis on these datasets and write a report to answer these
questions.
The report is expected to have the following components:

```
Three chapters one for each case, and each chapter contains the following:
```
```
Exploratory data analysis
```
```
Clear statement of statistical questions you are going to answer
```
```
The reason for choosing this statistical method for answering the question
```
```
Complete R codes for the analysis work
```
```
Interpreting R output
```
```
Summary of statistical findings
```
```
Scope of Inference
```
Case I: Bumpus’s Data on Natural Selection - An Observational Study

In an 1898 biology lecture at Woods Hole, Massachusetts, Hermon Bumpus reminded his audience that
the process of natural selection for evolutionary change was an unproved theory: ”Even if the theory of
natural selection were as firmly established as Newton’s theory of attraction of gravity, scientific method
would still required frequent examination of its claims.” As evidence in support of natural selection, he pre-
sented measurements on house sparrows brought to the Anatomical Laboratory of Brown University after an
uncommonly severe winter storm. Some of these birds had survived and some had perished. Bumpus asked
whether those that perished did so because they lacked physical characteristics enabling them to withstand
the intensity of that particular instance of selective elimination.

Table 1^1 exhibits the humerus (arm bone) lengths for the 24 adult male sparrows that perished and for
the 35 adult males that survived. Do humerus lengths tend to be different for survivors than for those that
perished? If so, how large is the difference?

Case II: Space Shuttle O-Ring Failures - An Observational Study

On January 27, 1986, the night before the space shuttle Challenger exploded, engineers at the company
that built the shuttle warned National Aeronautics and Space Administration (NASA) scientists that the
shuttle should not be launched because of predicted cold weather. Fuel seal problems, which had been

(^1) google: stem-leaf plot for more reference.


```
Perished Surivived
9 65
66
67
9 68 7
69
932 70 39
3 71 5
96600 72 13368889
988761 73 0033569
543 74 111139
422 75 12256
5 76 679
77 0
78 0
Lenengd: 68 7 represents 0.687 inch
```
Table 1: Humerus Lengths (inches) of adult male house sparrows, 24 that perished and 35 that survived in
a winter storm

encountered in earlier flights, were suspected of being associated with low temperatures. It was argued, how-
ever, that the evidence was inconclusive. The decision was made to launch, even though the temperature at
launch time was 29°F.

The data in Table 2 are the numbers of O-ring incidents on previous shuttle flights, categorized into those
launched at temperatures below 65°F and those launched at temperatures above 65°F. (Data from a graph
in Richard P.FeynmanWhat Do You Care What Other People Think? (New York: W. W. Norton,1988).)
Is there a higher risk of O-ring incidents at lower launch temperatures?

```
Launch Temperature Number of O-Ring Incidents
Below 65°F 1, 1, 1, 3
Above 65°F 0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,0,1,1,
```
```
Table 2: Numbers of O-ring incidents on 24 space shuttle flights prior to the Challenger disaster
```
Case III: The Big Bang - An Observational Study

Edwin Hubble used the power of the Mount Wilson Observatory telescopes to measure features of nebulae
outside the Milky Way. He was surprised to find a relationship between a nebula’s distance from earth and
the velocity with which it was going away from the earth. Hubble’s initial data on 24 nebulae are shown as
ascatterplotin Figure 1. (Data from Hubble, ”A Relation Between Distance and Radial Velocity Among
Extra-galactic Nebular,”Proceedings of the National Academy of Science15 (1929): 168-73.) The horizon-
tal axis measures the recession velocity, in kilometers per second, which was determined with considerable
accuracy by the red shift in the spectrum of light from a nebula. The vertical scale measures distance from
the earth, in megaparsecs: 1 megaparsec is 1 million parsecs, and 1 parsec is about 30.9 trillion kilometers.
Distances were measured by comparing mean luminosities of the nebulae to those of certain star types, a
method that is not particularly accurate. The data are shown later in this chapter as Table 3.


```
Figure 1: Scatterplot of measured distance versus velocity for 24 extra-galactic nebulae
```
The apparent statistical relationship between distance and velocity led scientists to consider how much
a relationship could arise. It was proposed that the universe came into being with a Big Bang, a long time
ago. The material in the universe traveled out from the point of the Big Bang, and scattered around the
surface of an expanding sphere. If the material were traveling at a constant velocity (Vfrom the point of
the bang, then the earth and any nebulae would appear as in Figure 2.

```
Figure 2: Big Bang theory model for distance-velocity relationship of nebulae
```
The distance (Y) between them and the velocity (X) at which they appear to be going away from each
other satisfy the relationship

```
(Y/2) / VT = (X/2) / V = sin(A),
```

WhereAis half the angle between them. In that case,

```
Y=TX
```
is a straight line relationship between distance and velocity. The points in Figure 1. do not fall exactly on a
straight line. It might be, however, that themeanof the distance measurements isTX. The slope parameter
Tin the equation Mean{Y}=TXis the time elapsed since the Big Bang (that is, the age of the universe).
Several questions arise. Is the relationship between distance and velocity indeed a straight line? Is the
y-intercept in the straight line equation zero, as the Big Bang theory predicts? How old is the universe?

```
i Nebula VelocityXi DistanceYi
1 S. Mag. 170 0.
2 L. Mag. 290 0.
3 NGC 6822 -130 0.
4 NGC 598 -70 0.
5 NGC 221 -185 0.
6 NGC 224 -220 0.
7 NGC 5457 200 0.
8 NGC 4736 290 0.
9 NGC 5194 270 0.
10 NGC 4449 200 0.
11 NGC 4214 300 0.
12 NGC 3031 -30 0.
13 NGC 3627 650 0.
14 NGC 4626 150 0.
15 NGC 5236 500 0.
16 NGC 1068 920 1.
17 NGC 5055 450 1.
18 NGC 7331 500 1.
19 NGC 4258 500 1.
20 NGC 4151 960 1.
21 NGC 4382 500 2.
22 NGC 4472 850 2.
23 NGC 4486 800 2.
24 NGC 4649 1090 2.
```
```
Table 3: Big Bang Study Data
```

