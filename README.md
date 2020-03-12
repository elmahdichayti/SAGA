# SAGA
A reproduction of the article "SAGA: A fast Incremental Gradient Method With Support for
Non-Strongly Convex Composite Objectives, by Aaron Defazio, Francis Bach, Simon Lacoste-Julien" during a course given by Francis BACH at university paris sud. 
The article can be found in ArXiv here https://arxiv.org/abs/1407.0202


In the article, a new (at the time) stochastic algorithm namely SAGA is introduced. This algorithm can be seen
as an extension of the SAG (stochastic average gradient) and SVRG (stochastic variance reduced gradients).
SAGA is shown to have better theoretical results than the before mentioned algorithms, it supports non-
differentiable objectives through the use of the proximal operator. SAGA takes advantage of any inherent
strong convexity and applies directly to non-strongly convex cases.
