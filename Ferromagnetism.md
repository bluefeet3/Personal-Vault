*Learning plan*
Outline ferromagnetism and the exchange field, temperature dependence of magnetisation and susceptibility.
Outline hysteresis.

# What is a ferromagnet?
Ferromagnetism is the phenomenon of **spontaneous magnetisation**, the magnetisation exists in the ferromagnetic material in the absence of an applied magnetic field.

Examples of ferromagnets are the [[Transition Metals]], Fe, Co, and Ni. Some [[Rare-Earth Metals]] can become ferromagnetic under suitable circumstances.

Ferromagnetism involves the alignment of a large fraction of the molecular [[Magnetic Moment|magnetic moments]] in a favourable direction in the crystal.

It only occurs below a certain temperature, known as the **Ferromagnetic Transition Temperature** or [[Curie Temperature]]. Note this temperature is *material dependent*

# Exchange Interactions
Thermal energy can be used to overcome exchange interactions. The **Curie Temperature** is a measure of the **Exchange Interaction Strength**. These exchange interactions are much stronger than dipole-dipole interactions.

The exchange interaction is a direct consequence of the [[Pauli Exclusion Principle]] and the [[Coulomb Interaction]] between **electrons**. Consider a system of two electrons. There are two possible arrangements for the [[Spin]] of the electrons, **parallel or anti-parallel**. If parallel, the exclusion principle requires that the electrons remain far apart, however, if anti-parallel, the electrons can exist closer and even have their wave functions overlap.

These two arrangements have **different energies** as the *energy increases with shorter separation* due to the Coulomb interaction. We can see that the [[Electrostatic Energy]] of an **electron system** depends on the *relative orientation of the spins*, the difference in energy defines the exchange energy.

The exchange interaction is **short ranged**, therefore, only the nearest neighbour atoms are responsible for producing the **molecular field**.

# Curie-Weiss Law
Higher than the Curie temperature, the *moments are oriented randomly*, resulting in a **zero net magnetisation**. In this region, the substance is paramagnetic, and its [[Magnetic Susceptibility]] is given by: $$\chi = \frac{C}{T-T_C}$$where $C$ is the [[Curie Constant]] and $T_C$ is the [[Curie Temperature]]. This is known as the [[Curie-Weiss Law]].

## Susceptibility close to $T_c$
The Curie-Weiss law describes well the observed susceptibility variation in the [[Paramagnetism|paramagnetic region]] *above the Curie Temperature*.

Around the vicinity of the Curie Temperature, a notable deviation is observed. This is due to the fact that *strong fluctuations of the magnetic moments* close to the **phase transition** temperature cannot be described by the [[Mean Field Theory]] used to derive the Curie-Weiss law. At temperatures close to $T_C$, the following is  more accurate.$$\chi \propto \frac{C}{(T-T_C)^{1.33}}$$


# Hysteresis Loop
If we apply a magnetic field to a previously demagnetised ferromagnetic substance its *magnetisation will gradually increase*. The magnetisation increases *relatively fast at first, then slows down* until it reaches a constant value at a point. At this point the substance is **saturated**. 

This curve is the **initial magnetisation curve**. The saturation magnetisation, $M_s$, is equal to the spontaneous magnetisation.

If the magnetic field is now decreased, the *magnetisation does not retrace the initial magnetisation curve*. It decreases more slowly, and when the magnetic field reaches zero, the magnetisation is still non-zero, $M_r$. This is the largest magnetisation possible under zero field. It is called the [[Remnant Magnetisation]] or **remanence**.

To decrease the magnetisation further, we must apply a field in the **opposite direction**. When the reverse field is sufficiently large, the magnetisation passes through zero. The reverse field required to bring the magnetisation to zero from remanence is called the **coercive field** or **coercivity**, $B_C$. Increasing the reverse field further further increases the magnetisation in the reverse direction until it also reaches saturation.

If we continue to change the field between large values in opposite directions, the magnetisation will vary repeatedly along the closed loop. This loop is called the [[Hysteresis Loop]].

![[Pasted image 20221206182236.png|500]]

## Magnetic Domains
Within each domain the magnetisation is uniform and equal to the spontaneous magnetisation. *Different domains are magnetised in different directions*.
The average magnetisation of this sample will not be equal to the spontaneous magnetisation.

Ferromagnetic materials are subdivided into domains rather than being uniformly magnetised. We know a system will always be in a *state which minimises energy* and therefore, we must explain why a subdivided state has a smaller energy than a uniformly magnetised state.
There are **four types** of energy which contribute to the total energy of the material.

## Exchange Energy
The [[Exchange Energy]] is responsible for ferromagnetism in magnetic materials. The exchange coupling between nearest neighbours is significant and results in parallel alignment.

### The Exchange Field
Slide 342 [[Condensed Matter Physics Lecture Notes.pdf]]
$$J = \frac{3k_BT_C}{2z\,S(S+1)}$$

## Domain Walls
In order to complete the picture about domain structures, we must consider the **boundary** between neighbouring domains. The width of the domain wall is qualitatively determined by the *balance between the exchange energy and the anisotropy energy*.

If the exchange energy is very strong and the [[Anisotropy Energy]] is small, we can expect that the width of the domain wall is large. In the case when the exchange energy is small and the anisotropy is big then the width of the domain wall should be small.