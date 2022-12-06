## Question A
### (a) Outline the effect of temperature on intrinsic and extrinsic semiconductors with respect to carrier density. In your answer use diagrams where required.

In intrinsic semiconductors, the carrier density is derived from the Fermi distribution to be as follows:$$n_i^2 = N_V N_C \exp{\left(\frac{-E_g}{kT}\right)}$$and hence the carrier density of an intrinsic semiconductor has a temperature dependence of: $$n_i \propto \sqrt{\exp{\left(\frac{1}{T}\right)}}$$
The same proportionality holds for extrinsic semiconductors as their carrier density is proportional to $n_i$, however the concentrations of acceptor and donor impurities also affect the carrier density by the following equations:$$n_{n} = \frac{1}{2}\left[N_D - N_A + \sqrt{(N_D-N_A)^2 + 4n_i^2}\right]$$and $$n_{p} = \frac{1}{2}\left[N_A - N_D + \sqrt{(N_A-N_D)^2 + 4n_i^2}\right]$$
### (b) For intrinsic semiconductors: Derive and expression for the position of the Fermi level ($E_F$) with respect to the conduction band edge ($E_c$). Start the derivation from the following expressions for the concentration of electrons and holes at the conduction band edge, where $N_V$ and $N_C$ are the effective density of states.$$n = N_C\,exp{\left(\frac{-(E_C - E_F)}{kT}\right)} \quad\quad p = N_V\,exp{\left(\frac{(E_F - E_V)}{kT}\right)}$$
Multiplying the two equations it follows that:$$np = N_VN_C\,\exp{\left(\frac{-(E_C-E_V)}{kT}\right)} = N_VN_C \, \exp{\left(\frac{-E_g}{kT}\right)}$$Where $E_g$ is the band gap energy.

The intrinsic carrier concentration, $n_i$ is defined as:$$n_i^2 = N_VN_C \, \exp{\left(\frac{-E_g}{kT}\right)}$$Note that this means that $n_i$ is both the concentration of electrons and the concentration of holes in an intrinsic semiconductor. $n_i=n=p$

Hence, one can write: $$N_C \exp{\left(\frac{-(E_C-E_F)}{kT}\right)} = N_V \exp{\left(\frac{(E_V-E_F)}{kT}\right)}$$and taking the log of both sides we can solve for the Fermi energy obtaining:$$E_F = \frac{1}{2}(E_C+E_V) + \frac{1}{2}kT \ln{\left(\frac{N_V}{N_C}\right)}$$
### (c) Following the derivation, use the resulting formula to calculate the following: For a particular semiconductor material, the charge carrier concentrations (N) are as follows; $N_C = 1.5\times10^{18}\,\text{cm}^{-3}$ and $N_V = 1.3\times10^{19}\,\text{cm}^{-3}$ with a band gap $E_g = 1.43 \,\text{eV}$ at $T=300\,\text{K}$, with $kT=0.026\,\text{eV}$. What is the position of the intrinsic Fermi level with respect to the conduction band edge $E_C$?

Using the expression for the Fermi level above:$$E_F = \frac{1}{2}(E_C+E_V) + \frac{1}{2}kT \ln{\left(\frac{N_V}{N_C}\right)}$$we know that the band gap energy is equal to the difference between the conduction band and the valence band. $E_g = E_C - E_V$ hence:$$E_C = E_g + E_V$$
Unfinished... can't find $E_C$ or $E_V$.

### (d) What are the assumptions of the free electron model? What is the Drude model and how does this explain electrical conductivity? In your answer refer to how Ohm's law can be understood through the Drude model. Use diagrams and questions in your answer.

The free electron model assumes that:
- All valence electrons are free to move, leaving behind positively charged ion cores.
- The charge from the positive ions is represented as a uniform positive background.
- Inter-electron repulsion is ignored. All electrons are treated as independent particles.

The Drude model describes conduction in metals. It says that each atom in the metal contributes one electron to the electron gas.