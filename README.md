# COMP2140-Lab-4-Simulating-a-Simple-Survivor-Game-with-a-Queue

Download Here: [COMP2140 Lab 4: Simulating a Simple Survivor Game with a Queue](https://codingherolab.com/product/comp2140-lab-4-simulating-a-simple-survivor-game-with-a-queue/)

For Custom/Original Work email codingprolab@gmail.com/whatsapp +1(541)423-7793

Objective
To simulate a simple survivor game with a queue.
Exercise
File Lab4.java contains an almost-complete application with a simple Queue. You need to add most of the
body of the method survivor, which currently only prints some information.
The survivor method should simulate (using a queue) the survivor game. In this game, N people
(numbered 0 to N − 1) stand in circle, then every kth person is counted out (leaves the circle), until only
one person is left. At each elimination, you should print out the eliminated person’s number.
For example, if there are 7 people (N = 7) and k = 2, then you should print out 1 3 5 0 4 2 6 because
the circle changes as follows:
0
1
2
4 3
5
6
Start
0
1
2
4 3
5
6
First elimination: 1
0
2
4 3
5
6
Second elimination: 3
0
2
4
5
6
Third elimination: 5
0
2
4
6
Fourth elimination: 0
2
4
6
Fifth elimination: 4
2
6
Third elimination: 2
6
Last element remaining: 6
The code that you add to the survivor method must simulate the game using a queue to represent the
circle of people. To do the eliminating, you must use the standard queue methods (enter, leave, front,
and isEmpty) provided in the Queue class. You may not change the Queue class or the main method in any
way.
Hint: You can keep eliminating until no people are left in the circle.
Sample output:
7 people numbered 0 to 6 stand in a circle.
Every second person is eliminated repeatedly until only one person is left.
The people are eliminated in the following order:
1 3 5 0 4 2 6 <=== last person left
11 people numbered 0 to 10 stand in a circle.
Every third person is eliminated repeatedly until only one person is left.
The people are eliminated in the following order:
2 5 8 0 4 9 3 10 7 1 6 <=== last person left
17 people numbered 0 to 16 stand in a circle.
Every 5-th person is eliminated repeatedly until only one person is left.
The people are eliminated in the following order:
4 9 14 2 8 15 5 12 3 13 7 1 0 6 11 16 10 <=== last person left
Program ends normally.
