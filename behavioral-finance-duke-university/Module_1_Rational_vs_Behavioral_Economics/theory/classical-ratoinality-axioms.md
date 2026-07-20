Topic 1: Classical Rationality Axioms
Before we can talk about irrationality, we must formalize what rationality means in the economic sense. In the 1940s, von Neumann and Morgenstern proposed that a rational decision-maker's preferences over uncertain outcomes must obey five axioms. If they do, we can represent those preferences with a utility function 
U
(
x
)
U(x), such that the agent acts to maximize expected utility.

Here are the five axioms, expressed using our preference notation:
A
⪰
B
A⪰B means "A is weakly preferred to B" (i.e., you like A at least as much as B).
A
≻
B
A≻B means "A is strictly preferred to B."
A
∼
B
A∼B means "you are indifferent between A and B."

Completeness: For any two lotteries 
A
A and 
B
B, either 
A
⪰
B
A⪰B, or 
B
⪰
A
B⪰A, or both (indifference). Intuition: You can always make up your mind; no "undecidable" pairs exist.

Transitivity: For any three lotteries 
A
,
B
,
C
A,B,C, if 
A
⪰
B
A⪰B and 
B
⪰
C
B⪰C, then 
A
⪰
C
A⪰C. Intuition: Your preferences are internally consistent and loop-free.

Non-Satiation (Monotonicity): More wealth is strictly preferred to less wealth. If lottery 
A
A yields a higher payoff than 
B
B in every possible state, then 
A
≻
B
A≻B. Intuition: More is always better.

Continuity: For any three lotteries 
A
⪰
B
⪰
C
A⪰B⪰C, there exists some probability 
p
∈
[
0
,
1
]
p∈[0,1] such that the agent is indifferent between 
B
B and a gamble that yields 
A
A with probability 
p
p and 
C
C with probability 
1
−
p
1−p. Intuition: Preferences are "smooth"—no infinite jumps in utility occur over tiny probability changes.

Independence (or Substitution): For any three lotteries 
A
,
B
,
C
A,B,C, 
A
⪰
B
A⪰B if and only if the mixed lottery 
p
A
+
(
1
−
p
)
C
⪰
p
B
+
(
1
−
p
)
C
pA+(1−p)C⪰pB+(1−p)C. Intuition: Our preference between 
A
A and 
B
B should be independent of any common "background" lottery 
C
C that is mixed in with the same probability. It ensures we evaluate the core gamble in isolation.

The "Money Pump" Argument

Now, let us stress-test these axioms with a very practical lens—because this is where you, as a PE/VC professional, will encounter the arbitrageurs of human behavior.

Suppose a General Partner (GP) exhibits cyclic preferences, a direct violation of Transitivity. Imagine:

Deal 
X
≻
Y
X≻Y (they prefer investing in AI infrastructure over SaaS)

Deal 
Y
≻
Z
Y≻Z (they prefer SaaS over climate tech)

But, irrationally, 
Z
≻
X
Z≻X (they prefer climate tech over AI infrastructure)

This is a cycle. Why is this financially catastrophic? Because a clever second-party (say, an LP or a co-investor) can construct a "Money Pump."

They start by giving the GP asset 
X
X. The GP prefers 
Z
Z over 
X
X, so they pay a small fee to swap 
X
X for 
Z
Z. Then, since 
Y
≻
Z
Y≻Z, they pay another fee to swap 
Z
Z for 
Y
Y. Then, since 
X
≻
Y
X≻Y, they pay yet another fee to swap 
Y
Y back to 
X
X. The GP is now back at their original asset 
X
X, but has paid repeated transaction costs (or conceded economic value) each cycle. Without transitivity, an arbitrageur can drain the GP's capital in an infinite loop. The "Money Pump" proves that intransitivity is not just a logical quirk—it is a direct path to capital destruction.

These axioms are not just academic fluff. They allow us to prove the existence of a utility function 
U
(
x
)
U(x) that represents these preferences. Once we have 
U
(
x
)
U(x), we can differentiate it, measure curvature, and—as we will see in later modules—quantify exactly how much risk premium a PE investor should demand for a volatile cash flow.

