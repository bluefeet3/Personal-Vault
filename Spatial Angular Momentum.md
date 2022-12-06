The stationary states of the hydrogen atom are labelled by 3 quantum numbers.

We have seen that the energy of the state depends on n. The other two quantum numbers $l$ and $m$ are **related to the orbital angular momentum**.

**Classically:** $L = r \times p$

This can simply be substituted with the quantum mechanical momentum. $P_x = \frac{\hbar}{i}\frac{\delta}{\delta x}$

## Eigenvalues
##### Commutation Relations
The commutator for $L_x$ and $L_y$ is: $$\left[ L_x, L_y \right] = i\hbar L_z$$ which follows cyclic permutation for $[L_y, L_z] \propto L_x$ and $[L_z, L_x] \propto L_y$

Which are the fundamental commutation relations for angular momentum.

By the [[The Uncertainty Principle|generalised uncertainty principle]], there are no states that are simultaneously eigenfunctions of $L_x$ and $L_y$.

The aim is to find eigenfunctions simultaneously of both $L^2$ and $L_z$: $$L^2f = \lambda f \,\text{and}\, L_zf = \mu f$$
With [[Ladder Operators]]:$$L_\pm \equiv L_x \pm iL_y$$
We find that $L_z(L_\pm f) = (\mu \pm \hbar)(L_\pm f)$, showing that $L_\pm$ is an eigenfunction of $L_z$ with eigenvalue $\mu \pm \hbar$. Hence, $L_+$ is the **raising operator** and $L_-$ the **lowering operator**, they increase and decrease the eigenvalue of $L_z$ by one unit of $\hbar$.
(Chapter 7, slide 7)

At the bottom of the ladder: $L_- f_b = 0$ hence the eigenvalue for $L_z$ at the base of the ladder as: $$L_z f_b = \hbar \bar{l}f_b$$ with $\bar{l} = -l$
$$l = \frac{N}{2}$$
The eigenfunctions are characterised by the numbers l and m.
$$L^2 f^m_l = \hbar l (l+1)f^m_l$$$$L_z f^m_l = \hbar m f^m_l$$
$$\vec{J} = \vec{L} + \vec{S}$$
