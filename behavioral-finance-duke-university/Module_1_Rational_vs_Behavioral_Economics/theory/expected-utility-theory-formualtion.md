In plain English, it says: The expected utility of a gamble is the average "happiness" (utility) you would get from every possible outcome, weighted by the likelihood of each outcome actually happening.

Let’s break it down piece by piece, step-by-step.

1. The Components
w
i
w 
i
​
  (The Outcomes): These are the specific amounts of wealth, final exit value, or payoff you will receive if a particular state of the world occurs.

p
i
p 
i
​
  (The Probabilities): This is the chance (between 0 and 1) that state 
i
i will actually happen. Crucially, all probabilities must add up to 1 (
∑
i
=
1
n
p
i
=
1
∑ 
i=1
n
​
 p 
i
​
 =1), meaning we have accounted for every possible future scenario.

U
(
w
i
)
U(w 
i
​
 ) (The Utility of the Outcome): This is the subjective "satisfaction," "happiness," or "value" you derive from having that specific amount of wealth. This is where your risk preference lives.

E
[
U
(
w
)
]
E[U(w)] (Expected Utility): This is the final "score" of the gamble. It is not the average money you expect to get; it is the average happiness you expect to feel.

2. Why do we use 
U
(
w
i
)
U(w 
i
​
 ) instead of just 
w
i
w 
i
​
 ?
If we just took the average money, we would use Expected Value: 
E
[
w
]
=
∑
p
i
⋅
w
i
E[w]=∑p 
i
​
 ⋅w 
i
​
 .

But humans are not calculators. We experience Diminishing Marginal Utility—the more wealth you have, the less additional happiness you get from each extra dollar.

To see this in action, let's use a concrete example with a coin flip gamble:

Heads (State 1): You win $100. (
w
1
=
100
w 
1
​
 =100, 
p
1
=
0.5
p 
1
​
 =0.5)

Tails (State 2): You win $0. (
w
2
=
0
w 
2
​
 =0, 
p
2
=
0.5
p 
2
​
 =0.5)

Let's assume your utility function is 
U
(
w
)
=
w
U(w)= 
w
​
  (the square root of wealth), which represents a risk-averse person.

Plugging into the formula:

E
[
U
(
w
)
]
=
(
0.5
×
100
)
+
(
0.5
×
0
)
E[U(w)]=(0.5× 
100
​
 )+(0.5× 
0
​
 )
E
[
U
(
w
)
]
=
(
0.5
×
10
)
+
(
0.5
×
0
)
=
5
E[U(w)]=(0.5×10)+(0.5×0)=5

Now, compare this to the Expected Value (average money):
E
[
w
]
=
(
0.5
×
100
)
+
(
0.5
×
0
)
=
50
E[w]=(0.5×100)+(0.5×0)=50

Notice the huge gap. The average money is $50, but the average *utility* is only 5.
Why? Because the square root function crushes the utility of the $100 win (from 100 down to 10), and heavily penalizes the $0 loss (down to 0). The risk-averse person sees this gamble as having a very low "emotional score."

3. The "Certainty Equivalent" (How to interpret the result)
What does a score of "5" actually mean in real life?
We find the Certainty Equivalent—the guaranteed amount of cash that would give you the same utility score of 5.

If 
U
(
w
)
=
w
U(w)= 
w
​
 , we solve 
w
=
5
w
​
 =5, which gives 
w
=
25
w=25.

This is the magic of the formula:
To a rational, risk-averse person, this 50/50 gamble between $100 and $0 is exactly equal in value to receiving a *guaranteed $25* in hand. They would reject a guaranteed $40 for this gamble, because the gamble's Expected Utility (5) is lower than the utility of a guaranteed $40 (
40
≈
6.32
40
​
 ≈6.32).

