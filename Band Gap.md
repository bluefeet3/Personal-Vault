*Learning Plan*
Starting with block theory derive the band gap. 
Outline two different Zone schemes and how they relate the presence of bands. 
Outline what tight binding theory is and how it can be applied to explain the electronic states of Carbon, Silicon and Magnesium.

### Bands
Bands define the distinction between metals, semi-metals, semiconductors and insulators.

Every solid contains electrons. We see that the electrons in crystals are arranged in energy bands.
These energy bands are separated by regions in energy for which no wavelike electron orbitals exist.

Such forbidden regions are called energy gaps or band gaps, and result from the interaction of the conduction electron waves with the ion cores of the crystal.

The crystal behaves as an **insulator** *if the allowed energy bands are either filled or empty*, for then no electrons can move in an electric field.

The crystal behaves as a **metal** *if one or more bands are partly filled*, say between 10 and 90 percent filled. 

The crystal is a **semiconductor** or a **semi-metal** *if one or two bands are slightly filled or slightly empty*.

##### Energy Levels
Isolated atoms have *precise allowed energy levels*.

Bands of allowed states are **separated by energy gaps** for which there are no allowed energy states.

The allowed states in conductors can be constructed from **combinations of free electron states** ([[Nearly Free Electron Model]]) or from **linear combinations of the states** of the isolated atoms ([[Tight Binding Model]]).

### Bloch Theory
In the free electron model, on average the wave function is almost constant over a scale of the lattice spacing.

Bloch postulated that the effect of the periodic potential would modify the electron wave-function with a periodicity of the lattice constant.

Electrons may be [[Difraction|diffracted]] or [[Scattering|scattered]] by the crystal. The electron has equal probability of scattering to the right or left and hence the **wavefunction forms a standing wave**.

##### Electron Probability Density
Physically, $\rho(+)$ corresponds to electrons pilling-up at the positive ions where the potential energy is lower than for the travelling wave - this is known as **bonding**.
$$\rho(+) = |\psi(+)|^2 \propto cos^2\left(\frac{\pi x}{a}\right)$$
**Anti-Bonding** potential higher
$$\rho(-) = |\psi(-)|^2 \propto sin^2\left(\frac{\pi x}{a}\right)$$
##### Band Gap
$$E_g = \int_0^1 dx \,U(x)\left(|\psi(+)|^2 - |\psi(-)|^2\right)$$ where $U(x) = U\cos{(2\pi x / a)}$

```ad-note
title: Reduced Zone Scheme
The diagram below displays the distribution for one atom across the lattice (Extended Zone Scheme), accounting for adjacent atoms gives the shape below for just the 1st Brillouin Zone (Reduced Zone Scheme).
Like 2d buckets filling up.
```
![[reducedZoneScheme.png]]
### Conduction
Without an electric field, the electrons exist in the ground state.

In the presence of an electric field, all electrons move. But, are scattered back toward the ground state.

If the scattering of electrons is weak then there is *continuous movement through k space*. However, there is a **group velocity** within that overall movement which makes the position of the electrons oscillate.

This is known as the [[Nearly Free Electron Model]]