Supplier Cost Optimization Using Portfolio Variance Minimization

Project completed as part of the Coursera Mathematics for Machine Learning courses.

Dataset

Period: January 2016 – March 2020 (51 months)

Suppliers: Two suppliers — A and B

Metric: Monthly prices (USD per item)

Size: 51 observations per supplier

Methodology
1. Portfolio Variance Minimization

This project applies a mathematical approach commonly used in finance — portfolio variance minimization — to determine the most stable mix of supplier choices. The formula used:

𝜎
𝑝
2
=
𝑤
2
𝜎
𝐴
2
+
(
1
−
𝑤
)
2
𝜎
𝐵
2
+
2
𝑤
(
1
−
𝑤
)
Cov
(
𝐴
,
𝐵
)
σ
p
2
	​

=w
2
σ
A
2
	​

+(1−w)
2
σ
B
2
	​

+2w(1−w)Cov(A,B)

Where:

𝑤
w = allocation weight of Supplier A

1
−
𝑤
1−w = allocation weight of Supplier B

2. Key Metrics Calculated

Mean price for each supplier

Variance and standard deviation

Covariance and correlation

Optimal allocation weights minimizing total volatility

Expected blended cost

Minimum achievable variance

Optimal Allocation Results
Supplier	Allocation	Expected Price	Variance
A	70.1%	$100.80	28.04
B	29.9%	$100.00	112.98
Blended	100%	$100.56	9.44
Key Findings

Supplier A:

More stable (low variance)

Slightly more expensive

Supplier B:

Lower cost

Highly volatile

Optimal Mix:

70.1% Supplier A + 29.9% Supplier B

Produces the lowest possible variance while maintaining a reasonable average cost
