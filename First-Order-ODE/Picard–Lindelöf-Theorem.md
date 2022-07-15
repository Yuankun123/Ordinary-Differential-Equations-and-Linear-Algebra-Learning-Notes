## Picard–Lindelöf Theorem

### Theorem

If $D $ is an open subset of ${\mathbb{R} \times \mathbb{R}} $, $f: D \rightarrow \mathbb{R}$ is continuous in x and Lipschitz continuous in y, and $y'(x) = f(x, y)$ is an explicit first order ODE,

then, $\forall (x_{0}, y_{0}) \in D$, the initial value problem $y(x_{0}) = y_{0}$ must have a unique local solution.

##### Notes:

* Compared to the Peano Theorem, this theorem assumes more and concludes more. It requires Lipschitz continuity of $f $ in $y $ within $D $, and it guarantees uniqueness.
* By saying that $f $ is Lipschitz continuous in $y $ within $D $, we mean that $f $ is not only continuous but also subjected to the following condition: there is a finite number $K $ such that $\forall (x, y_{1}),\,(x, y_{2}) \in D,\:|f(x,y_{2}) - f(x, y_{1})| < K$. (Intuitively, this means that the rate of change of $f $ with respect to $y $ in bounded. This is a weaker condition than ${\partial f \over \partial y}$ is continuous.)

