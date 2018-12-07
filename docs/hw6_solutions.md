## Homework Assignment 6
Intermediate Microeconomics (Econ 100A)  
Kristian López Vargas  
UCSC - Spring 2017

** Due on Friday 9 June 2017 **

** Homework assignments will be turned-in on paper, at the beginning of the corresponding lecture. Late assignments will not be accepted. ** 

** Only four randomly-chosen questions will be graded. ** 

<span style="color:red">It is graded out of 100 points and 5 points will be subtracted if you do not staple your homework.</span>

### Question 1: 
Suppose that the monopolist faces a linear demand curve, $P(Q) = A - BQ$. Further suppose that the monopolist has the marginal cost function: $MC = Q$.

1. Find the revenue as a function of Q.
2. Find the marginal revenue as a function of Q.
3. Find the quantity that maximizes the monopolist's profit as a function of A and B.
4. Find the equilibrium price as a function of A and B. 
5. Let's use some numbers. Suppose $A=10$ and $B=2$. Solve for the profit-maximizing quantity and price.
6. Using $A=10$ and $B=2$, draw a demand curve and a marginal revenue function as well as marginal cost $($i.e. supply curve$)$. Shade the deadweight loss. Also label clearly tha profit-maximizing quantity and price chosen by the monopolist.
7. What would have been the competitive equilibrium price and quantity $($hint: equate MC and the demand function$)$? Label the competitive equilbrium point. Also compute the size of the deadweight loss due to inefficiency casued by the monopolist behavior.

### Solutions
1. $R(Q) = P(Q)\cdot Q = (A - B \cdot Q)\cdot Q = AQ - BQ^2$
2. $MR(Q) = A - 2BQ$
3. Setting $MR = MC$ gives $A-2BQ = Q$. By solving for $Q$, we get $Q_M = \\frac{A}{1+2B}$.
4. Plug $Q_M$ into the demand curve. $$\begin{aligned}
P_M &= A - B \cdot Q_M \\\\
P_M &= A - B \cdot \\frac{A}{1+2B} =  A - \\frac{AB}{1+2B} = \\frac{A+AB}{1+2B}\\\\
\end{aligned}$$
5. $Q_M = \\frac{10}{1+2\cdot 2} = 2$ and $P_M =\\frac{10+10\cdot 2}{1+2\cdot 2} = 6$.
6. Green is marginal cost $($supply curve$)$, red is linear demand, and blue is marginal revenue function. The equilibrium quantity and price is $(2,6)$.
<iframe src="https://www.desmos.com/calculator/q3mu11zm7y?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameBorder=0 /></iframe>
7. The competitive equilibrium price can be found by $Q = 10-2Q$, which gives $Q = P = 10/3$. The deadweight loss is $\frac{1}{2} \cdot 4\cdot (\frac{10}{3} - 2)= \frac{8}{3}$.


### Question 2: 
Suppose a monopolist faces a market demand of $Q^D=400-P$ and has a total cost function of $TC\left(Q\right)=Q^{2}$.

1.  What is the equilibrium price and quantity decided by the monopolist?

2. What is the average cost at the equilibrium quantity?

2.  How much profit does the monopolist make at the equilibrium price and quantity?       

### Solutions
1.  Recall that the monopolist chooses a price on the basis of $MR=MC$. Note that we need the demand function re-written to get $P$ as a function of $Q$. $$\begin{aligned}
Q & = 400-P\\\\
P & = 400-Q\end{aligned}$$ In order to find $MR$: $$\begin{aligned}
MR & = \\frac{\partial\left(PQ\right)}{\partial Q}=\\frac{\partial}{\partial Q}\cdot\left[\left(400-Q\right)Q\right]=\\frac{\partial}{\partial Q}\cdot\left[400Q-Q^{2}\right]\\\\
 & = 400-2Q\end{aligned}$$ We can find $MC$ by taking the derivative of total cost: $$MC=\\frac{\partial TC}{\partial Q}=2Q$$ Setting $MR$ and $MC$ equal: $$\begin{aligned}
400-2Q & = 2Q\\\\
400 & = 4Q\\\\
Q_{M} & = 100\end{aligned}$$ To find the price, recall that: $$\begin{aligned}
P_{M} & = 400-Q_{M}\\\\
 & = 400-100\\\\
 & = 300\end{aligned}$$

2. $AC = \\frac{TC}{Q} = \\frac{Q^2}{Q} = Q = 100$.

3. For each unit, the monopolist makes a profit of 200 $(=P - AC = 300 - 100)$. Hence, the total profit is $200 \cdot Q_M = 200 \cdot 100 = 20,000$. 

### Question 3: 
A homogeneous products duopoly faces a market demand function given by $Q=40-4P$, where $Q=Q_{1}+Q_{2}$. Both firms have a constant marginal cost $MC=2$. 

1. Suppose the two firms set their quantities simultaneously by guessing the other firm's quantity choice. Derive the equation of each firm's reaction curve and then graph these curves.

2.  What is the Cournot equilibrium quantity and price in this market for each firm?

3.  What would the equilibrium price in this market be if it were perfectly competitive? 

4.  What is the Bertrand equilibrium price in this market?

### Solutions:
1.  First note that: $$P=10-\frac{1}{4}\cdot Q$$ In equilibrium, this means that: $$P=10-\frac{1}{4}\cdot\left[Q_{1}+Q_{2}\right]$$ Solving firm 1's maximization problem yields: $$\max_{Q_{1}}P\left(Q\right)\cdot Q_{1}-c\left(Q_{1}\right)$$
$$\max_{Q_{1}} \Big(10-\frac{1}{4}Q_{1}-\frac{1}{4}Q_{2} \Big) Q_{1}-c (Q_{1})$$ 
Finding the first order condition:
$$\begin{aligned}
10-\frac{1}{2}Q_{1}-\frac{1}{4}Q_{2}-2 & = 0\\\\
\frac{1}{2}Q_{1} & = 8-\frac{1}{4}Q_{2}\\\\
Q_{1}\left(Q_{2}\right) & = 16-\frac{1}{2}Q_{2} \text{, or for graphing purpose } Q_2 = 32 - 2 Q_1\end{aligned}$$ Because of the symmetery, the firm 2's reaction function is $$Q_{2}\left(Q_{1}\right)=16-\frac{1}{2}Q_{1}$$  <iframe src="https://www.desmos.com/calculator/0zibprizoq?embed" width="500px" height="500px" style="border: 1px solid #ccc" frameBorder=0 /></iframe>

2.  To find this, plug firm 2’s reaction function into firm 1’s reaction function: $$\begin{aligned}
Q_{1}\left(Q_{2}\left(Q_{1}\right)\right) & = 16-\frac{1}{2}\cdot\left[16-\frac{1}{2}Q_{1}\right]\\\\
Q_{1}^{C} & = 16-8+\frac{1}{4}Q_{1}^{C}\\\\
\frac{3}{4}Q_{1}^{C} & = 8\\\\
Q_{1}^{C} & = \frac{32}{3}=10.67\end{aligned}$$ By symmetry, $$Q_{2}^{C}=10.67$$ The price is a function of quantities: $$\begin{aligned}
P^{C} & = 10-\frac{1}{4}\cdot\left[Q_{1}^{C}+Q_{2}^{C}\right]\\\\
& = 10-\frac{1}{4}\cdot\left[10.67+10.67\right]\approx4.67\end{aligned}$$

3.  $P^{\*}=MC=2$. The competitive equilibrium price is lower than Cournot equillibrium price. 

4.  When there are two or more firms in a market, the Bertrand equilibrium price is set at the marginal cost. In this case, the two firms' marginal cost is equal, hence, $$P^{B}\left(J>1\right)=MC=2$$


### Question 4: 
Consider a duopoly with each firm having different marginal costs. Each firm has a marginal cost curve $MC_{i}=20+Q_{i}$ for firm $i=1,2$. The market demand curve is $P=32-Q$, where $Q=Q_{1}+Q_{2}$.

1.  What are the Cournot equilibrium quantities and price in this market? 

2.  What would be the equilibrium price in this market if the two firms acted as a profit-maximizing cartel $($i.e., attempt to set prices and outputs together to maximize total industry profits $)$?

3.  What would be the equilibrium price in this market if firms acted as price-taking firms $($there are still only two firms$)$?

4.  What is the Bertrand equilibrium price in this market?

### Solutions:
1. $$\max_{Q_{1}}\left(32-Q_{1}-Q_{2}\right)Q_{1}-c_{1}\left(Q_{1}\right)$$ $$\begin{aligned}
32-2Q_{1}-Q_{2}-20-Q_{1} & = 0\\\\
3Q_{1} & = 12-Q_{2}\\\\
Q_{1}\left(Q_{2}\right) & = 4-\frac{1}{3}Q_{2}\end{aligned}$$ By symmetry, $$Q_{2}\left(Q_{1}\right)=4-\frac{1}{3}Q_{1}$$ Therefore, $$\begin{aligned}
Q_{1}\left(Q_{2}\left(Q_{1}\right)\right) & = 4-\frac{1}{3}\cdot\left[4-\frac{1}{3}Q_{1}\right]\\\\
Q_{1}^{C} & = 4-\frac{4}{3}+\frac{1}{9}Q_{1}^{C}\\\\
\frac{8}{9}Q_{1}^{C} & = \frac{8}{3}\\\\
Q_{1}^{C} & = 3\end{aligned}$$ By symmetry, $$Q_{2}^{C}=3$$ The price is a function of quantities: $$\begin{aligned}
P^{C} & = 32-Q_{1}^{C}-Q_{2}^{C}\\\\
& = 32-3-3=26\end{aligned}$$

2.  We will examine this from the perspective of each firm’s profit-maximizing contribution: $$\max_{Q_{1},Q_{2}}\left(32-Q_{1}-Q_{2}\right)\left(Q_{1}+Q_{2}\right)-c\left(Q_{1}\right)-c\left(Q_{2}\right)$$ $$\max_{Q_{1},Q_{2}}\left(32-Q_{1}-Q_{2}\right)Q_{1}+\left(32-Q_{1}-Q_{2}\right)Q_{2}-c\left(Q_{1}\right)-c\left(Q_{2}\right)$$ $$\begin{aligned}
\frac{\partial}{\partial Q_{1}} & = 32-2Q_{1}-Q_{2}-Q_{2}-20-Q_{1}=0\\\\
\frac{\partial}{\partial Q_{2}} & = 32-2Q_{2}-Q_{1}-Q_{1}-20-Q_{2}=0\end{aligned}$$ Thus, the profit-maximizing $Q_{1}$ and $Q_{2}$ are given by: $$\begin{aligned}
3Q_{1} & = 12-2Q_{2}\\\\
3Q_{2} & = 12-2Q_{1}\end{aligned}$$ Solving: $$\begin{aligned}
Q_{1} & = 4-\frac{2}{3}\cdot\left(4-\frac{2}{3}Q_{1}\right)\\\\
Q_{1} & = \frac{4}{3}+\frac{4}{9}Q_{1}\\\\
\frac{5}{9}Q_{1}^{cartel} & = \frac{4}{3}\\\\
Q_{1}^{cartel} & = \frac{12}{5}=2.4\end{aligned}$$ Similarly, we can show that: $$Q_{2}^{cartel}=2.4$$ Price is a function of these quantities, so: $$P^{cartel}=32-2.4-2.4=27.2$$

3.  We will examine from the perspective of firm 1: $$P^{\*}=MC=20+Q_{1}$$ Therefore, individual supply $($from firm 1 and, by symmetry, from firm 2$)$ is: $$S_{i}\left(P\right)=P-20$$ And market supply is: $$S_{market}\left(P\right)=2\cdot\left(P-20\right)=2P-40$$ Setting this equal to demand: $$\begin{aligned}
S\left(P\right) & = D\left(P\right)\\\\
2P-40 & = 32-P\\\\
3P & = 72\\\\
P^{\*} & = 24\end{aligned}$$

4.  The Bertrand equilibrium price is set to the marginal cost. In this case, the two firms' marginal cost is Firms would undercut to the competitive equilibrium. $$P^{B}\left(J>1\right)=MC=P^{\*}=24$$


### Question 5: 
Consider an oligopoly in which firms choose quantities. The inverse market demand curve is given by $P=a-b\left(q_{1}+q_{2}\right)$, where $q_{1}$ is the quantity produced by Firm 1, and $q_{2}$ is the quantity produced by Firm 2. Each firm has a marginal cost equal to $c$.

1.  What is the equilibrium market quantity if the two firms acted as a cartel $($i.e., attempt to set prices and outputs together to maximize total industry profits$)$. How about the equilibrium market price? 

3. Instead of cartel, suppose now firm 1 acts as the leader and firm 2 acts as the follower. What is the Stackelberg equilibrium quantities determined by each firm? What is the equilibrium market price?

4. Find $\frac{\pi_1}{\pi_2}$ using the Stackelberg quantities and price. Whose profit is higher? 

### Solutions:
<!--
1.  $$\max_{q_{1}}\left[a-b\left(q_{1}+q_{2}\right)\right]\cdot q_{1}-cq_{1}$$ $$\max_{q_{1}}aq_{1}-bq_{1}^{2}-bq_{2}\cdot q_{1}-cq_{1}$$ $$\begin{aligned}
a-2bq_{1}-bq_{2}-c & = 0\\\\
2bq_{1} & = a-c-bq_{2}\\\\
q_{1}\left(q_{2}\right) & = \frac{a-c}{2b}-\frac{1}{2}q_{2}\end{aligned}$$ By symmetry: $$q_{2}\left(q_{1}\right)=\frac{a-c}{2b}-\frac{1}{2}q_{1}$$ In equilibrium: $$\begin{aligned}
q_{1}\left(q_{2}\left(q_{1}\right)\right) & = \frac{a-c}{2b}-\frac{1}{2}\cdot\left(\frac{a-c}{2b}-\frac{1}{2}q_{1}\right)\\\\
q_{1} & = \left(1-\frac{1}{2}\right)\cdot\frac{a-c}{2b}+\frac{1}{4}q_{1}\\\\
\frac{3}{4}\cdot q_{1} & = \frac{1}{2}\cdot\frac{a-c}{2b}\\\\
q_{1}^{C} & = \frac{a-c}{3b}\end{aligned}$$ By symmetry, $$q_{2}^{C}=\frac{a-c}{3b}$$ The price is a function of quantities: $$\begin{aligned}
P^{C} & = a-b\left(q_{1}^{C}+q_{2}^{C}\right)\\\\
& = a-b\left(\frac{2\left(a-c\right)}{3b}\right)\\\\
& = \frac{3a-2a+2c}{3}\\\\
& = \frac{a+2c}{3}\end{aligned}$$
-->
1. The cartel's objective is to maximize the joint profits by choosing $q_1$ and $q_2$: $$\max_{q_{1}, q_2}\left[a-b\left(q_{1}+q_{2}\right)\right]\cdot (q_1 + q_2) -cq_{1} - cq_2$$ $$q_1: a - 2bq_1 - 2bq_2 = c \\\\ q_2: a-2bq_1- 2bq_2 = c$$ $$ \implies Q_{cartel}^{\*} = q_1 + q_2 = \frac{a-c}{2b} $$  The equilibrium price can be found by pluging $Q^{\*}$ into the demand function: $$P_{cartel}^{\*} = a-b(q_1+q_2) = a-b\frac{a-c}{2b} = \frac{b(a + c)}{2b}.$$ 
2.  Consider firm 2 responding to firm 1’s price, which it actually sees $$\max_{q_{2}}P\left(q_{1}+q_{2}\right)q_{2}-cq_{2} = (a - b(q_1 +q_2))q_2 - cq_2$$ 

FOC with respect to $q_2$ gives $$a - bq_1 - bq_2 - bq_2 -c = 0 \\\
\implies q_{2}\left(q_{1}\right)=\frac{a-c}{2b}-\frac{1}{2}q_{1}$$ 

Now, firm 1 acts first, knowing that this is how firm 2 will respond: $$\max_{q_{1}}P\left(q_{1}+q_{2}\left(q_{1}\right)\right)q_{1}-cq_{1}$$ $$\max_{q_{1}}P\left(q_{1}+\frac{a-c}{2b}-\frac{1}{2}q_{1}\right)q_{1}-cq_{1}$$ In other words: $$\max_{q_{1}}\left[a-b\left(q_{1}+\frac{a-c}{2b}-\frac{1}{2}q_{1}\right)\right]\cdot q_{1}-cq_{1}$$ $$\max_{q_{1}}aq_{1}-\frac{b}{2}q_{1}^{2}-\frac{a-c}{2}q_{1}-cq_{1}$$ $$\max_{q_{1}}\left(a-c-\frac{a-c}{2}\right)q_{1}-\frac{b}{2}q_{1}^{2}$$ $$\max_{q_{1}}\left(\frac{a-c}{2}\right)q_{1}-\frac{b}{2}q_{1}^{2}$$ The optimal choice of $q_{1}$ becomes: $$\begin{aligned}
\frac{a-c}{2}-bq_{1} & = 0\\\\
q_{1}^{S} & = \frac{a-c}{2b}\end{aligned}$$ Firm 2’s choice in reaction is given by: $$\begin{aligned}
q_{2}\left(\frac{a-c}{2b}\right) & = \frac{a-c}{2b}-\frac{1}{2}\left(\frac{a-c}{2b}\right)\\\\
& = \frac{2\left(a-c\right)-\left(a-c\right)}{4b}\\\\
q_{2}^{S} & = \frac{a-c}{4b}\end{aligned}$$ The price is a function of these quantities: $$\begin{aligned}
P^{S} & = a-b\left(q_{1}^{S}+q_{2}^{S}\right)\\\\
& = a-b\left(\frac{a-c}{2b}+\frac{a-c}{4b}\right)\\\\
& = a-\left(\frac{2\left(a-c\right)+a-c}{4}\right)\\\\
& = a-\frac{3(a-c)}{4}\\\\
& = \frac{a+3c}{4}\end{aligned}$$ 
3.  $$\begin{aligned}
\pi_{1}\left(q_{1}^{S},P^{S}\right) & = \left(P^{S}-c\right)q_{1}^{S}\\\\
\pi_{2}\left(q_{2}^{S},P^{S}\right) & = \left(P^{S}-c\right)q_{2}^{S}\\\\
\implies \frac{\pi_1}{\pi_2} &= \frac{\left(P^{S}-c\right)q_{1}^{S}}{\left(P^{S}-c\right)q_{2}^{S}}
 = \frac{\frac{a-c}{2b}}{\frac{a-c}{4b}} = 2
\end{aligned}$$
The leader earns twice as much profit as the follower. 


### Question 6: 
Suppose two firms, Genera Pharma and Futura Pharma, are the only two producers of a specific drug. Genera and Futura have the same formula and sell the drug for the same price, but they are considering whether or not to spend money on an advertising campaign. Each firm can either buy the advertising campaign or not buy it and the following table shows profits for four different scenarios.

<table style="margin:10px auto; width:50%">
<tbody>
<tr>
  <th></th>
  <th></th>
  <th colspan="2">Genera</th>
  </tr>
  <tr>
  <th></th>
  <th></th>
  <th>AD</th>
  <th>No AD</th>
  </tr>
<tr>
  <th rowspan="2">Futura</th>
  <th> <b>AD</b></th>
  <th>(4,4)</th>
  <th>(9,0)</th>
</tr>
<tr>
  <th><b>No AD</b></th>
  <th>(0,9)</th>
  <th>(5,5)</th>
</tr>
</tbody>
</table>

1.  What is the scenario that maximizes the sum of profits of the two companies?

2.  Is there a dominant strategy for each firm? 

3.  What is the pure strategy Nash Equilibrium?

4. Denote the probability of choosing $AD$ for Futura as $f$ and for Genera as $g$. Find the best response function for Futura, $b_f(g)$, and Genera, $b_g(f)$.

### Solutions:
1.  The best collective outcome is when neither firm buys advertising $($ ${$}$10 million combined payout > ${$}$9m > ${$}$8m $)$

2.  Advertising is the dominant strategy for both firms.

3.  The pure strategy Nash equilibrium is for both firms to  advertise. 

4. Then Futura's payoff is:
$$\begin{align}
&= 4fg + 9f(1-g) + 0(1-f)g + 5(1-f)(1-g) \\\\
&= 4fg + 9f - 9fg + 5 - 5f - 5g + 5fg \\\\
&= 4f + 5 - 5g\\\\
\end{align}$$
It is maximized when $f^{\*}=1$ regardless of the choise of the opponent. Hence,  $b_f(g) = 1$.
Genera's payoff is:
$$\begin{align}
&= 4fg + 0f(1-g) + 9(1-f)g + 5(1-f)(1-g) \\\\
&= 4fg + 9g - 9fg + 5 - 5f - 5g + 5fg \\\\
&= 4g + 5 - 5f \\\\
\end{align}$$ 
It is maximized when $g^{\*}=1$ regardless of the choise of the opponent. Hence, $b_g(f) = 1$

### Question 7: 
Below table shows the probability of winning for Roger Federer and Rafael Nadal for each of two groundstrokes in tennis: down the line (DL) and crosscourt (CC).

<table style="margin:10px auto; width:50%">
<tbody>
<tr>
  <th></th>
  <th></th>
  <th colspan="2">Roger Federer</th>
</tr>
<tr>
  <th></th>
  <th></th>
  <th>DL</th>
  <th>CC</th>
  </tr>
<tr>
  <th rowspan="2">Rafael Nadal</td>
  <th> <b>DL</b></th>
  <th>(50,50)</th>
  <th>(80,20)</th>
</tr>
<tr>
  <th><b>CC</b></th>
  <th>(90,10)</th>
  <th>(20,80)</th>
</tr>
</tbody>
</table>

1. Find the pure strategy NE if any.
2. Find the mixed strategy NE if any.
3. Find the probability of winning of Federer and Nadal, respectively.

### Solutions:
1. There's no pure strategy NE. 
2. Nadal solves for the value of p that equates Federer’s payoff from positioning himself for DL or CC:
$$\begin{align}
50p+10(1‐p) &= 20p+80(1‐p) \\\\ 
50p+10‐10p &= 20p+80‐80p \\\\
40p+10 &= 80‐60p \\\\
100p &= 70 \\\\
p &= 70/100 = .70.
\end{align}$$
Federer solves for the value of q that equates Nadal's payoff from positioning herself for DL or CC:
    $$\begin{align}
50q+80(1‐q) &= 90q+20(1‐q) \\\\ 
50q+80‐80q &= 90q+20‐20q \\\\
80‐30q &= 70q+20 \\\\
60 &= 100q \\\\
q &= 60/100 = .60.
\end{align}$$

3. Federer's probability of winning from DL is $DL=50(.70)+10(.30)=38\%$ and the probability of winning from CC is $CC=20(.70)+80(.30)=38\%$. Since the probabilities sum to 1, Nadal's probability of winning is 62%. 

### Question 8: Coordination Game
Consider the South Korea - North Korea arms race in which each country could build nuclear missiles or refrain from building them. The payoffs are shown in table below.

<table style="margin:10px auto; width:60%">
<tbody>
<tr>
  <th></th>
  <th></th>
  <th colspan="2">North Korea</th>
</tr>
<tr>
  <th></th>
  <th></th>
  <th>Build</th>
  <th>Refrain</th>
  </tr>
<tr>
  <th rowspan="2">South Korea</td>
  <th> <b>Build</b></th>
  <th>(4,5)</th>
  <th>(4,1)</th>
</tr>
<tr>
  <th><b>Refrain</b></th>
  <th>(3,8)</th>
  <th>(10,10)</th>
</tr>
</tbody>
</table>

1. What are the dominant strategies for each country if any?
2. What are the pure strategy NE?
2. Denote $n$ as the probability NK will build nuclear missles and $s$ as the probability SK will build nuclear missles. Find the best response function for each country, $b_s(n)$ and $b_n(s)$.
3. Find the mixed strategy NE in light of the answer in part 2

### Solutions:
1. There is no dominant strategy for either country.
2. $(Build, Build)$ and $(Refrain, Refrain)$ are the pure strategy equilibria.
2. SK's payoff: $$ 
\begin{align}
&= 4sn + 3(1-s)n+4(1-n)s+10(1-s)(1-n)\\\\
&= 4sn + 3n - 3sn + 4s - 4sn + 10 - 10n - 10s + 10sn\\\\
&= 7sn - 6s + 10 - 7n \\\\
&= s(7n-6) + 10 - 7n 
\end{align}
$$
Hence SK's best response is, $$
b_s(n) =\begin{cases}
0 & if\ n < \frac{6}{7} \\\\
\in\left[0,1\right] & if\ n = \frac{6}{7} \\\\
1& if\ n > \frac{6}{7} \\\\
\end{cases}
$$
NK's payoff: $$ 
\begin{align}
&= 5sn + 8(1-s)n+1(1-n)s+10(1-s)(1-n)\\\\
&= 5sn + 8n - 8sn + s - sn + 10 - 10n - 10s + 10sn\\\\
&= 6sn - 9s - 2n + 10\\\\
&= n(6s-2) + 10 - 9s
\end{align}
$$
Hence NK's best response is, $$
b_n(s) =\begin{cases}
0 & if\ s < \frac{1}{3} \\\\
\in\left[0,1\right] & if\ s = \frac{1}{3} \\\\
1& if\ s > \frac{1}{3} \\\\
\end{cases}
$$
3. $(s=\frac{1}{3}, n=\frac{6}{7})$ is the mixed strategy equilibrium. 

### Question 9: Centipede game
The centipede game, first introduced by Robert Rosenthal in 1981, is an extensive form game in which two players take turns choosing either to take a slightly larger share of an increasing pot, or to pass the pot to the other player. In other words, player 1 chooses between D $($Down$)$ and R $($Right$)$, where **D** is pocketing the pot and **R** is passing the pot to the player 2. Similarly, player 2 chooses between $d$ and $r$.

 The payoffs are arranged so that if one passes the pot to one's opponent and the opponent takes the pot on the next round, one receives slightly less than if one had taken the pot on this round.

<img src="https://upload.wikimedia.org/wikipedia/commons/6/68/Centipede_game.png" style="max-height:30%; align-content:bottom; border:0">

1. Find the subgame perfect Nash Equilibrium using backward induction.

### Solutions:
1. For backward induction, we start from the last node at which player 2 decides between $d$ which gives $(2,4)$ and $r$ which gives $(3,3)$. Since $4>3$, the player 2 will choose $d$. 
Now on the second node from the last, knowing player 2 will choose $d$, player 1 chooses between $(3,1)$ and $(2,4)$. Since $3>2$, player 1 chooses $D$. 
Similarly, on the third node from the last, player 2 chooses $d$, and finally on the very first node, player 1 chooses $D$. 

To write down the equilibrium of strategies, strategies have to be specified at every node of decisions. There are two nodes $($1st, 3rd$)$ for player 1 and two nodes $($2nd, 4th$)$ for player 2. In a long version, $($Player 1 plays $D$ in her 1st node, Player 1 plays $D$ in her 2nd node; Player 2 plays $d$ in her 1st node, Player 2 plays $d$ in her 2nd node$)$ is the subgame perfect NE. In a short version, $(DD; dd)$ is the subgame perfect NE.
	
### Question 10: Ultimatum Game
The ultimatum game is a game in economic experiments. The first player $($the proposer$)$ receives a sum of money and proposes a fair proposal $($**F** - 5;5$)$ or unfair proposal $($**U** - 8;2$)$. The second player $($the responder$)$ chooses to either accept $($**A**$)$ or reject $($**R**$)$  this proposal. If the second player accepts, the money is split according to the proposal. If the second player rejects, neither player receives any money. 

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/be/Ultimatum_Game_Extensive_Form.svg/1280px-Ultimatum_Game_Extensive_Form.svg.png" style="max-height:30%; align-content:bottom; border:0">

1. Find the subgame perfect Nash Equilibrium using backward induction.

### Solutions:
1. Given the fair proposal, the second player choose to accept the proposal because $5 > 2$. Given the unfair proposal, the second player chooses to accept the proposal because $2 > 0$. Knowing this, the first palyer will choose $U$ over $F$ because $8>5$. 

To write down the equilibrium of strategies, strategies have to be specified at every node of decisions. There is one node for player 1 and two nodes for player 2. In a long version, $($Player 1 plays $U$; Player 2 plays $A$ if player 1 plays $F$, Player 2 plays $A$ if player 1 plays $U$ $)$ is the subgame perfect NE. In a short version, $(U; AA)$ is the subgame perfect NE.

In Reality? According to [this](https://en.wikipedia.org/wiki/Ultimatum_game#Experimental_results), "When carried out between members of a shared social group $($e.g., a village, a tribe, a nation, humanity$)$ people offer "fair" $($i.e., 50:50$)$ splits, and offers of less than 30% are often rejected."