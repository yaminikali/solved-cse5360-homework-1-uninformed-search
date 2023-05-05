Download Link: https://assignmentchef.com/product/solved-cse5360-homework-1-uninformed-search
<br>
<h1>Uninformed Search</h1>

<ol>

 <li>For the following tree, show the lists of <em>open </em>and <em>visited </em>nodes (i.e. nodes to which the goal test and the successor function have been applied) for each cycle of the listed search algorithms. The goal nodes are <em>X </em>and <em>Z</em>, and the numbers next to the edges indicate the associated cost.</li>

 <li>Breadth-first search</li>

 <li>Depth-first search</li>

 <li>Uniform cost search ( ties should be broken alphabetically )</li>

</ol>

For each node in the <em>open </em>and <em>visited </em>lists also indicate the associated cost.

<h1>Informed Search</h1>

<ol start="2">

 <li>Consider the following problem: You are working in a shop and have to put 1<em>kg </em>of rice into a container (initially empty) from a rice store (with unlimited amounts of rice). To weigh the rice you have a scale that can only measure two weights, namely 3<em>kg </em>and 5<em>kg </em>and you can move rice between the rice store, the scale, and the container (both the rice store and the container can hold an unlimited amount of rice). To know how much rice you have in the container, you can therefore move the rice only in quantities of 3<em>kg </em>or 5<em>kg</em>. Assume that we want to move as little rice as possible and thus the cost of every move is proportional to the amount of rice that is moved.</li>

 <li>Formulate the problem as an informed search problem by designing a state space, a successorfunction, a goal test, and an admissible heuristic for this problem.</li>

 <li>Show the operation of Greedy Best-first search on this problem by listing the open list and thevisited list (including the cost value used) for each iteration of the search.</li>

</ol>

2020 Manfred Huber        Page 1 CSE 5360 – <em>Artificial Intelligence I </em>Homework 1: Problem Solving Using Search

<ol>

 <li>Show the operation of <em>A</em><sup>∗ </sup>search on this problem by listing the open list and the visited list (including the cost value used) for each iteration of the search.</li>

 <li>Show the operation of <em>IDA</em><sup>∗ </sup>search on this problem by listing the open list and the visited list (including the cost value used) for each iteration of the search.</li>

</ol>

<h1>Problem Solving Using Search</h1>

<ol start="3">

 <li>Consider an extension of the problem in part 2 where the scale can measure 3 different weight, <em>i</em>, of size <em>c<sub>i</sub></em>, and you should fill rice into two containers, <em>j</em>, where the amount of rice put in each container is <em>x<sub>j</sub>kg</em>. Again you can move rice between the rice store, the scale, and the containers. As previously, the cost of each move is equal to the amount of rice that is moved and rice can only be weighted on the scale.</li>

</ol>

Write a program which solves this problem using <em>A</em><sup>∗ </sup>search (make sure that the values for the weights that the scale can measure and the goal amount for each container are easy to change in the code). You have to implement your own <em>A</em><sup>∗ </sup>search and can thus not use any prior implementations of search functions. Your search should return the correct sequence of rice moves, including the total cost. In addition, it should output the sequence in which nodes were added to the open list and how they were visited.