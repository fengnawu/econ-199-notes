

## Homework Assignment 4
Intermediate Microeconomics (Econ 100A)  
Kristian López Vargas  
UCSC - Spring 2017

** Due on Friday 12 May 2017 **

** Homework assignments will be turned-in on paper, at the beginning of the corresponding lecture. Late assignments will not be accepted. ** 

** Only four randomly-chosen questions will be graded. ** 

<span style="color:red">It is graded out of 100 points and 5 points will be subtracted if you do not staple your homework.</span>

### Question 1: 
Suppose a firm has the following production function: $$Q(L,K)=4K^{1/2}L^{1/2}$$ Recall that the isocost line is as follows: $$C=wL+rK$$

1.  What is the $($long run$)$ optimal choice of $L$ and $K$ for a given $Q$, $w$, and $r$? In other words, provide a formula for the optimal choice of labor $L^{\*}(w,r,Q)$ and capital $K^{\*}(w,r,Q)$ as a function of the parameters $Q$, $w$, and $r$.

2.  Given $Q=16$, $w=4$, and $r=1$, what are the optimal levels of labor and capital, $L^{\*}$ and $K^{\*}$? What is the cost of producing $Q=16$ at these input prices?
   
3.  Suppose now that you are in the short run, $Q=16$, $w=4$, $r=1$, and the capital level is fixed at $\bar{K}=4$. What is the optimal level of labor in the short run? What is the cost of producing $Q=16$ in the short run at these input prices?
        
### Solutions
1. Begin with the optimal conditions from cost minimization: 	
$$ \begin{align}
\\frac{MP_{L}}{MP_{K}} & = \\frac{w}{r}\\\\
\\frac{2K^{1/2}L^{-1/2}}{2K^{-1/2}L^{1/2}} & = \\frac{w}{r}\\\\
\\frac{K}{L} & = \\frac{w}{r}\\\\
K & = \\frac{w}{r}\cdot L\end{align}$$ We pair this condition with the production function: $$\begin{align}
Q & = 4\left(\\frac{w}{r}\cdot L\right)^{1/2}L^{1/2}\\\\
Q & = 4\left(\\frac{w}{r}\right)^{1/2}L\\\\
L^{\*}(w,r,Q) & = \\frac{1}{4}\left(\\frac{r}{w}\right)^{1/2}Q\end{align}$$ Note that: $$\begin{align}
K^{\*}(w,r,Q) & = \\frac{w}{r}\cdot L^{\*}(w,r,Q)\\\\
& = \\frac{1}{4}\cdot\\frac{w}{r}\cdot\left(\\frac{r}{w}\right)^{1/2}Q\\\\
& = \\frac{1}{4}\left(\\frac{w}{r}\right)^{1/2}Q
\end{align}
$$

2.  We can simply insert these numbers into our formula from part (a): $$\begin{align}
        L^{\*}\left(4,1,16\right) & = \\frac{1}{4}\cdot\left(\\frac{1}{4}\right)^{1/2}\cdot16=2\\\\
        K^{\*}\left(4,1,16\right) & = \\frac{1}{4}\cdot\left(\\frac{4}{1}\right)^{1/2}\cdot16=8\end{align}$$ Knowing this, we can calculate the cost of producing $Q=16$ at these prices: $$\begin{align}
        Cost^{\*}(w,r,Q) & = wL^{\*}(w,r,Q)+rK^{\*}(w,r,Q)\\\\
         & = 4\cdot2+1\cdot8=16\end{align}$$

3. We now find the optimal choice of labor given $K=4$: $$Q\left(L|K=4\right)=4\left(4\right)^{1/2}L^{1/2}=8L^{1/2}$$ $$\begin{align}
        8L^{1/2} & = Q\\\\
        L^{1/2} & = \\frac{Q}{8}\\\\
        L & = \\frac{Q^{2}}{64}=\\frac{16^{2}}{8^{2}}=4\end{align}$$ The cost is given by: $$\begin{align}
        Cost_{SR}(w,r,Q) & = wL_{SR}(w,r,Q)+rK_{SR}\\\\
         & = 4\cdot4+1\cdot4=20\end{align}$$


### Question 2: 
Suppose a firm has the following production function: $$ Q(L,K)=\min \\{K,4L\\} $$ Recall that the isocost line is as follows: $$ C=wL+rK $$

1.  What is the $($long-run$)$ optimal choice of $L$ and $K$ for a given $Q$, $w$, and $r$? In other words, provide a formula for the optimal choice of labor $L^{\*}(w,r,Q)$ and capital $K^{\*}(w,r,Q)$ as a function of the parameters $Q$, $w$, and $r$.

2.  Given $Q=16$, $w=4$, and $r=1$, what are the optimal levels of labor and capital, $L^{\*}$ and $K^{\*}$? What is the cost of producing $Q=16$ at these input prices?

3.  Suppose now that you are in the short run, $Q=16$, $w=4$, $r=1$, and the capital level is fixed at $\bar{K}=20$. What is the optimal level of labor in the short run? What is the cost of producing $Q=16$ in the short run at these input prices? Would it be possible to meet $Q=16$ if $K=4$ in the short run?


### Solutions
1. Recall that the optimal choice for a $($perfect complements$)$ production function lies along the ray $ aK=bL $ $($ in this case, $K=4L$ $)$ from the origin. With this in mind, $$K^{\*}(w,r,Q)=4L^{\*}(w,r,Q)=Q$$ In other words, the optimal long-run choice of labor and capital for a given quantity does not depend on factor prices. $$\begin{align}
K^{\*}(w,r,Q) & = Q\\\\
L^{\*}(w,r,Q) & = \\frac{1}{4}Q\end{align}$$

2. We can simply insert these numbers into our formulas from part (a): $$\begin{align}
K^{\*}\left(4,1,16\right) & = 16\\\\
L^{\*}\left(4,1,16\right) & = \\frac{1}{4}\cdot16=4\end{align}$$ The cost of producing $Q=16$ is $C = rK + wL = 1\times 16 + 4 \times 4 = 32 $.

3. Note that if $K=20$, the production function becomes: $$ Q(L)=\min \\{ 20,4L\\}. $$ In other words, if $4L\le20$ $($ i.e. $L\le5$ $)$: $$Q(L)=4L.$$ For $L>5$, $$Q(L)=20$$ If $Q=16,$ the optimal choice of $L$ would be: $$\begin{align}
4L_{SR} & = Q=16\\\\
L_{SR} & = 4\end{align}$$ 
The short-run cost is $$C = r\bar{K} + wL = 1\times 20 + 4 \times 4 = 36 $$
If $K=4$, note that $$ Q(L)=\min\\{ 4,4L\\} $$ The maximum possible $Q$ would be 4, so $Q=16$ is not attainable.

     
### Question 3: 
Suppose a firm has the following production function: $$Q(L,K)=3L+K$$ Recall that the isocost line is as follows: $$C=wL+rK$$

1.  What is the $($ long-run $)$ optimal choice of $L$ and $K$ for a given $Q$, $w$, and $r$? In other words, provide a formula for the optimal choice of labor $ L^{\*}(w,r,Q) $  and capital $ K^{\*}(w,r,Q)$  as a function of the parameters $Q$, $w$, and $r$.

2.  Given $Q=16$, $w=4$, and $r=1$, what are $L^{\*}$ and $K^{\*}$?


### Solutions
1. Note that for perfect substitutes, the solution will be to produce using only one input unless $ \\frac{w}{r}=\\frac{MP_{L}}{MP_{K}} $. We know that we will produce using only labor if: 
$$\begin{align}
\\frac{MP_{L}}{w} & > \\frac{MP_{K}}{r}\\\\
\\frac{3}{w} & > \\frac{1}{r}.
\end{align}$$
We also know that this would entail a production function of: $$Q=3L$$ Similarly, we will produce using only capital if: $$\begin{align}
\\frac{MP_{L}}{w} & <  \\frac{MP_{K}}{r}\\\\
\\frac{3}{w} & <  \\frac{1}{r}\end{align}$$ Which would entail a production function of: $$Q=K$$ Therefore: $$
L^{\*}(w,r,Q)=\begin{cases}
\\frac{Q}{3} & if\ \\frac{w}{r}<3\\\\
\in\left[0,\\frac{Q}{3}\right] & if\ \\frac{w}{r}=3\\\\
0 & if\ \\frac{w}{r}>3
\end{cases}$$ $$K^{\*}(w,r,Q)=\begin{cases}
0 & if\ \\frac{w}{r}<3\\\\
Q-3L & if\ \\frac{w}{r}=3\\\\
Q & if\ \\frac{w}{r}>3
\end{cases}
$$

2. We can substitute these numbers into our formulas from the question above. Note that $\\frac{w}{r}=4>3$ $$\begin{align}
L^{\*}\left(4,1,16\right) & = 0\\\\
K^{\*}\left(4,1,16\right) & = Q=16\end{align}$$

### Question 4: 
A firm uses two inputs, capital and labor, to produce output. Its production function exhibits a diminishing technical rate of substitution $($e.g. Cobb-Douglas production function$)$. 

1.  If the price of capital and the price of labor increase by the same percentage $($e.g., 40 percent$)$, what will happen to the cost-minimizing input quantities for a given output level?


2.  If the price of capital increases by 20 percent while the price of labor increases by 40 percent, what will happen to the cost-minimizing input quantities for a given output level?

### Solutions
1. The cost-minimizing input quantities for a given output level will not change, as they depend only on the ratio of input prices $\\frac{w}{r}$.

2. Since $\\frac{w}{r}$ is now higher than before the price change, the new choice of $L$ and $K$ would also have to satisfy a higher technical rate of substitution to ensure that $$\\frac{MP_{L}}{MP_{K}}=\\frac{w}{r}.$$ This implies that, for a production function with a diminishing technical rate of substitution, the firm would be using less labor $($ graphically the slope of isoquant is steeper $)$. 


### Question 5: 
Suppose a brewery uses a Cobb-Douglas production function for his production. He studies the production process and finds the following. An additional machine-hour of fermentation capacity would increase output by 400 bottles per day $(i.e. MP_K = 400)$. An additional man-hour of labor would increase output by 900 bottles per day $(i.e. MP_L = 900)$. The price of a man-hour of labor is ${$}$18 per hour. The price of a machine-hour of fermentation capacity is ${$}$5 per hour.

1. Is the brewery currently minimizing its cost of production? Check using the minimization condition.

2. It turns out, the brewery is not optimally chossing the factors of production. To lower its production cost, which factor of production should the brewery increase and which factor should he decrease? 

3.  Suppose that the price of a machine-hour of fermentation capacity rises to ${$}$8 per hour. How does this change the answer from part 1?


### Solutions
1. We want to verify whether the brewery is producing at the cost-minimizing choice, which must satisfy: $$\begin{align}
\\frac{MP_{L}}{MP_{K}} & =  \\frac{w}{r}, \text{ or }\\\\
\\frac{MP_{L}}{w} & =  \\frac{MP_{K}}{r}\\\\ \end{align}$$
Now, plug in the numbers to check the condition:
$$\begin{align}
\\frac{900}{18} & <  \\frac{400}{5}\\\\
50 & < 80\end{align}$$ Since the minimization condition does not hold, he could reduce the cost of production without impacting the output level. 

2.  Since the marginal product of a dollar spent on capital $\left(\\frac{MP_{K}}{r}\right)$ exceeds the marginal product of a dollar spent on labor $\left(\\frac{MP_{L}}{w}\right)$, the brewery could lower its total production costs and keep output constant by reducing labor inputs and increasing capital inputs.

3. In our calculations we would update the price: $$\begin{align}
\\frac{900}{18} & = \\frac{400}{8}\\\\
50 = 50\end{align}$$ In this case, the brewery is mimizing the cost of production. 

<!--
### Question 6: 
Draw a graph of the demand curve for capital when the firm wants to produce 15 units of output, for each of the following production functions:

1.  $Q=\min\\{ L,K\\} $ - inputs are perfect complements

2.  $Q=L+K$ - inputs are perfect substitutes $($assume the price of labor = 5, for simplicity$)$

### Solutions
-->


### Question 6: 
For each of the total cost functions, write the expressions for the average cost, average fixed cost, average variable cost, and marginal cost:

1.  $TC\left(Q\right)=5Q$

2.  $TC\left(Q\right)=120+5Q$

3.  $TC\left(Q\right)=5Q^{2}$

4.  $TC\left(Q\right)=120+5Q^{2}$


### Solutions
1. $$\begin{align}
AC & = \\frac{5Q}{Q} = 5\\\\
AFC & = 0 \\\\
AVC & = \\frac{5Q}{Q}=5\\\\
MC & = \\frac{5Q}{\partial Q}=5\end{align}$$

2. $$\begin{align}
AC & = \\frac{120+5Q}{Q} = \\frac{120}{Q} + 5 \\\\
AFC & = \\frac{120}{Q} \\\\
AVC & = \\frac{5Q}{Q}=5\\\\
MC & = \\frac{\partial (120+5Q)}{\partial Q}=5\end{align}$$

3. $$\begin{align}
AC & = \\frac{5Q^2}{Q} =  5Q \\\\
AFC & = 0 \\\\
AVC & = \\frac{5Q^2}{Q}=5Q\\\\
MC & = \\frac{\partial 5Q^2}{\partial Q}=10Q\end{align}$$

4. $$\begin{align}
AC & = \\frac{120+5Q^2}{Q} = \\frac{120}{Q} + \\frac{5Q^2}{Q} = \\frac{120}{Q} + 5Q \\\\
AFC & = \\frac{120}{Q} \\\\
AVC & = \\frac{5Q^2}{Q}=5Q\\\\
MC & = \\frac{\partial (120+5Q^2)}{\partial Q}=10Q\end{align}$$


### Question 7: 
Suppose a firm’s long-run total cost is as follows: $$TC\left(Q\right)=30Q-20Q^{2}+Q^{3}$$

1.  For what range of $Q$ does this cost function exhibit economies of scale?


2.  For what range of $Q$ does this cost function exhibit diseconomies of scale?


### Solutions
1. Recall that a cost function exhibits economies of scale when average cost is decreasing as Q increases. We are therefore looking for the range of Q under which $$\begin{align}
\\frac{\partial AC}{\partial Q} & <  0\\\\
\\frac{\partial}{\partial Q}\left(30-20Q+Q^{2}\right) & <  0\\\\
-20+2Q & <  0\\\\
Q & <  10\end{align}$$

2. Recall that a cost function exhibits diseconomies of scale when average cost is increasing as Q increases. We are therefore looking for the range of Q under which $$\begin{align}
\\frac{\partial AC}{\partial Q} & >  0\\\\
-20+2Q & >  0\\\\
Q & >  10\end{align}$$


### Question 8: 
A firm produces a product with labor and capital as inputs. The production function is described by $Q=2LK$. Let $w=1$ and $r=1$ be the prices of labor and capital, respectively.

1.  Find the equation for the long-run total cost curve as a function of quantity $Q$.

2.  Solve the short-run cost-minimization problem when capital is fixed at a quantity of 5 units $(i.e., K=5)$. Derive the equation for the firms short-run total cost curve as a function of quantity $Q$ and graph it together with the long-run total cost curve.

3.  $($optional$)$. How would the short-run and long-run total cost curves look like if we increase/decrease $w$ and $r$? Comment.


### Solutions
1. Recall that the cost-minimizing condition is $$\begin{align}
\\frac{MP_{L}}{MP_{K}} & = \\frac{w}{r}\\\\
\\frac{2K}{2L} & = \\frac{w}{r}\\\\
K^{\*} & = \\frac{w}{r}L^{\*}\end{align}$$ We can then use the production function to find formulas for both $K^{\*}$ and $L^{\*}$: $$\begin{align}
Q & = 2L^{\*}\left(\\frac{w}{r}\cdot L^{\*}\right)=2\cdot\\frac{w}{r}\cdot\left(L^{\*}\right)^{2}\\\\
\\frac{Q}{2}\cdot\\frac{r}{w} & = \left(L^{\*}\right)^{2}\\\\
L^{\*} & = \left(\\frac{r}{w}\cdot\\frac{Q}{2}\right)^{1/2}\end{align}$$ Similarly, $$\begin{align}
K^{\*} & = \\frac{w}{r}L^{\*}\\\\
& = \\frac{w}{r}\cdot\left(\\frac{r}{w}\cdot\\frac{Q}{2}\right)^{1/2}\\\\
& = \left(\\frac{w}{r}\cdot\\frac{Q}{2}\right)^{1/2}\end{align}$$ We can then plug these into the long-run total cost curve: $$\begin{align}
TC(w,r,Q) & = wL^{\*}+rK^{\*}\\\\
& = w\cdot\left(\\frac{r}{w}\cdot\\frac{Q}{2}\right)^{1/2}+r\cdot\left(\\frac{w}{r}\cdot\\frac{Q}{2}\right)^{1/2}\\\\
& = \left(w\cdot r\cdot\\frac{Q}{2}\right)^{1/2}+\left(w\cdot r\cdot\\frac{Q}{2}\right)^{1/2}\\\\
& = 2\cdot\left(w\cdot r\cdot\\frac{Q}{2}\right)^{1/2}\\\\
& = \left(2\cdot w\cdot r\cdot Q\right)^{1/2}\end{align}$$ For $w=1$, $r=1$: $$TC\left(Q\right)=\left(2\cdot1\cdot1\cdot Q\right)^{1/2}=\sqrt{2Q}$$

2. If $K=5$, $$\begin{align}
Q & = 2\cdot5\cdot L=10L\\\\
L_{SR} & = \\frac{Q}{10}\end{align}$$ Consequently, the short-run total cost curve is as follows: $$\begin{align}
TC_{SR}(w,r,Q) & = wL_{SR}+r \cdot 5\\\\
& = w\cdot\left(\\frac{Q}{10}\right)+5r\end{align}$$ For $w=1$, $r=1$: $$\begin{align}
TC_{SR}\left(Q\right) & = 1\cdot\left(\\frac{Q}{10}\right)+5\cdot1\\\\
& = 5+\\frac{Q}{10}\end{align}$$
See the graph below where the long-run cost curve is in red and short-run cost is in green. We can see that short-run cost, with the level of capital fixed, is higher than the long-run cost in which the level of capital is allowed to be adjusted. Note that there will be a specific level of output, where short-run cost and long-run cost is equal, where the optimal level of capital is the fixed level of capital.  
<iframe src="https://www.desmos.com/calculator/y7oifmicne?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameBorder=0 /></iframe>


3. Recall $$\begin{align}
TC_{LR}(w,r,Q) & = \left(2\cdot w\cdot r\cdot Q\right)^{1/2} \\\\
TC_{SR}(w,r,Q) & = w\cdot\left(\\frac{Q}{10}\right)+5r
\end{align}$$

The change in $w$ and $r$ would yield to the same change in $TC_{LR}(w,r,Q)$, while it has a differential effect on $TC_{SR}(w,r,Q)$. A change in $w$ changes the slope of the short-run total cost while a change in $r$ changes the fixed cost of the short-run total cost. See the graphs below as an example with  $(r,w) = (2,1)$ and $(r,w) = (1,2)$.

<iframe src="https://www.desmos.com/calculator/olmezvngpv?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameBorder=0 /></iframe>

<iframe src="https://www.desmos.com/calculator/isioogc0t0?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameBorder=0 /></iframe>