*Learning plan*
What are intrinsic semiconductors? 
Outline the properties of hole particles. 
Show an expression for the Law of mass action (carrier concentration) and that the Fermi level must fall at the centre of the band gap. 
Calculate carrier concentrations and occupancy probabilities.

# Intrinsic Semiconductors
Semiconductors are intermediate [[Band Gap]] materials which may conduct due to [[Thermal Excitation]] of electrons.
![[Pasted image 20221010121434.png|400]]

An **intrinsic** semiconductor is a semiconductor material in its pure form.

## Thermal Excitation in Semiconductors
As the number of conduction electrons increases with temperature, the **resistance decreases** with increasing temperature (unlike metals).

As an electron is excited to a higher state, a [[Holes|hole]] is left behind.
![[Holes]]

## Fermi Distribution in Intrinsic Semiconductors
In intrinsic semiconductors the carrier density is derived from the Fermi distribution to be as follows:$$n_i^2 = N_V N_C \exp{\left(\frac{-E_g}{kT}\right)}$$where $N_V$, $N_C$ are the valence and conduction band concentrations at the bottom of the conduction band and the top of the valence band under conditions of full occupancy. $E_g$ is the band gap energy.

~ Slide 171

$$E_F = \frac{1}{2}(E_C+E_V) + \frac{1}{2}kT\ln{\left(\frac{N_V}{N_C}\right)}$$

![[valenceToConductionBand.png|400]]

# Extrinsic Semiconductors
*Learning Plan*
What are extrinsic semiconductors and where is the Fermi energy for these systems?
PN junctions and the effect of forward and reverse bias.
Outline the Shockley or ideal diode equation which is a fundamental characteristic of PN-junctions.

Introduction of a small concentration of *shallow level impurities* such as Boron and Phosphorus on the electronic structure of Silicon. As Phosphorus has **one more valence electron** per atom than Silicon.

The extra electron ends up in a *localised shallow electronic state* just below the conduction band edge. These states are called [[Donor States]].

For temperatures greater than 100 K, the energy required to *ionise* the phosphorus atom is small in comparison to the **band gap**. Effectively, all of the substituted phosphorus atoms are ionised.

In general for silicon, *Group V* elements act as **donor impurities** as the contribute additional electrons to the conduction band.
*Group III* elements act as [[Acceptor States|acceptor]] impurities as they trap electrons from the valence band generating [[Holes]].

```ad-note
title: Conventionally
*Conventionally*, a semiconductor crystal with donor impurities is said to be **n-Type**, as there is an excess concentration of negatively charged carriers. (Electrons in the conduction band)

*In contrast*, a semiconductor crystal with acceptor impurities is said to be **p-Type**, as there is an excess concentration of positively charged carriers. (Holes in the valence band)
```

## Fermi Distribution in Extrinsic Semiconductors
In extrinsic semiconductors, the carrier density is defined for either an n type or p type semiconductor.$$n_{n} = \frac{1}{2}\left[N_D - N_A + \sqrt{(N_D-N_A)^2 + 4n_i^2}\right]$$and $$n_{p} = \frac{1}{2}\left[N_A - N_D + \sqrt{(N_A-N_D)^2 + 4n_i^2}\right]$$

## Mobility
The mobility is the magnitude of the drift velocity of a charge carrier per unit electric field.$$\mu = \frac{|v|}{E}$$
The electrical conductivity is the sum of the electron and hole contributions: $$\sigma = (ne\mu_e + pe\mu_h)$$ where n and p are the concentrations of electrons and holes.

### Temperature
Ionised impurity scattering: $$\mu_i \propto T^\frac{3}{2}$$
Acoustic phonon scattering:

