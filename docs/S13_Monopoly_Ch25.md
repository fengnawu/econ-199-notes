
## Producer (Chapter 3) 

#### Intermediate Microeconomics (Econ 100A)

#### Natalia Lazzati

#### UCSC - Winter 2019


---------

## 3.1 Profit Maximization

We will study profit maximization in competitive markets. These are markets where each firm takes as given both the price of the good that it produces and the prices of the inputs that it uses to produce that good (e.g., labor and capital). 

There are two key concepts in our model of the competitive firm:

1. **Technology**: It tells us how much the firm can produce for each combination of inputs.
2. **Prices of the output** ---or the good that it produces--- and inputs.

Together, **1** and **2** determine both how much a competitive firm will optimally produce and how is going to produce it.

To simplify the exposition, we will focus on a simple version of the problem of the firm ---as we did with consumer problem. The components of our model are as follows:

1. We assume there are only two inputs: input 1 and input 2.
2. We represent the quantities of these inputs as x1 and x2, respectively.
3. The production function is given by f(x1,x2).
4. The prices of the inputs are represented by w₁ and w₂, respectively.
5. The price of the output is represented _p_.

The purpose of the firm is to select the combination of inputs that maximizes its profits. More formally, we can express its problem as follows

- max x1,x2 {pf(x1,x2)-w1x1-w2x2}

where pf(x1,x2) is the revenue of the firm and w1x1 + w2x2

To solve this problem, we will assume that the production function of the firm, fx1,x2,  is differentiable and the solution of the problem is interior. When these conditions are satisfied, then the First Order Conditions (FOCs) are as follows

- p∂f(x1,x2)/∂x1-w1 = 0	     **(FOC1)**

- p∂f(x1,x2)/∂x2-w2 = 0	     **(FOC2)**

The solution of this problem is given by the pair 

- x1(p,w1,w2)   and   x2(p,w1,w2)

that simultaneously solves the system of two equations FOC1 and FOC2. 
These functions are called the unconditional input demands of the firm

The output function is given by

- y(p,w1,w2)=f(x1(p,w1,w2),x2(p,w1,w2)).

This function tells us how much the firm will optimally produce for each combination of the prices of the output and inputs that it might face. 

The optimal solution of the firm problem has an interesting economic interpretation. To show it, let

- MPi(x1,x2)= ∂f(x1,x2)/∂xi   for i=1,2

be defined as the marginal product of input i. It represents the extra amount of the good that the firm gets by increasing input i in one unit. Using this concept, the optimal solution satisfies

- MP1(x1,x2)/ w1= MP2(x1,x2)/w2

That is, the marginal product per dollar spent in each input is the same for the two of them. To see why this should be the case, let us assume that the firm is producing at a point in which

- MP1(x1,x2)/ w1 > MP2(x1,x2)/w2

This means that the extra product per dollar spent in input 1 is strictly higher than the extra product the firm gets per dollar spent in input 2. In this case, the firm could be better off by increasing the amount of the first input and decreasing the amount of the second one. Doing so, the firm could produce the same in a cheaper way! This process stops when both terms are the same. (A similar idea applies to the case in which MP1(x1,x2)/ w1 < MP2(x1,x2)/ w2 .)

**Example**:  Let us assume the production function of the firm has a Cobb-Douglas specification. In particular, let

- f(x1,x2)=(x1)^1/4(x2)^1/4

Under this specification, the problem of the firm is 

- max x1,x2 { px11/4x21/4- w1x1-w2x2 } 

Differentiating with respect to the two input variables we get

 p1/4x1-3/4x21/4-w1=0	 (FOC1)

 p1/4x11/4x2-3/4-w2=0	 (FOC2)

Together, these two equations imply that 

- x2w2 = x1w1 

Substituting this expression in FOC1 we get 

x1' =1/16 p2 w1-3/2w21/2   and   x2' =1/16 p2 w11/2w2-3/2. 

Thus, the optimal level of production of the firm is

 y* = f(x1',x2') = [(1/16)p2w1-3/2w21/2]^1/4 [(1/16)p2w11/2w2-3/2]1/4 = p/[4(w1w2)1/2] 

When we studied the problem of the consumer we illustrated the ideas by using three different specifications of the utility function:

- Cobb-Douglas
- Perfect Substitutes
- Perfect Complements

While the same three specifications can be used for the production function of the firm, some of them lead to unreasonable conclusions for the competitive environment. 

**Example**: Let us assume the production function of the firm has a perfect substitutes specification. In particular, let

- f(x1,x2)=x1 + x2.

Under this specification, the problem of the firm is

max x1,x2 {p(x1+x2)-w1x1-w2x2} 

Suppose that, for some x1=x1' and x2=x2', 

px1'+x2'-w1x1'-w2x2'=10>0.

That is, with this combination of inputs the firm is making 10$. Let us next consider using twice as much input as before. Then,

p(2x1'+2x2')-w1(2x1')-w2(2x2') = 2[p(x1'+x2')-w1x1'-w2x2'] = 20 > 0

This means that, by doubling the amount of the inputs, then the firm gets twice as much profits as before. By repeating this process a few times, you will realize that the optimal level of inputs are just infinite! Since we do not observe firms behaving in this way, we conclude that this specification of the production function is probably not adequately when we model competitive markets.

One can show that a similar problem appears for the perfect complement specification of the production function and with the Cobb-Douglas one when a + b > 1

----------------------
## 3.2 Profit Maximization and Cost Minimization
The problem of the firm can be studied in a different way

- maxy {py - C(y)}

where C(y) is the minimum cost of producing y. The FOC of this problem is captured by

- p=C'(y)

where C'(y)=Cy/y is the marginal cost function. 

The solution of this problem, y*=y(p), is the supply function (or supply curve) of the firm.

To show that this problem is indeed equivalent to the one of maximizing profits we just studied, we need to find an expression for the minimum cost function C(y).

The problem of cost minimization can be postulated as follows: The firm wants to produce a specific amount of good, y, in the cheapest possible way. Formally, its problem is given by

- minx1,x2{w1x1 + w2x2: f(x1,x2)=y}

Note that this problem is relevant for any profit maximizing firm ---even those with market power! 

The problem of cost minimization is a constrained optimization problem. Thus, assuming f is differentiable, and the solution is interior, we can use the Lagrangian method to solve it.

The Lagrangian for this minimization problem is given by

- L(x1,x2,λ)= w1x1 + w2x2 -λ[f(x1,x2)-y]

Differentiating this function with respect to the two input variables  and  λ we get

 - w1-λ∂f(x1,x2)/∂x1 =0	 (FOC1)

 - w2-λ∂f(x1,x2)/∂x2 =0	 (FOC2)

 - [-fx1,x2-y] =0		 (FOC3)

The solution of this problem is given by a pair

- x1'=x1(w1,w2,y)   and   x2'=x2(w1,w2,y)

These functions are called the conditional input demands of the firm. The reason for the name is that we are conditioning them to get a specific level of output.

The (minimum) cost function is obtained as follows

- C(y)=w1x1(w1,w2,y) + w2x2(w1,w2,y)

**Example**: Let us assume the production function of the firm has the Cobb-Douglas specification

- f(x1,x2)=(x1)1/4(x2)1/4.

Under this specification, the problem of the cost minimizing firm is 

- minx1,x2 {w1x1+w2x2:x11/4x21/4 =y}

The Lagrangian function for this problem is given by

L(x1,x2,λ)=w1x1+w2x2-λ((x1)1/4(x2)1/4-y)

Differentiating this function with respect to the two input variables  and  λ we get

 - w1-λ1/4x1-3/4x21/4 =0	 (FOC1)

- w2-λ1/4x11/4x2-3/4 =0	 (FOC2)

- -x11/4x21/4+y =0 	  	(FOC3)

Using FOC1 and FOC2, we get

- x1=x2w2/w1.

Substituting the latter in FOC3, we get

- -x2w2/w1x21/4+y =0.

Thus, **x2' =y2(w1/w2)1/2** Proceeding in a similar way, we get **x1' =y2(w2/w1)1/2**

It follows that the cost function of the firm is given by

- C(y)=w1 y2(w2/w1)1/2 + w2 y2 (w1/w2)1/2 = 2y2(w1w2)1/2

Given this result, the problem of the profit maximizing firm can be expressed as follows

- maxy{py- 2y2(w1w2)1/2}

Differentiating the objective function with respect to y, we get 

- p-4y(w1w2)1/2 = 0

Thus, the optimal level of production is 

- y'=p/[4(w1w2)1/2] 

This is exactly the same expression we obtained in the previous section.


----------------------
## 3.3 Supply Function

We have seen that the supply function of the firm is a function that indicates the amount of the good that the firm produces ---to maximize profits--- for each pair of prices of the good and inputs. We are often interested in the relation between the level of production and the market price of the good. In these cases, we assume that the prices of the inputs remain the same and express the supply of the firm as a sole function of the price of the good

 y*=yp.

The supply function of the market combines the supply curve of each firm. It state the aggregate level of production that the firms would optimally choose for each possible price of the good under consideration. In the time horizon where the number of firms is fixed (typically called the “short run”), the market supply curve is the horizontal sum of each firm supply curve:

 

where yhp=yh* is the supply function of firm j, and H is the total number of firms currently in the market.

Example: In the previous example, the supply curve of a firm with Cobb Douglas technology fx1,x2=x11/4x21/4 was y*=p/4w1w21/2. Let us assume that the prices of the production factors are both equal to one; that is, w1=w2=1. This implies that yhp=p/4. If there are 100 identical firms in the market, then the supply curve of the market is



That is, the market supply is Qs = 25p

----------------------
## 3.4 Stay in the Market?

We can define the profit function of the firm as the amount of money that the firm makes for each combination of prices of the good and inputs, assuming that the firm selects the combination of inputs that maximizes its profits. That is, 

- PI (p,w1,w2) = max x1,x2 {pf(x1,x2) - w1x1 - w2x2 } = maxy {py- C(y)}

This function represents the maximum profits the firm can make in the market.

A competitive firm decides to stay in the market if and only if 

- PI (p,w1,w20) > 0


This is the same as to say

- p > C(y*)/y*

where C(y)/y represents the average cost function of the firm.

There are two important concepts in economics that the firm should consider while taking the stay/exit decision. These ideas are also important in many daily decisions we make. 

The first concept is the **opportunity cost**. It captures the loss of potential gain from other courses of action when one specific alternative is chosen. When the firm decides whether to stay in the market, it should consider the opportunity cost of all inputs! For instance, it should take into account the value of the working time of the owner of the firm.

The second concept is the **sunk cost**. It captures a cost that has already been incurred and cannot be recovered. When the firm decides whether to stay in the market, it should not consider the sunk costs! For instance, its decision should not be affected by the cost of evaluating the feasibility of an investment project.

In the long run, we might expect

 p=C(y*)/y* 

The reason is that, whenever p>C(y*)/y*, many firms find it attractive to enter the market. The entrance of new firms usually increases the overall level of production, pushing the price down. This process repeats till the initial condition --- p=C(y*)/y*--- is reached.





<!--

// This piece of code below creates the reveal presentation and pushes to GitHub and then deploys to GitHub pages. Modify the commit message and paste it into terminal.

cd docs && \
pandoc  \
-t revealjs -V revealjs-url=reveal.js \
--css=reveal.js/css/theme/simple.css \
-H reveal.js/js/revealMathJax.js \
-s S13_Monopoly_Ch25.md -o S13_Monopoly_Ch25.html && \
cd .. && \
git add docs/* && \
git commit -am " add content to S13_Monopoly_Ch25.md " && \
git push origin master && \
mkdocs gh-deploy 

-->