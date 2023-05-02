Download Link: https://assignmentchef.com/product/solved-cmsc401-assignment-3-dijkstra-algorithm
<br>
<h1>Best Road Trip</h1>

<ul>

 <li>You are planning to drive from Richmond to L.A.</li>

 <li>You want to spend as little as possible on the gas and motels.</li>

 <li>So you need to pick the best route – with cheapest motels and smallest cost of gas</li>

 <li>You have done your research and you know:

  <ul>

   <li>cost of an overnight stay in the cheapest motel in each of the cities on the possible routes</li>

   <li>cost of driving between cities without overnight stays</li>

  </ul></li>

 <li>Now you need to write a program that will take all that data, and find the cheapest route

  <ul>

   <li>The route with lowest sum of motel and gas costs</li>

  </ul></li>

</ul>

<h1>Assignment 3</h1>

<ul>

 <li>Write a program cmsc401.java that reads the database of</li>

</ul>




<table width="931">

 <tbody>

  <tr>

   <td width="818">–      The number of cities, N, in the first line. N&gt;=3, N&lt;=1000–      The total number of direct highways between cities, M, in the second line. M&gt;=2, M&lt;=10000–      Lowest motel price for each of N-2 cities (excluding L.A. and Richmond), each as a single line of two numbers: city number(3…N), motel cost (1…200)–      Gas prices for traveling direct highways between two cities, each as a single line of three numbers: city number (1…N), city number (1…N), cost of gas for travel between the two cities(1…200)–      Richmond is city number 1, L.A. is city number 2–      Cost shouldn’t include a motel in Richmond, not in L.A.</td>

   <td width="113"><strong>5</strong><strong>7</strong><strong>3    </strong><strong>78</strong><strong>4    </strong><strong>87</strong><strong>5    </strong><strong>98</strong><strong>1 4 98</strong><strong>5 4 45</strong><strong>1 5 140</strong><strong>4 3 87</strong><strong>2    </strong><strong>5 150</strong><strong>3    </strong><strong>5 109</strong><strong>3 2 73</strong></td>

  </tr>

 </tbody>

</table>

gas &amp; motel costs, which is in the format below:

<h1>Example</h1>

Input in correct format             Correct output

388

5

7

<ul>

 <li>78</li>

 <li>87</li>

 <li>98</li>

</ul>

1 4 98

5 4 45

1 5 140

4 3 87

<ul>

 <li>5 150</li>

 <li>5 109 Green shows the cheapest route from city 1</li>

</ul>

3 2 73          (Richmond) to city 2 (L.A). Cost is $388:

$140+$150 for gas + $98 for motel

<h1>Remarks</h1>

<ul>

 <li>There will always be at least one way of getting from city 1 to city 2</li>

 <li>If a cost for gas from city A to B is in the input, cost for gas from B to A is the same and will not be in the input</li>

 <li>No other text, comments, questions on output</li>

</ul>

<h1>Constraints</h1>

<ul>

 <li>Any Java libraries, classes, functions related to graphs, vertices, edges are NOT allowed</li>

</ul>

– Create your own…

<ul>

 <li>Using Java queue or priority queue (and other simple data structures such as lists, hash maps) is allowed</li>

</ul>