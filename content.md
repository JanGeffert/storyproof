# My favorite story proof
[Stat 110](https://projects.iq.harvard.edu/stat110) is the best class I have taken at Harvard.
Joe Blitzstein taught me about Poisson approximations, Beta distributions, and conditional probabiliy. But most importantly he taught me how to think – giving me strategies for how to think about a problem.
Trying simple and extreme cases, drawing a picture, recognizing the underlying structure of a problem (symmetry, for instance).

One of my favorite techniques were **story proofs**. A story proof is an alternate way of proving a mathematical statement, that does not go through arithmetic acrobatics, but instead tries to find a more intuitive, yet general, *story* behind a statement.
Consider

\frac{(2n)!}{2^n \times n!} = (2n-1)(2n-3)...3.1

Let's try to prove that what is on the left-hand side of the equation is equal to the right-hand side. We could try do do arithmetic, using algebra and equivalence operations to change both sides of the equation until we end up with the same on each side. That will work. It will show us that the two expressions are equivalent. It will also not help us understand anything. It is a mindless exercise. Isn't there away we can get an intuitive understanding of what is going on? Enter story proofs.

Let's find a story to describe the expressions on both sides. Assume that there are 2n people in a dance. To dance, two people have to find each other and form a pair. Assuming that everybody can dance, how many different settings of pairs can we create?

One way to do it, is to line up every one in a row. Then we say that the first two are a pair, and the second two are a pair and so on. How many such pairs exists?

How many ways are there to put 2n people in a row? The first position can be filled by 2n people, the second by (2n-1), the third by (2n-2), down until the last spot which the last person will have to fill. Mathematically, we can express this as (2n)!.

This, however, is not the answer to our original question. After all, it doesn't make a difference, whether the first pair is (Partner 1, Partner 2) or (Partner 2, Partner 1). It is the same pair! Therefore, there are half as many combinations 
