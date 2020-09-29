---
layout: homepage
---

<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

# The geometry of complex differentiability *(9/6/2020)*

Complex differentiability is usually viewed as an *analytic* property of functions.  But this perspective suggests we might look for a *geometric* characterization.  Take a function $$f(z)=u(z)+iv(z)$$ with real-valued $$u,v$$.  Now we can define the partial derivatives of $$u$$ and $$v$$ with respect to $$x=\Re(z)$$ and $$y=\Im(z)$$.  

Where $$f$$ is complex differentiable, it is straightforward to derive the celebrated Cauchy-Riemann equations $$u_x=v_y$$ and $$u_y=-v_u$$.  We can use these relations to manipulate the complex differential 
<center>$$df:=\begin{pmatrix}u_x & u_y \\ v_x & v_y\end{pmatrix}\stackrel{CauRie}{=}\begin{pmatrix}u_x & u_y \\ -u_y & u_x\end{pmatrix}\stackrel{LinAlg}{=}u_x\begin{pmatrix}1 & 0 \\ 0 & 1\end{pmatrix}+u_y\begin{pmatrix}0 & 1 \\ -1 & 0\end{pmatrix}.$$</center>
<br>
Thus the pushforward of a vector in the tangent space to a complex differentiable point of $$f$$ is the weighted sum of a scaling and a rotation by $$\pi/2$$.  So the differential is a conformal map --- angles are preserved.

In fact, this characterization is essentially sufficient.  For if $$df$$ is a conformal map, we have that it is a weighted sum of a  we can derive the Cauchy-Riemann equations by working in reverse, and we're done.


This post results from a discussion I had with <a href="https://people.math.umass.edu/~markman/" target="_blank">Eyal Markman</a> following a lecture on complex analysis. 
