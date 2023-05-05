Download Link: https://assignmentchef.com/product/solved-datastructure-assignment-2
<br>






Chapter 2

6 pts

<ol>

 <li>In the definition of Big-O, why is the “for N &gt;= n0” needed?</li>

</ol>

6 pts

<ol start="2">

 <li>If f1(N) = 2N and f2(N) = 3N, why are they both O(N), since 3N is larger than 2N for N&gt;=1?</li>

</ol>

6 pts

<ol start="3">

 <li>a) For f1(N) = 2N and f2(N) = 3N:</li>

</ol>

calculate f1(5) and f2(5), then f1(10) and f2(10).  When N was doubled in each case, what happened to the result?  Explain why this happens.

<ol>

 <li>b) For f1(N) = 2N*N and f2(N) = 3N*N:  calculate f1(5) and f2(5), then f1(10) and f2(10).  When N was doubled in each case, what happened to the result?  Explain why this happens.</li>

</ol>




6 pts

<ol start="4">

 <li>Since Big-O notation is a mathematical tool for functions like f(N) or g(N), how is it applicable to algorithm analysis?</li>

</ol>

6 pts

<ol start="5">

 <li>Which grows faster, 2^n or n! ? Explain why.</li>

</ol>

10 pts (2 each)

<ol start="6">

 <li>Give the Big-O notation for the following expressions:

  <ol>

   <li>4n^5 + 3n^2 – 2</li>

   <li>5^n – n^2 + 19</li>

   <li>(3/5)*n</li>

   <li>3n * log(n) + 11</li>

   <li>[n(n+1)/2 + n] / 2</li>

  </ol></li>

</ol>

Questions 7-12 are 10 points each.

Assume numItems has the role of N, which may vary from one run to the next.

<ol start="7">

 <li>What is the Big-O running time for this code? Explain your answer.</li>

</ol>

for (int i=0; i&lt;numItems; i++)

System.out.println(i+1);

<ol start="8">

 <li>What is the Big-O running time for this code? Explain your answer.</li>

</ol>

for (int i=0; i&lt;numItems; i++)        for (int j=0; j&lt;numItems; j++)

System.out.println( (i+1) * (j+1) );

<ol start="9">

 <li>What is the Big-O running time for this code? Explain your answer.</li>

</ol>

for (int i=0; i&lt;numItems+1; i++)        for (int j=0; j&lt;2*numItems; j++)           System.out.println( (i+1) * (j+1) );

<ol start="10">

 <li>What is the Big-O running time for this code? Explain your answer.</li>

</ol>

if ( num &lt; numItems )        for (int i=0; i&lt;numItems; i++)

{

System.out.println(i);

}     else

System.out.println(“too many”);

<ol start="11">

 <li>What is the Big-O running time for this code? Explain your answer.</li>

</ol>

int i = numItems;      while (i &gt; 0)

i = i / 2;     // integer division will eventually reach zero

<ol start="12">

 <li>What is the Big-O running time for this code? Explain your answer.     (You do not need to work out a recurrence formula).</li>

</ol>

public static int div(int numItems)

{

if (numItems == 0)            return 0;         else

return numItems%2 + div(numItems/2);      }

Submit these files:     hw2.doc  (.doc can be .txt, .jpg, etc.)