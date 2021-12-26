# Symmetric Latin Square

### Description

1. Number of possible $$7\times 7$$ symmetric matrices such that each row contains numbers from $$1$$ to $$7$$ (i.e. each row contains all numbers $$1$$ to $$7$$ once).
2. In extension to that, number of possible matrices where the diagonals contain all numbers $$1$$ to $$7$$.

### Solution

It's about Latin squares, and details can be found in Wiki.

{% embed url="https://en.wikipedia.org/wiki/Latin_square" %}
Latin Square
{% endembed %}

In an $$n\times n$$ symmetric latin square, each number must occur an equal number of times above and below the diagonal. However, for odd $$n$$ this must imply that each number appears once on the diagonal. So these two questions are actually one question, and the answer is $$328320$$ from the following URL.

{% embed url="https://oeis.org/A035482" %}
Number of $$n\times n$$symmetric matrices each of whose rows is a permutation of $$1\ldots n$$.
{% endembed %}

Until now no explicit formula has been found. Maybe using code for enumeration is a good way.

