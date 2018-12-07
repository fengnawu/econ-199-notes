

## Homework Assignment 2
Intermediate Microeconomics (Econ 100A)  
Kristian López Vargas  
UCSC - Spring 2017

** Due on Friday 21 Apr 2017 **

** Homework assignments will be turned-in on paper, at the beginning of the corresponding lecture. Late assignments will not be accepted. ** 

** Only four randomly-chosen questions will be graded. ** 

<span style="color:red">It is graded out of 100 points and 5 points will be subtracted if you do not staple your homework.</span>

### Question 1: 
Luke's choice behavior can be represented by the utility function $u(x_1,x_2) = x_1 + x_2$. The prices of $x_1$ and $x_2$ are denoted as $p_1$ and $p_2$, and his income is $m$.   

1. Draw at least three indifference curves and find its slope $($i.e. MRS$)$. Is the MRS changing depending on the points of $(x_1,x_2)$ at which it is evaluated, or constant?  
2. Draw a budget constraint assuming that $p_1 < p_2$. Find the optimal bundle $(x^{\*}_1,x^{\*}_2)$ as a function of income and prices.  
3. Draw a budget constraint assuming that $p_1 > p_2$. Find the optimal bundle $(x^{\*}_1,x^{\*}_2)$ as a function of income and prices.  
4. Draw a budget constraint assuming that $p_1 = p_2$. Find the optimal bundle $(x^{\*}_1,x^{\*}_2)$ as a function of income and prices.  

###Solutions:
1. $MRS_{x,y} = -\\frac{MU_x}{MU_y} = -1$. The slope is constant, and not changing as we can see from the indifference curve map.  
2. See the graph below. The optimal bundle is $(x^{\*}_1,x^{\*}_2) = \\frac{m}{p_1}, 0$.  
3. See the graph below. The optimal bundle is $(x^{\*}_1,x^{\*}_2) = 0, \\frac{m}{p_2}$. 
4. See the graph below. The optimal bundle is $(x^{\*}_1,x^{\*}_2)$ such that $p_1 \times x^{\*}_1 + p_2 \times x^{\*}_2 = m$.  

![](img/HW/HW2graphs/hw2q1.jpg)


### Question 2: 
Lorelai's choice behavior can be represented by the utility function $$
u(x_1,x_2) = 0.9ln(x_1)+ 0.1x_2.$$ The prices of both $x_1$ and $x_2$ are ${$}$5 and she has an income of ${$}$40.  

1. What preference does this utility function represent? $($Hint: the utility is function is not linear, but at least linear in good $x_2$.$)$
1. Drawinwg indifference curves: you can copy down the graph on your paper using [econgraphs](https://www.econgraphs.org/graphs/micro/consumer_theory/utility_max). Set the preferences and parameters accordingly as given in the question. Click on "snap to optimal bundle'' to see the optimal choice. Click on "show indifference curve map." Draw the lowest **four** indifference curves as you see from the graph.   
2. Find the marginal utility of $x_1$ and $x_2$. What is the maximum number of $x_1$ so that  $MU_{x_1}$ is bigger than or equal to $MU_{x_2}$?  
3. Given her income of ${$}$40, how many units of $x_1$ can she buy? Would she buy any positive number of $x_2$ in light of the answer from Q2.3? Find the optimal bundle.  
4. Suppose instead her income is  ${$}$50. Would she buy any positive number of $x_2$? Find the optimal bundle using the tangency condition.  
5. Find the optimal bundle with an income of ${$}$100 using the tangency condition. What happens to the consumption amount of $x_1$ compared to the consumption of $x_1$ with an income of ${$}$50? $($Hint: In [econgraphs](https://www.econgraphs.org/graphs/micro/consumer_theory/utility_max), play around by moving an income slide bar and see how the optimal bundle changes.$)$
6. Will the optimal bundle be the same or different if the utility function were $u(x_1,x_2) = 9 ln(x_1) + x_2$? What if the utility function were $u(x_1,x_2) = x_1^9 \times exp(x_2)$? Explain.

###Solutions:
1. This is a quasilinear utility function which represents quasilinear preferences.   
2. See the graph below.  
3. $MU_{x_1} = \\frac{0.9}{x_1}$ and $MU_{x_2} = 0.1$. $MU_{x_1}$ is greater than or equal to $MU_{x_2}$ only if $x_1 \leq 9$.
4. When the income is 40, Lorelai can buy 8 units of good 1 at which point the marginal utility of good 1 is still higher than the marginal utility of consuming good 2. Hence, she wants to spend all of her income on good $x_1$ and nothing on $x_2$. In other words, $x^{\*}_1 = \\frac{m}{p_1} = \\frac{40}{5} = 8 $ and $x^{\*}_2 = 0$.  
5. When the income is 50, Lorelai can buy 10 units of good 1 at which point the marginal utility of good 1 is lower than the marginal utility of consuming good 2. In other words, she will be better off by reducing the consumption of good 1 in exchange for good 2. That means the solution is not any more at the boundary. Hence, we can solve this using tangency condition. Tangency condition says the MRS evaluated at $(x^{\*}_1, x^{\*}_2)$ is equal to the negative of price ratio, $ -\\frac{p_1}{p_2} $. The MRS is:   

$$
MRS(x_1,x_2) = - \\frac{MU_{x_1}}{MU_{x_2}} =  -\\frac{\\frac{0.9}{x_1}}{0.1} = -\\frac{9}{x_1}.$$

Since the price ratio is 1, the tangency condition is $\\frac{9}{x^{\*}_1} = 1$. This gives $x^{\*}_1 = 9$. Now use the equality of budget constraint to solve for $x^{\*}_2$:   

$$
5\times x^{\*}_1 + 5\times x^{\*}_2 = 50
\implies 5 \times 9 + 5\times x^{\*}_2 = 50
\implies x^{\*}_2 = 1
$$
6. As we've seen in the previous question, income does not enter the  tangency condition, $\\frac{9}{x^{\*}_1} = 1$. Hence ${x^{\*}_1}$ is still 9. Now using the equality of budget constraint: 
$$
5\times x^{\*}_1 + 5\times x^{\*}_2 = 100
\implies 5 \times 9 + 5\times x^{\*}_2 = 100
\implies x^{\*}_2 = 11
$$
A characteristic of quasilinear preference is that, when income is large enough, an extra increase in income is spent only one good $(x_2)$ in which the utility is linear.   
7. We can obtain the old utility function by multiplying the first utility function by $0.1$ and by taking a log transformation for the second utility function. Since they are both monotonic transformation, it preserves the preferences and the optimal bundle as well.  
![](img/HW/HW2graphs/hw2q2.jpg)


### Question 3:
Paris has a utility function over berries $($denoted by $B$ $)$ and chocolate $($denoted by $C$ $)$ as follows: 
$$
U(B,C) = \\frac{1}{3} ln(B) + \\frac{2}{3} ln(C)
$$  The price of berries and chocolate is $p_B$ and $p_C$, respectively. Paris's income is $m$. 

1. What preferences does this utility function represent?
2. Find the $MRS_{BC}$ as a function of $B$ and $C$ assuming $B$ is on the x-axis. 
3. Find the optimal bundle B and C as a function of income and prices using the tangency condition. 
4. What is the fraction of total expenditure spent on berries and chocolate out of total income, respectively?
4. Now suppose Paris has an income of ${$}$300. The price of a container of berries is ${$}$5 and the price of a chocolate bar is ${$}$4. Find the numerical answers for the optimal bundle, by plugging the numbers into the solution you found in Q3.3.

### Solutions:
1. It is a log transformation of $U(B,C) = B^{1/3} C^{2/3}$, which we know represents Cobb-Douglas preferences. Since log is a strictly increasing function, it represents the same preferences, Cobb-Douglas.
2. $$
MRS_{BC} = -\\frac{MU_B}{MU_C} = - \\frac{\\frac{1}{3}\\frac{1}{B}}{\\frac{2}{3}\\frac{1}{C}} = -\\frac{1}{2}\\frac{C}{B}.$$
3. Tangency condition: $$
\\frac{C}{2B} = \\frac{p_B}{p_C} \implies C = \\frac{p_B}{p_C} 2B $$
Plug it into the Budget constraint: $$
p_B B + p_C C = m \implies p_B B + p_C \Big(\\frac{p_B}{p_C} 2B \Big) = m \\\\
\implies p_B B + 2 p_B B = m \implies 3B = \\frac{m}{p_B} \implies B = \\frac{m}{3p_B} \\\\
\implies C = \\frac{p_B}{p_C} 2B = \\frac{p_B}{p_C} 2 \Big(\\frac{m}{3p_B}\Big) = \\frac{2m}{3p_C}
$$
Answers:$$
B^{\*}(m,p_B) = \\frac{m}{3p_B} \\\\ 
C^{\*}(m,p_C) = \\frac{2m}{3p_C}
$$ 
4. 1/3rd of income is spent on berries and 2/3rd of income is spent on chocolates. $$
p_B B^{\*}(m,p_B) = \\frac{m}{3} \\\\
p_C C^{\*}(m,p_C) = \\frac{2m}{3} 
$$ Notice the proportion is equal to the coefficients in the utility function $($i.e. $\\frac{1}{3}$ and $\\frac{2}{3}$$)$, which is a characteristic of Cobb-Douglas utility function.   
5. Answers:$$
B^{\*}(m,p_B) = \\frac{300}{3 \times 5} = 20 \\\\ 
C^{\*}(m,p_C) = \\frac{2 \times 300}{3 \times 4 } = 50
$$ 

### Question 4:
Consider a general utility function $U(x_1, x_2)$. Let's now solve for the optimal bundle generally using the Lagrangian Method.  
1. Write down the objective function and constraint in math.  
2. Set up the Lagrangian Equation.  
3. Fnd the first derivatives.  
4. Find the first order conditions.  What's the interpretation for $\lambda$?   
5. Rearrange them to get the tangency condition.

### Solutions

1. $ max $\{$ U(x_1, x_2) $\}$ $ subject to $p_{x_1} x_1 + p_{x_2} x_2 = m$  
2. $ L = U(x_1, x_2) + \lambda (m - p_{x_1} x_1 - p_{x_2} x_2)$  
3. $$
\\frac{\partial U(x_1,x_2)}{\partial x_1} - \lambda p_{x_1}  = MU_{x_1} - \lambda p_{x_1}  \\\\  
\\frac{\partial U(x_1,x_2)}{\partial x_2}  - \lambda p_{x_2} = MU_{x_2} - \lambda p_{x_2}  
$$
4. Set the above derivatives equal to zero. $$
MU_{x_1} (x_1 = x_1^{\*}) - \lambda p_{x_1} = 0 \implies \\frac{MU_{x_1}(x_1 = x_1^{\*})}{p_{x_1}}  = \lambda \\\\
MU_{x_2} (x_2 = x_2^{\*}) - \lambda p_{x_2} = 0 \implies \\frac{MU_{x_2} (x_2 = x_2^{\*})}{p_{x_2}}  = \lambda
$$
$\lambda$ measures the marginal utility of relaxing a constraint, which is an income. 
5. $$
\\frac{MU_{x_1}(x_1 = x_1^{\*})}{MU_{x_2} (x_2 = x_2^{\*})} = \\frac{p_{x_1}}{p_{x_2}}
$$

<!--
1. $max \{  \\frac{1}{3} ln(B) + \\frac{2}{3} ln(C) } $ subject to $p_B B + p_C C = m$  
2. $L = \\frac{1}{3} ln(B) + \\frac{2}{3} ln(C)  + \lambda (m - p_B B - p_C C)$  
3. $$
\\frac{\partial L}{\partial B} = \\frac{1}{3} \\frac{1}{B} - \lambda p_B  \\\\  
\\frac{\partial L}{\partial C} = \\frac{2}{3} \\frac{1}{C} - \lambda p_C
$$
4. Set the above derivatives equal to zero. $$
\\frac{1}{3} \\frac{1}{B^{\*}} - \lambda p_B = 0 \implies B^{\*} \lambda p_B = \\frac{1}{3} \\\\
\\frac{2}{3} \\frac{1}{C^{\*}} - \lambda p_C = 0 \implies C^{\*} \lambda p_C = \\frac{2}{3} 
$$
5. $$
\\frac{C}{2B} = \\frac{p_B}{p_C} \implies C = \\frac{p_B}{p_C} 2B $$
Plug it into the Budget constraint: $$
p_B B + p_C C = m \implies p_B B + p_C \Big(\\frac{p_B}{p_C} 2B \Big) = m \\\\
\implies p_B B + 2 p_B B = m \implies 3B = \\frac{m}{p_B} \implies B = \\frac{m}{3p_B} \\\\
\implies C = \\frac{p_B}{p_C} 2B = \\frac{p_B}{p_C} 2 \Big(\\frac{m}{3p_B}\Big) = \\frac{2m}{3p_C}
$$
Answers:$$
B^{\*}(m,p_B) = \\frac{m}{3p_B} \\\\ 
C^{\*}(m,p_C) = \\frac{2m}{3p_C}
$$ 
-->








### Question 5:
Jess has the utility function $U(x_1,x_2) = min ${$ 2x_1, x_2 $}$ $. The price of $x_1$ is $p_{x_1}$, the price of $x_2$ is $p_{x_2}$, and his income is $m$.  
1. Find Jess’s optimal bundle $x_1^{\*}$ and $x_2^{\*}$ as a function of $p_{x_1}$, $p_{x_2}$, and $m$.  
2. What's the proportion of consumption amounts between $x_1^{\*}$ and $x_2^{\*}$? In other words, find $\\frac{x_1^{\*}}{x_2^{\*}}$.  
3. Suppose instead the utility function is $U(x_1,x_2) = min ${$ \\frac{x_1}{2}, \\frac{x_2}{3} $}$ $. Without solving for the optimal bundles, what's the proportion of consumption amounts between $x_1^{\*}$ and $x_2^{\*}$, i.e. $\\frac{x_1^{\*}}{x_2^{\*}}$?

### Solutions
1. With perfect complements utility function, the optimal bundle is at the kink point which is when the two inputs of minimum function are equal, i.e. $2x_1 = x_2$.
Plug $2x_1 = x_2$ into the budget constraint $BC = x_1 p_{x_1} + x_2 p_{x_2} = m$:
$$ \begin{align}
\implies BC &= x_1 p_{x_1} + (2 x_1) p_{x_2} = x_1 ( p_{x_1} + 2p_{x_2}) = m \\\\
\implies x_1^{\*} &= \\frac{m}{p_{x_1} + 2p_{x_2}} \\\\
\implies x_2^{\*} &= 2 x_1^{\*}  = 2 \\frac{m}{p_{x_1} + 2p_{x_2}} \\\\
\end{align}  $$ 
2. $\\frac{x_1^{\*}}{x_2^{\*}} = \\frac{1}{2}  $
3. $ \\frac{x_1^{\*}}{2} = \\frac{x_2^{\*}}{3} \implies \\frac{x_1^{\*}}{x_2^{\*}} = \\frac{2}{3}$. Alternatively you can read off the numbers in the denominators of the utility function. 


### Question 6:
Logan has preferences over olives $(x_1)$ and ice creams $(x_2)$. He prefers to eat them separately but not together, which is represented by:
$$ U(x_1, x_2) = x_1^2 + x_2^2.$$
Also suppose his income is ${$}$100 and the prices of olives and ice creames are $p_{x_1} = {$}1$ and $p_{x_2} = {$}2$, respectively. 

1. Is this convex preferences or concave preferences? 
2. Solve for the bundle that satisfis the tangency condition.
3. What's the level of utility using the bundle you just solved in Q6.2?
4. Consider spending all of your income on olives $(x_1)$. What's the utility from this bundle?
5. Which bundle does Logan prefer between the bundle in Q6.2 and Q6.4? Does the tangency condition lead to the optimal bundle?
6. What's the optimal bundle when price of olives is ${$}$3. 

### Solutions 
1. The preference that prefers a bundle of single good over the average bundle is concave preferences. 
2. $ \\frac{MU_{x_1}}{MU_{x_2}} = \\frac{p_{x_1}}{p_{x_2}} \implies \\frac{2 x_1}{2 x_2} = \\frac{1}{2} \implies x_2 = 2 x_1$. 

Plug this into the budget constraint $BC = 1 x_1 + 2 x_2 = 100$: 
$ BC = 1 x_1 + 2 (2 x_1) = 5 x_1 = 100 \implies x_1 = 20 $ and $x_2 = 40$  
3. $20^2 + 40^2 = 2000$  
4. $100^2 + 0^2 = 10,000$  
5. Logan prefers the boundary bundle (100,0) over the interior bundle (20,40). With concave preferences, the tangency condition does not lead to the optimal bundle.  
6. With higher price for olives, the optimal bundle is $(0, \\frac{m}{p_{x_2}}) = (0, \\frac{100}{2}) = (0,50).$

### Question 7:
Consider a utility function $u(x_1, x_2) = 2x_1 + x_2$.   

1. What is the optimal bundle with $p_{x_1}$, $p_{x_2}$, and income $m$?  
2. What is the optimal bundle with $p_{x_1} = 6$, $p_{x_2} = 3$, and income $30$?

### Solutions:
1. Since perefect substitutes preferences allow for the corner solutions, we cannot use the tangency condition. There are two ways to tackle the corner solution problems. First, as shown in the lecture, we compare |MRS| with |price ratio|. |MRS| is equal to 2. Hence, as long as $\\frac{p_{x_1}}{p_{x_2}} < 2$, the optimal bundle will be $(\\frac{m}{p_{x_1}},0)$. If $\\frac{p_{x_1}}{p_{x_2}} > 2$, the optimal bundle will be $(0,\\frac{m}{p_{x_2}})$. If $\frac{p_{x_1}}{p_{x_2}} = 2$, the optimal bundle is any $ (x_1^{\*},x_2^{\*}) $ such that $ p_{x_1} \times x_1^{\*} + p_{x_2} \times x_2^{\*} = m $.   <br /><br />  Second way to solve this problem is to compare $\frac{MU_1}{p_{x_1}}$ with $\frac{MU_2}{p_{x_2}}$, which is equivalent to the comparison of |MRS| with $\frac{p_{x_1}}{p_{x_2}}$. For example, if $\frac{MU_1}{p_{x_1}} > \frac{MU_2}{p_{x_2}}$, you spend all of your income on good 1 because the marginal utility per dollar spent on good 1 is higher than the marginal utility per dollar spent on good 2.
<br />
<br />
2. Since the price ratio of 2 is equal to |MRS|, It implies any bundle that satisfies  $6 \times x^{\*}_1 + 3 \times x^{\*}_2 = 30$ is optimal. 
	
### Question 8:
Consider a utility function $u(x_1, x_2) = \sqrt{x_1} + \sqrt{x_2}$.  
1. What is the optimal bundle with $p_{x_1}$, $p_{x_2}$, and income $m$?  
2. $($optional$)$ Would the corner solution where all income is spent on single good be possible? 

### Solutions: 
1. $MU_{x_1} = \\frac{1}{2\sqrt{x_1}}$ and $MU_{x_2} = \\frac{1}{2\sqrt{x_2}}$. First, we solve for the optimal bundle using the tangency condition. $$
\\frac{MU_{x_1}}{MU_{x_2}} = \\frac{\sqrt{x_2}}{\sqrt{x_1}} = \\frac{p_{x_1}}{p_{x_2}} \implies \\frac{x_2}{x_1} = \Big(\\frac{p_{x_1}}{p_{x_2}}\Big)^2 \implies x_2^{\*} = \Big(\\frac{p_{x_1}}{p_{x_2}}\Big)^2 x_1^{\*} 
$$
Plug it into the BC. $$
p_{x_1} \times x_1^{\*}+ p_{x_2} \times \Big(\\frac{p_{x_1}}{p_{x_2}}\Big)^2 x_1^{\*} = m \\\\
\implies p_{x_1} \times x_1^{\*}+  \\frac{p_{x_1}^2}{p_{x_2}} x_1^{\*} = m \\\\
\implies x_1^{\*}  \Big(p_{x_1} + \\frac{p_{x_1}^2}{p_{x_2}}\Big) = m \\\\
\implies x_1^{\*}  =  m/ \Big(p_{x_1} + \\frac{p_{x_1}^2}{p_{x_2}}\Big) = \\frac{p_{x_2} m}{p_{x_1}(p_{x_1} + p_{x_2})} \\\\
\implies  x_2^{\*}  =  \Big(\\frac{p_{x_1}}{p_{x_2}}\Big)^2 x_1^{\*} = \\frac{p_{x_1} m}{p_{x_2}(p_{x_1} + p_{x_2})} \\\\
$$
To make sure that the interior solution from the tangency condition is optimal, we can plug in the corner solutions into the utility function and see if the level of utility is higher than the level from the interior solution. In this case, the tangency condition leads to the optimal solution. 

2. By looking at the $MU_{x_1} = \\frac{1}{2\sqrt{x_1}}$ and $MU_{x_2} = \\frac{1}{2\sqrt{x_2}}$, we can see that a tiny positive amount of either $x_1$ or $x_2$ $($i.e. as $x_1$ and $x_2$ goes to zero in the limit $)$ gives the infinite level of utility, implying that posivie numbers of both goods are preferable than consuming only one good. Hence, the corner solution is not possible.




<!--
git add docs/hw2_solutions.md && \
git commit -am " add content to hw2_solutions.md " && \
git push origin master && \
mkdocs gh-deploy
-->