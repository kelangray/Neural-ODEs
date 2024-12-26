# Neural-ODEs

Neural ODEs leverage Ordinary Differential Equations to develop new deep learning architectures. They learn dynamics of the form:

$$
\frac{dX(t)}{dt} = f_\theta(X(t), t), \quad X(0) = x,
$$

where $f_\theta$ is some neural network and $x \in \mathbb{R}^n$ is some data. The final prediction is then taken to be $X(1)$.
<div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
  <div style="flex: 0; padding-left: 10px;">
    <img src="classification_problem.gif" alt="Scatter Animation" width="50%">
  </div>
</div>
