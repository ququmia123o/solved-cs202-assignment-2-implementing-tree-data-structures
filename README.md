Download Link: https://assignmentchef.com/product/solved-cs202-assignment-2-implementing-tree-data-structures
<br>
<h1>Implement the following tree data structures using C++ programming language.</h1>

<ol>

 <li>Binary Tree (Marks-5)</li>

 <li>BST (BSTree.hpp) by inheriting the functions and node structure (BinaryNode class) of binary tree (BinaryTree.hpp). (Marks-10)</li>

 <li>Implement AVL tree (AVL.hpp) by inheriting the BST (BSTree.hpp). (Marks-15)</li>

 <li>Implement the RB tree (RBTree.hpp) by inheriting BST (BSTree.hpp) also inherit BinaryNode class by creating RBTNode class. (Marks-20)</li>

</ol>

<em>Above marks will be provided only if below mentioned files are present.</em>

Write a separate main programs to evaluate the functions in data structures binary tree, binary search tree (BST), balanced search trees such as AVL tree and red-black (RB) tree. The main functions should have the options to read inputs from user and display.

For the evaluation of the above trees below mentioned main.cpp is also necessary (otherwise your code won’t be evaluated). A main file which takes an input <em>Q</em>(1 <em>&lt;</em>= <em>Q &lt;</em>= 100000), number of queries. Next <em>Q </em>lines contain queries of the given form.

<ul>

 <li>1 <em>x </em>(insert x into the tree)</li>

 <li>2 <em>x </em>(delete one occurence of x from tree if present)</li>

 <li>3 <em>x </em>(find x in tree. Print 1<em>/</em>0)</li>

 <li>4 (print value of maximum element in the tree)</li>

 <li>5 (print value of minimum element in the tree)</li>

</ul>

Note:

<ol>

 <li>x can be of any type – int, long long, double, string etc.</li>

 <li>Compile the main.cpp to create an executable file (named <em>trees</em>) which runs in the below format.</li>

</ol>

./trees tree-name data-type

We will run the code in given format

./trees bst string <em>&lt; </em>in.txt <em>&gt; </em>out.txt

./trees avl int <em>&lt; </em>in.txt <em>&gt; </em>out.txt ./trees rbt double <em>&lt; </em>in.txt <em>&gt; </em>out.txt <em>out.txt </em>will be matched against actual results file.

<ol start="3">

 <li>Do not change the class names. It is expected to strictly use the interfaces provided in the classes to implement the tasks. (Marks-10)</li>

</ol>

<h1>2           Problems</h1>

<ol>

 <li>World is full of Trolls and Troll Hunters. There are n hunters numbered from 1 to n, each has a Strength coefficient associated with them. If a hunter i with strength coefficient A[i] is surrounded by Trolls, then a hunter j with strength coefficient A[j] such that A[j]<em>&gt;</em>A[i] can protect him. The time taken by Hunter i to reach Hunter j is given by formula |i-j|. For every Troll Hunter, You have to calculate the minimum time after which the given troll hunter, could be saved from troll.</li>

</ol>

Consider at a time only one troll hunter can be attacked. Attack on a Hunter is independent of each other. (Marks-20)

Input

Integer n (1 <em>&lt;</em>= <em>n &lt;</em>= 100000) – number of Troll Hunters. Next line contains <em>n </em>space separated values <em>i<sup>th </sup></em>of them denoting the strength coefficient of hunter positioned at <em>i<sup>th </sup></em>index. (1 <em>&lt;</em>= <em>A</em>[<em>i</em>] <em>&lt;</em>= 1<em>e</em>18) Output <em>n </em>space separated values <em>i<sup>th </sup></em>one corresponding to the minimum time required so that <em>i<sup>th</sup></em>

2

Hunter can be saved from Troll. If some Hunter can’t be saved print -1

<ol start="2">

 <li><em>Older the wine the better it tastes</em>. One day Barney decided to throw a grand party to all his friends. He had n friends standing in a straight line and he gave each of them a bottle of wine. Each wine bottle has the year of manufacturing written on it. Every friend can see the manufacturing year of his own bottle and all the bottles ahead of him ie to his right (but not left). Friends being of jealous type, each of them wanted to know how many of the friends standing ahead got a better tasting wine. (Marks-20)</li>

</ol>

Input

Integer n (1 <em>&lt;</em>= <em>n &lt;</em>= 100000) – number of friends Barney invites. Next line contains <em>n </em>space separated values <em>i<sup>th </sup></em>of them denoting the year of manufacturing of the <em>i<sup>th </sup></em>bottle.

(1 <em>&lt;</em>= <em>A</em>[<em>i</em>] <em>&lt;</em>= 1<em>e</em>18) Output

<em>n </em>space separated values <em>i<sup>th </sup></em>one corresponding to the number of tastier wines ahead of it.