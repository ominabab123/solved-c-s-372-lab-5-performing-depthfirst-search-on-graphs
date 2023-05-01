Download Link: https://assignmentchef.com/product/solved-c-s-372-lab-5-performing-depthfirst-search-on-graphs
<br>






In this lab, you will design and implement depth­first search (DFS) algorithms using recursive and iterative strategies.

<h1>1        Requirement for the DFS algorithm</h1>

We will design linear­time DFS algorithms with the following input and output:

<strong>Input: </strong>graph <em>G </em>with the Graph class defined in Lab 4.

<strong>Output: </strong>All nodes in graph <em>G</em>

<ul>

 <li>are marked as visited</li>

 <li>have a pre clock value</li>

 <li>have a post clock value</li>

</ul>

Please update the Graph and Node classes to include the above information. There are multiple ways of enhancing the data structures from the previous lab. You are free to design your strategy. They cannot be saved as global variables.

<h1>2        Recursive solution</h1>

Implement the recursive solution we discussed in class using the following C++ function prototype:

void        DFS_recursive ( Graph &amp; G)

{

/ /    Your      recursive     code   f o r  DFS

}

<h1>3        Iterative solution</h1>

Implement the iterative solution using the strategy similar to the iterative solution of the breadth­first­search (BFS). Instead of using a queue, you can use a stack to save the discovered but not yet processed nodes. Use the following C++ function prototype:

void          DFS_iterative ( Graph &amp; G)

{

/ /    Your  i t e r a t i v e  code   f o r  DFS

}

You are encouraged to use the std::stack class from C++.

<h1>4        Test the classes</h1>

Generate five example graphs to test your code. The graphs do not have to be very large but must represent the following variety: cyclic/acyclic, directed/undirected, having one or more connected components.

Your C++ program must include a main() function that calls the testall() function. When the program is compiled by a C++ compiler, it generates a binary executable file that will run when invoked from the command line.

<h1>5        Plot the runtime as a function of number of nodes and edges</h1>

After testing the correctness of the the program, you will study how the runtime scale with the size of graph for the two methods. Use the random graph function you developed in Lab 4 to generate random graphs of increasing sizes reaching 10,000 nodes and 1,000,000 edges or more.

You will produce four plots in R:

<ol>

 <li>DFS­recursive runtime as a function of number of nodes</li>

 <li>DFS­iterative runtime as a function of number of nodes</li>

 <li>DFS­recursive runtime as a function of number of edges</li>

 <li>DFS­iterative runtime as a function of number of edges</li>

</ol>


