Download Link: https://assignmentchef.com/product/solved-blg202e-homework-2
<br>
<strong>Questions:</strong>

<ol>

 <li>Consider the problem</li>

</ol>

<em>x</em><sub>1 </sub>− <em>x</em><sub>2 </sub>+3<em>x</em><sub>3 </sub>= 2 <em>x</em><sub>1 </sub>+ <em>x</em><sub>2 </sub>= 4 3<em>x</em><sub>1 </sub>−2<em>x</em><sub>2 </sub>+ <em>x</em><sub>3 </sub>= 1

Carry out Gaussian elimination in its simplest form for this problem. What is the resulting upper triangular matrix?

Proceed to find the solution by backward substitution.

<ol start="2">

 <li>Let</li>

</ol>

(a) The matrix A can be decomposed using partial pivoting as

<h1>PA = LU</h1>

where U is upper triangular, L is unit lower triangular, and P is a permutation matrix. Find the 4 x 4 matrices U, L, and P.

(b) Given the right-hand-side vector <strong>b=</strong>(26<em>,</em>9<em>,</em>1<em>,</em>−3)<em><sup>T</sup></em>, find x that satisfies Ax = b. (Show your method: do not just guess.)

<ol start="3">

 <li> Implement the Power Method in Python by writing a program that inputs a matrix <em>A </em>∈ <em>R<sup>nxn </sup></em>and an initial guess vector <em>v</em><sub>0 </sub>∈ <em>R<sup>n</sup></em>. Use your code to find an eigenvector of matrix given below, starting with the initial guess vectors <em>v</em><sub>0 </sub>= (1<em>,</em>2<em>,</em>−1)<em><sup>T </sup></em>and <em>v</em><sub>0 </sub>= (1<em>,</em>2<em>,</em>1)<em><sup>T</sup></em></li>

</ol>

Report the first 5 iterates for each of the two initial vectors. Then find eigenvalues and eigenvectors of A (you can use numpy.linalg.eig<a href="#_ftn1" name="_ftnref1"><sup>[1]</sup></a>). Where do the sequences converge to? Why do the limits not seem to be the same?

<strong>Note: </strong>You can use NumPy package in Python for the implementation.

<ol start="4">

 <li> In this question you will play with one picture (see Figure 1) that can be found in homework’s attachment in Ninova (clown.bmp).

  <ul>

   <li>Write a Python code for computing the truncated SVD of this image. Start with rank <em>r </em>= 2 and go up by powers of 2, to <em>r </em>= 64. For a compact presentation of your figures, use the matplotlib subplots<a href="#_ftn2" name="_ftnref2"><sup>[2]</sup></a> for each of the pictures, with 3(nrows) and 2(ncols) as the first two arguments.</li>

   <li>Comment on the performance of the truncated SVD for each of the pictures. State how much storage is required as a function of r and how much storage is required for the original picture.</li>

  </ul></li>

</ol>

<strong>Note: </strong>You can use NumPy, matplotlib, opencv packages in Python for the implementation.

Figure 1: Clown image.

<a href="#_ftnref1" name="_ftn1">[1]</a> https://numpy.org/doc/stable/reference/generated/numpy.linalg.eig.html

<a href="#_ftnref2" name="_ftn2">[2]</a> https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplots.html