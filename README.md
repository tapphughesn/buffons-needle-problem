# buffons-needle-problem

Buffon's needle problem is the following: Suppose you have a collection of needles (line segments) and you randomly drop them onto a ruled paper. What is that chance that a needle, as it comes to rest on the paper, will cross with one of the rule lines on the paper?

It turns out that the probability of the needle crossing the ruled line is

<img src="https://render.githubusercontent.com/render/math?math=\Huge \frac{2l}{\pi d}">

where *l* is the length of the needle and *d* is the distance between the ruled lines on the paper.

This formula can then be used to approximate pi by counting how many needles crossed the ruled lines.

See the [presentation slides](https://github.com/tapphughesn/buffons-needle-problem/blob/master/buffons_needle_problem_mathgems.pdf) for two proofs of this fact, and check out the [jupyter notebook](https://github.com/tapphughesn/buffons-needle-problem/blob/master/BuffonsNeedleProblem.ipynb) to see how this problem can be used to estimate pi stochastically. 
