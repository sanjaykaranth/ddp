ddp
===

DDP - change-point analysis based skill discovery

One-sample Kolmogorov–Smirnov statistic 
The empirical distribution function Fn for n independent and identically distributed (i.i.d.) ordered observations Xi is defined as

F
n
(
x
)
=
number of (elements in the sample
≤
x
)
n
=
1
n
∑
i
=
1
n
1
(
−
∞
,
x
]
(
X
i
)
,
{\displaystyle F_{n}(x)={\frac {{\text{number of (elements in the sample}}\leq x)}{n}}={\frac {1}{n}}\sum _{i=1}^{n}1_{(-\infty ,x]}(X_{i}),}
where 
1
(
−
∞
,
x
]
(
X
i
)
{\displaystyle 1_{(-\infty ,x]}(X_{i})} is the indicator function, equal to 1 if 
X
i
≤
x
X_{i}\leq x and equal to 0 otherwise.
The Kolmogorov–Smirnov statistic for a given cumulative distribution function F(x) is

D
n
=
sup
x
|
F
n
(
x
)
−
F
(
x
)
|
D_{n}=\sup _{x}|F_{n}(x)-F(x)|
where supx is the supremum of the set of distances. Intuitively, the statistic takes the largest absolute difference between the two distribution functions across all x values.

By the Glivenko–Cantelli theorem, if the sample comes from distribution F(x), then Dn converges to 0 almost surely in the limit when 
n
n goes to infinity. Kolmogorov strengthened this result, by effectively providing the rate of this convergence (see Kolmogorov distribution). Donsker's theorem provides a yet stronger result.

In practice, the statistic requires a relatively large number of data points (in comparison to other goodness of fit criteria such as the Anderson–Darling test statistic) to properly reject the null hypothesis.
