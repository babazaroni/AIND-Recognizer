[Notation in probability and statistics](https://en.wikipedia.org/wiki/Notation_in_probability_and_statistics)

[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

[List of Logic Symbols](https://en.wikipedia.org/wiki/List_of_logic_symbols)

and &and; or &or; not &not; implies &rarr; &rArr; independent &perp;

conditioned on |

&sum;


is equivilent &harr;

## Probabilities

### Basic

Conditional probabilites: use | as in P(X|Y).  P(X|Y) = P(X,Y)/P(Y)

Joint Probabilites: use ,  as in P(X,Y)

complementary probability P(A) = p &rArr; P(&not;A) = 1 - p

independence X &perp; Y : Product of Marginals P(x)P(Y) = joint probability P(X,Y) 

dependence P(X<sub>2</sub> = Heads | X<sub>1</sub> = Heads) probability X<sub>2</sub> is heads given X<sub>1</sub> is heads

total probability P(Y) = &sum; P(Y|X = *i*)P(X = *i*)  Allows one to deduce a probability if you know all the other probabilities.

P(&not;X|Y) = 1 - P(X|Y)

### Bayes Rule

P(X|Y) = P(Y|X) * P(X)/P(Y) or  Posterior =  Likelyhood * Prior / Marginal Likelyhood

P(X|Y,Z) = P(Y|X,Z) * P(X|Z)/P(X|Z) [Multiple conditions](https://math.stackexchange.com/questions/408774/bayes-rule-with-multiple-conditions)

P(B) often expanded to &sum; P(B|A=a)P(A=a) for all a (Total Probability)

Confounding

Explaining away

### Inference

Nodes can be either Evidence, Hidden, Query

inference by Enumeration

Speed up Enumeration by pulling out terms, variable elimination

