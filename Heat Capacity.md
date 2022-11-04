*Learning Plan*
How to define heat capacity.
Outline and derive the Einstein Model.
Outline and derive the Debye model.

# Heat Capacity
### Lattice Vibrations
The concept of [[Temperature]] and [[Thermal Equilibrium]] are based on the idea that the individual particles in a system have some form of motion.

### Heat Capacity
[[Heat Capacity]] is defined as how much heat (energy) it takes the raise the temperature of an object by a certain amount.

There are two main models of heat capacity:
**Dulong-Petit Model**
- Classical: Atoms behave as if on springs, vibrating independently on a lattice.

**Einstein Model**
- Quantum Mechanics: Atoms still vibrate independently on a lattice, but the frequency of vibration is *quantised*.

### Dulong-Petit Law
Assumes that:
- Atoms act independently of each other
- Classical mechanics fails at low temperature

The [[Specific Heat Capacity (C)]] is the amount of energy required to raise the temperature of 1 kg of a substance by 1 K:
$$C = \frac{C_{molar}}{M_{molar}} = \frac{3 N_A k_B}{M_{molar}} = \frac{3 R}{M_{molar}}$$
This model works reasonably well at temperatures close to room temperature and with heavier elements, however it is a very poor fit at low temperatures.

## [[Einstein Model of Heat Capacity|The Einstein Model]] (1907)
The Duling-Petit model is an oversimplification due to its assumptions.

In 1907 Einstein proposed that a quantum description was needed to fully explain the temperature dependence.

In the Einstein model, the energy is **quantised**:
$$E = \left(n +\frac{1}{2}\right) \hbar \omega$$
### Implications
Vibrational energy is quantised and therefore, **heat is quantised**.

The minimum energy of the system is not zero. Even at 0 K, the system has energy.
Thermal energies are measured from above this base-point.

#### Heat Capacity
$$C = \frac{\partial E}{\partial T}$$
$$C_V(T) = \frac{3 R \left( \frac{\theta_E}{T} \right)^2 e^{\theta_E/T}}{(e^{\theta_E/T}-1)^2}$$
where Einstein temperature: $\theta_E = \frac{\hbar \omega}{k}$

### Temperature Limits
When the Einstein temperature is low: $\frac{\theta_E}{T} \ll  1$
$$C_V(T) \approx 3R$$

When the Einstein temperature is high: $\frac{\theta_E}{T} \gg  1$
$$C_V(T) \approx 3R \left(\frac{\theta_E}{T}\right)^2 e^{-\theta_E / T}$$
```ad-failure
title: Accuracy
Although the Einstein model is more accurate, it still breaks down for mid range temperatures as it still makes the assumption that atoms on the lattice vibrate independently of eachother, which is not true
```

## Is the Einstein Model correct?
At low temperature, the heat capacity is found to have acubic temperature dependence (not exponential)

The model assumes that atoms act independently, however, atoms act collectively.

**Debye** put forward a model to account for collective motion.

## [[Debye Model of Heat Capacity|The Debye Model]] (1912)
##### Debye's Model of a solid:
- 3N normal modes of oscillations
- Spectrum of frequencies from $\omega = 0$ to $\omega_{\text{max}}$
- Treat solids as a continuous elastic medium

This changes the expression for $C_V$ because each mode of oscillation contributes a frequency-dependent heat capacity. $$C_V(T) = \int_0^{\omega_{\text{max}}} N(\omega)\,C_E(\omega, T)\,d\omega$$ where $N(\omega)$ is the number of oscillators per unit $\omega$ and $C_E$ is the Einstein function for one oscillator.

In essence, the Debye model is similar to the Einstein model with one key difference.
The energy of the system is the [[Phonon Energy]] times the average number of phonons times the **number of modes**.

Modes with low $\omega$ will be *excited at low temperatures*, contributing to the heat capacity. Therefore, the heat capacity varies less at low T compared to the Einstein model.

### Debye Frequency
For any one wavelength of oscillation, there are shorter wavelength oscillations that will also have atoms in the same position on the lattice.