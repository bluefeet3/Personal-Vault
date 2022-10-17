Equations such as the time-independent Schrodinger Equation for a harmonic oscillator can be solved using ladder operators.$$-\frac{\hbar^2}{2m}\frac{d^2\psi}{dx^2} + \frac{1}{2}m\omega^2x^2\psi = E\psi$$
This differential equation can be solved with a power series method, but it can be also solved using ladder operators.
The equation above is equivalent to: $$\frac{1}{2m}\left[ \hat{p}^2 + (m\omega x)^2 \right] \psi = E \psi$$ where $\hat{p} = \frac{\hbar}{i}\frac{d}{dx}$

We can factorise the Hamiltonian: $$\hat{H} = \frac{1}{2m}\left[ \hat{p}^2 + (m\omega x)^2 \right]$$ for numbers $u^2 + v^2 = (iu + v)(-iu + v)$.

For operators we cannot do this as they do not generally commute. So we have to introduced two new operators, Ladder Operators.

##### Check notes

These ladder operators allow us the generate new solutions starting from one. The ladder operators allow the climbing of the energy ladder.
$a_+$ is the **raising operator** and $a_-$ the **lowering operator**.

There exists a lowest rung: $$\hat{a_-}\psi_0 = 0$$
**Ground State:**$$\frac{1}{\sqrt{2\hbar m \omega}}\left( \hbar \frac{d}{dx} +m\omega x\right)\psi_0 = 0$$
https://www.docsity.com/en/harmonic-oscillator-2-quantum-physics-and-mechanics-lecture-slides/177289/

