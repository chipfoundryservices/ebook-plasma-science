# Chapter 1: Fundamentals of Low-Temperature Processing Plasmas

## 1.1 Non-Equilibrium Thermodynamic State
Semiconductor processing plasmas operate in the glow discharge regime at pressures between $1\text{ mTorr}$ and $100\text{ mTorr}$ ($0.13\text{ to } 13.3\text{ Pa}$). They are characterized by a profound breakdown of thermodynamic equilibrium:

$$T_e \gg T_{\text{ion}} \approx T_{\text{gas}} \approx 300\text{–}450\text{ K}$$

Where:
- Electron temperature: $T_e \approx 2\text{–}5\text{ eV}$ ($23,000\text{–}58,000\text{ K}$)
- Ion temperature: $T_i \approx 0.03\text{–}0.05\text{ eV}$ (near room temperature)
- Fractional ionization: $\eta = \frac{n_e}{n_e + n_g} \approx 10^{-6}\text{ to } 10^{-2}$

Because electrons have negligible mass compared to ions ($m_e / M_i \sim 10^{-5}$), collisional energy transfer between electrons and heavy neutrals is inefficient, allowing electrons to sustain high kinetic energy while the wafer remains cool.

## 1.2 Debye Shielding and Plasma Frequency
A quasi-neutral plasma ($n_e \approx n_i$) shields out electrostatic perturbations over a characteristic distance known as the **Debye Length** ($\lambda_D$):

$$\lambda_D = \sqrt{\frac{\epsilon_0 k_B T_e}{e^2 n_e}}$$

For typical processing parameters ($n_e = 10^{10}\text{ cm}^{-3}$, $T_e = 3\text{ eV}$), $\lambda_D \approx 128\mu\text{m}$.
If local charge neutrality is perturbed, electrons oscillate at the **Electron Plasma Frequency** ($\omega_{pe}$):

$$\omega_{pe} = \sqrt{\frac{e^2 n_e}{\epsilon_0 m_e}} \approx 2\pi \times (8980 \sqrt{n_e}) \text{ rad/s}$$

At $n_e = 10^{11}\text{ cm}^{-3}$, $f_{pe} \approx 2.84\text{ GHz}$, meaning electrons respond instantaneously to standard RF excitation frequencies (13.56 MHz, 27 MHz, 60 MHz).
