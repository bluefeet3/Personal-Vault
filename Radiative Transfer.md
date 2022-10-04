Proper calculation of radiative transfer is quite complicated.

This is just the fundamental equation of radiative transfer.

### Fundamental equation of radiative transfer

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
The absorbed energy: $$dE_{\text{abs}} = \alpha_\nu I_\nu \, dr\, dA \, d\nu \, d\omega \, dt$$ where $\alpha_\nu$ is the absorption coefficient or [[Radiative Opacity|opacity]] at frequency $\nu$.

##### Important Sources of Opacity in Stellar Plasma
Electron scattering: Lots of free electrons in stellar plasma.

Opacity due to atomic lines ([[Bound-Bound Transitions|bound-bound]]) is very important to study stellar spectrum.

Opacity due to molecules on the surface of cool stars.

Opacity due to photoionisations.