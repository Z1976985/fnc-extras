## Chapter 1
* **Page 19/Exercise 1.2.7.** The polynomial in part (a) should be `x^2 - (2+ep)*x + 1`, not `x^2 + (2+ep)*x + 1`. (Thanks to Nicholas Harty.)
* **Page 23 / Example 1.3.3** "Using (1.2.8)" should be "using (1.2.9)."
* **Page 27 / Exercise 1.3.4** The wording in this problem could be clearer. Here is an [alternate version](alt134.pdf).

## Chapter 3
* **Page 102 / Exercise 3.1.3.** (a) The last coefficient should be `c_8`. (Thanks John Tran.)
* **Page 118 / Exercise 3.4.8.** The RHS should be `\begin{bmatrix} \sqrt{\alpha^2 + \beta^2} \\ 0 \end{bmatrix}`. (Thanks Chris Reynolds and Franklin Dyer.)

## Chapter 4
* **Page 127 / Exercise 4.1.9.** In part (a), the plus sign in the definition of $\tilde{f}_\epsilon$ should be a minus sign, i.e., $\tilde{f}_\epsilon(x) = f_\epsilon(x)/(x-1.01)$. (Thanks Andrew Geyko and Franklin Dyer.)
* **Page 161** In the formula between (4.6.3) and (4.6.4), all the variable names should be in bold, as they are all vectors and matrices.
* **Page 165 / Exercise 4.6.4.** The Sherman-Morrison formula is given incorrectly (specifically, the denominator). It should read:  
![formula](Sherman-Morrison.svg).  
(Thanks to Claudio Torres.)

## Chapter 5
* **Page 190 / (5.3.5) and (5.3.6)** The right-hand sides of both equations should be vectors, not diagonal matrices. (Thanks to Wei Cai.) 
* **Page 199 / (5.4.11)** The sum should start at k=0 to be in sync with the code (this formula is not needed elsewhere). (Thanks to Shahrokh Esmaeili.)
* **Page 201 / Exercise 5.4.5** The nodes in part (a) are given by t_j = 0.3 + jh. (Thanks to Shahrokh Esmaeili.)
* **Page 215 / Example 5.5.3** The first expression in the last line of the formula should have a negative sign in front. (Thanks to Peter Monk.) 
* **Page 237, Exercise 5.7.6** The definition of erf should have sqrt(pi) in the denominator, not pi.

## Chapter 6
* **Page 255, Exercise 6.2.2** The exact solution of the IVP in part (e) is exp((x^3+3x-4)/3), and the exact solution in part (f) is 6/(2x^3+6x+3).
* **Function 6.5.1** In line 30, the variable `unew2` is the 3rd-order solution, not the 2nd-order solution as the variable name and comment imply. (Thanks to Tom Hagstrom.)

## Chapter 7
* **Page 305 / Theorem 7.2.2** Replace "an nonsingular" with "a nonsingular".

## Chapter 8
* **Page 326 / Proof of Theorem 8.3.1** In the fourth line of the proof the first term `(A-sI)` should be replaced with `(A-sI)⁻¹`.
* **Page 332 / sentence before or actually containing (8.4.1)** should have `n×m` instead of `m×n`.
* **Page 362 / Function 8.5.1** The function runs correctly as printed. However, the `H` and `Q` matrices there are initially allocated smaller than their final sizes. (MATLAB expands them anyway.) Also, to be consistent with the earlier arnoldi.m function, replace `M` with `m` and `m` with `j`. 

## Chapter 9
* **Page 387 / Figure in example 9.1.1** The y-axis label was not rendered correctly; it is the cardinal polynomial l_2.
* **Page 390 / (9.6.2)** The last expression needs to be multiplied by 2. (Thanks to Wei Cai.) 
* **Page 423 / Example 9.6.2** In the last line, the results "x_1" and "x_2" should be named "t_1" and "t_2". 

## Chapter 10
* **Page 415 / Exercise 10.1.1** The boundary conditions were left out of the problem statements. Suggestions: (a) u(0) = 2, u(1) = 3; (b) u'(0) = -1, u(4) = 2; (c) u(-1) = 2, u(1) = 3.
* **Page 416 / Exercise 10.1.2** (c) Typo in boundary conditions; they should be u(-1) = -1, u(1) = 1. (d) Typo in the ODE, use (1-x^2)u'' rather than (1-u^2)u''. 
* **Page 467 / Equation (10.4.6a)** The beta in this equation should be gamma. 
* **Page 468 / Function 10.4.1** Line 15 in the function documentation should be deleted, as it references a nonexistent output argument. 

## Chapter 12 
* **Page 540 / Example 12.4.1** The z-axis of the left-side plot was omitted and should be "u". 

## Chapter 13
* **Page 547 / Example 13.1.2** The example function should read f(x,y) = sin(xy-y).
* **Page 554 / Exercise 13.3.3(b)** The solution of the PDE is u(x,y) = sinh(4xy-x). (Thanks to Tom Hagstrom.)
* **Page 573 / Example 13.4.2** After the reference to (13.3.6), the next sentence should start, "The second term," not "The first term." 
