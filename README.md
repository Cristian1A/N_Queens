<h1 align="center">N Queens</h1>
<ul>
<li>N-Queens problem is a way of rethinking the <a href=href="https://en.wikipedia.org/wiki/Eight_queens_puzzle">eight queens puzzle</a> proposed by the chessman Max Bezzel in 1848 which consits on putting n queens in an n x n chess board squares in such a way that none of the queens could threaten any other.</li>
<br>
<li>Since brute force solutions can make the process of finding solutions quite computationally expensive, this project will focus on solving the problem from a <a href="https://en.wikipedia.org/wiki/Genetic_algorithm">genetic algorithm</a> approach.</li>
<br>
<li>
The implementation will be following the next steps:
<ol>
<li>A first generation of individuals will be inicializated with random values for each queen position on the board.</li>
<li>On each current generation individual will be calculated a fitness function, based in the number of threats, to be minimized in order to find the optimal solution.</li>
<li>A number of individuals will be selected from the current generation to be crossbreeded.</li>
<li>Over time, a mutation will be applied to each new individual generated.</li>
<li>New individuals will compose a new generation which will replace the old one.</li>
<li>Steps 2 through 6 will be repeated until a zero fitness individual is born.</li>
</ol>
</li>
</ul>
