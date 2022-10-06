Proper calculation of radiative transfer is quite complicated.

This is just the fundamental equation of radiative transfer.

### Fundamental equation of radiative transfer

![[equationOfRadiativeTransfer.png|400]] 

There exists some radiation passing through a surface element dA.

Some of the radiation will leave the surface within a solid angle d$\omega$.

$\theta$ is the angle between between d$\omega$ and the surface normal.

$dE_\nu = I_\nu \cos{\theta} \,dA \,d\nu \,d\omega \,dt$  

The coefficient $I_\nu$ is the intensity at a specific frequency.

```ad-note
title: What is the Solid Angle ($d\omega$)
The solid angle element is equal to a surface element on a unit sphere.

It is adimensional.
```

The problem is simplified by *assuming a cylinder* => $\cos{\theta} = 1$

The **total energy** is the energy emitted less the energy absorbed.
The absorbed energy: $$dE_{\text{abs}} = \alpha_\nu I_\nu \, dr\, dA \, d\nu \, d\omega \, dt$$ where $\alpha_\nu$ is the *absorption coefficient* or [[Radiative Opacity|opacity]] at frequency $\nu$.

**Emission coefficient:** $$[j_\nu] = [W \, m^{-3} \, Hz^{-1} sterad^{-1}]$$
$$dE_{\text{em}} = j_\nu I_\nu \, dr\, dA \, d\nu \, d\omega \, dt$$

**Total Energy:** $$dE_\nu = dI_\nu \,dA\,d\nu\,d\omega\,dt$$ where $dI_\nu = j_\nu dr - \alpha I_\nu dr$

$$=> \frac{dI_\nu}{\alpha_\nu dr} = \frac{j_\nu}{\alpha_\nu} - I_\nu$$ which introduces a **source function**: $S_\nu = j_\nu/\alpha_\nu$

We define the [[Optical Thickness]] $\tau$ at frequency $\nu$: $$d\tau_\nu = \alpha_\nu dr$$$$\frac{dI_\nu}{dT_\nu} = S_\nu - I_\nu$$
### Basic Equation of Radiative Transfer:
$$\frac{dI_\nu}{dT_\nu} = S_\nu - I_\nu$$
Hence, if $I_\nu < S_\nu$ then the intensity tends to increase in the direction of propagation.

If $I_\nu > S_\nu$ then the intensity tends to decrease in the direction if propagation.

**In equilibrium** the emitted and absorbed energies are equal:$$I_\nu = \frac{j_\nu}{\alpha_\nu} = S_\nu$$ Hence, $\frac{dI_\nu}{d\tau_\nu} = 0$ (Because the intensity is constant)

In **thermodynamic equilibrium** the radiation of the medium is blackbody radiation: $$S_\nu = B_\nu(T) = \frac{2h\nu^3}{c^2}\frac{1}{\exp{(\frac{h\nu}{kT}}) - 1}$$
##### Formal Solution of the radiative transfer equation is:
$$I_\nu(\tau_\nu) = I_\nu(0)e^{-\tau_\nu} + \int_0^{\tau_\nu} e^{-(\tau_\nu - t) }S_\nu(t)dt$$
The first part represents the intensity of the background radiation coming through the medium and decaying exponentially in the medium.

The second part gives the emission in the medium.

*This is a formal solution as $S_\nu(t)$ is unknown and cannot be solved*

**Assuming S is constant $S_\nu(\tau_\nu)$ in the cloud and the background radiation is ignored:**
$$I_\nu(\tau_\nu) = S_\nu \int_0^{\tau_\nu}e^{-(\tau_\nu - t) }dt = S_\nu(1-e^{-\tau_\nu})$$
If $\tau >> 1$ , the cloud is optically thick: $$I_\nu = S_\nu$$The emission and absorption processes are in equilibrium

##### Important Sources of Opacity in Stellar Plasma
Electron scattering: Lots of free electrons in stellar plasma.

Opacity due to atomic lines ([[Bound-Bound Transitions|bound-bound]]) is very important to study stellar spectrum.

Opacity due to molecules on the surface of cool stars.

Opacity due to photoionisations.
