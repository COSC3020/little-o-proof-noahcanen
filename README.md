# Little-o

In addition to the big-O, big-$\Omega$, and big-$\Theta$ notation that
we covered at the beginning of this class, a few other notations are sometimes
used in asymptotic analysis.  For example, "little-$o$" notation.

Prove (i.e.\ give a formal mathematical proof) that $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.

Hint: The proof will be *very* short and *very* easy. You can start by
identifying the differences between the definitions of O and o.

I have started with the formal definition of $o$ below. Add your answer to this
markdown file. [This
page](https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/writing-mathematical-expressions)
might help with the notation for mathematical expressions.

$f(n)\in o(g(n)) \iff \forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$

$f(n)\in O(g(n)) \iff \exists c>0, \exists n_0, \forall n\ge n_0: f(n) <= c g(n)$

if $f(n)\in o(g(n))$ implies that $f(n)\in O(g(n))$.

then $\forall c>0, \exists n_0, \forall n\ge n_0: f(n) < c g(n)$ implies that $\exists c>0, \exists n_0, \forall n\ge n_0: f(n) <= c g(n)$

$f(n) < c g(n)$ implies that $f(n) <= c g(n)$ By the law of transitivity

$\forall c>0, \exists n_0, \forall n\ge n_0& implies that $\exists c>0, \exists n_0, \forall n\ge n_0$ 

so $f(n)\in o(g(n))$ implies
that $f(n)\in O(g(n))$.  is true


For this assignment, I was able to do it entirely on my own with a little help from https://www.stat.cmu.edu/~cshalizi/uADA/13/lectures/app-b.pdf on o and https://www.geeksforgeeks.org/analysis-algorithms-big-o-analysis/ no O.

"I certify that I have listed all sources used to complete this exercise, including the use of any Large Language Models. All of the work is my own, except where stated otherwise. I am aware that plagiarism carries severe penalties and that if plagiarism is suspected, charges may be filed against me without prior notice."

