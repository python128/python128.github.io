<script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>

#### Q1. A metal ring of mass M and radius R is set rotating about an exis going through the diameter. The experiment is conducted in space at an infinite distance. Its angualar velocity is $$\omega$$. Find tension as a function on angle $$\theta$$ from horizontal.
Solution: 
Let tension be T.
Free Body diagram for elementary section of ring.

Force balance along vertical,

$$(T+dT) cos(\theta + d \theta) = T cos \theta\tag1$$ 

Centripetal force acting inwards along horizontal,

$$(T+dT)cos(\theta + d \theta) - T sin \theta = dm(r)(\omega^2)\tag2$$

Simplifying (1),

$$Tsin\theta d \theta = dT cos \theta\tag1$$

Simplifying (2),

$$Tcos\theta d \theta + dT sin \theta = \frac{MR\omega^2}{2\pi} cos \theta d \theta \tag2$$

Let  $$T_0 = \frac{MR\omega^2}{2\pi}$$

Substituting (1) in (2), we get

$$cos \theta (dT cot \theta) + dT sin \theta = T_0 cos \theta d \theta$$

$$dT = T_0 sin \theta cos \theta d \theta$$

Integrating,

$$\int_{T_0}^{T} dT = \frac{T_0}{2} \int_{0}^{\theta} sin 2\theta d\theta$$

$$T = T_0\left( 1 + \frac{1}{2} sin^2 \theta \right)$$

$$\therefore T = \frac{MR\omega^2}{2\pi}\left(1 + \frac{1}{2}sin^2 \theta \right)$$
