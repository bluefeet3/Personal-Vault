Most of the information received from stars is through electromagnetic radiation.

[[Radiative Opacity]] is the measure of the capability of matter to absorb and scatter photons.

##### Examples of matter-radiation interactions
[[Resonance Scattering]] scatters photons through an excitation and deexcitation of the atom.
Variations of this scattering exist where higher energy photons are replaced by multiple lower energy photons.

This can also be completed with collisions with free electrons. The [[Kinetic Energy]] is transformed into [[Atomic Energy]]. Which is subsequently transformed into [[Radiative Energy]]

### Local Thermodynamic Equilibrium
The atomic energy levels and ionic populations of the plasma are determined solely by collisions.
Stars are of a high density and hence collisions are very important.

[[Mean Free Path]]

The local temperature solely depends on the thermodynamic properties of the local plasma.

##### Boltzmann Equation
The atomic energy levels of a given ion are populated inversely exponentially as a function of their energy. That is, lower energy levels are naturally more populated than higher energy levels.

The population number $n_i$ of an energy state $i =$ number of atoms per unit volume.
In thermal equilibrium, the population numbers follow a [[Boltzmann Distribution]]:$$\frac{n_i}{n_0} = \frac{g_i}{g_0}\cdot\exp\left( \frac{-\Delta E}{kT} \right)$$
where $T \approx T_{exc}\,$ excitation temperature and $k =$ [[Boltzmann Constant]], and $g_i$ is the statistical weight of level $i$.
```ad-note
The ratio of $n_i$ over $n_0$ should be expected to be always less than 1
```

```ad-note
Degeneracy of the H atom: $g = 2n^2$
```

### Saha Equation

*If collisions dominate*, the equation that regulates ionisation is called the [[Saha Equation]]: $$ \frac{n_{i+1}}{n_i} = \frac{1}{n_e}\left( \frac{2 \pi m_e kT}{h^2}\right)^{\frac{3}{2}} \frac{2 U_{i+1}}{U_i} \exp\left( -\frac{E_{ion}}{kT} \right)$$
**Where:**
$E_{ion}$ is the ionising energy...
$U$ is the partition function
(work in progress section)


The Boltzmann equation tells is about the relative populations of a given species of atom. **However,** we have not yet considered the interaction between species.

### Ionisation
How to find the fraction of H atoms which are neutral?

**First Approximation:** When the temperature rises high enough that the typical kinetic energy of atoms reaches the energy required to ionise a hydrogen atom, then the material becomes ionised.
$$T = \frac{E_{ion}}{k}$$
What happens if we consider atoms in higher excitation states?

**Partition Function**
$$U = g_1 + \sum_{i=2}^{\infty}g_i \exp{\left(\frac{-(E_i-E_1)}{kT}\right)}$$