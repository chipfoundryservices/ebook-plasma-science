# Appendix B: Mathematical Derivations

## B.1 Bohm Sheath Criterion Derivation
Consider a collisionless 1D sheath with planar boundary at $x = 0$, where potential $\Phi(0) = 0$. Ions enter with velocity $u_0$.

From conservation of ion energy:

$$\frac{1}{2} M_i u(x)^2 = \frac{1}{2} M_i u_0^2 - e \Phi(x) \implies u(x) = \left( u_0^2 - \frac{2e\Phi}{M_i} \right)^{1/2}$$

From continuity of ion current density $J_i = e n_i(x) u(x) = e n_0 u_0$:

$$n_i(x) = n_0 \left( 1 - \frac{2e\Phi}{M_i u_0^2} \right)^{-1/2}$$

Assuming electrons follow a Boltzmann distribution in the repulsive potential:

$$n_e(x) = n_0 \exp\left( \frac{e\Phi}{k_B T_e} \right)$$

Poisson's equation for the electrostatic potential in the sheath is:

$$\frac{d^2 \Phi}{dx^2} = -\frac{e}{\epsilon_0} (n_i - n_e) = -\frac{e n_0}{\epsilon_0} \left[ \left( 1 - \frac{2e\Phi}{M_i u_0^2} \right)^{-1/2} - \exp\left(\frac{e\Phi}{k_B T_e}\right) \right]$$

For small potentials near the sheath edge ($\frac{e|\Phi|}{k_B T_e} \ll 1$), Taylor expand both terms:

$$\left( 1 - \frac{2e\Phi}{M_i u_0^2} \right)^{-1/2} \approx 1 + \frac{e\Phi}{M_i u_0^2}$$

$$\exp\left(\frac{e\Phi}{k_B T_e}\right) \approx 1 + \frac{e\Phi}{k_B T_e}$$

Substituting back into Poisson's equation:

$$\frac{d^2 \Phi}{dx^2} \approx -\frac{e n_0}{\epsilon_0} \left[ \frac{e\Phi}{M_i u_0^2} - \frac{e\Phi}{k_B T_e} \right] = \frac{e^2 n_0 \Phi}{\epsilon_0} \left[ \frac{1}{k_B T_e} - \frac{1}{M_i u_0^2} \right]$$

For the potential $\Phi(x)$ to be monotonically decreasing (convex curvature $\frac{d^2\Phi}{dx^2} > 0$ for $\Phi < 0$):

$$\frac{1}{k_B T_e} - \frac{1}{M_i u_0^2} \le 0 \implies M_i u_0^2 \ge k_B T_e \implies u_0 \ge \sqrt{\frac{k_B T_e}{M_i}} \equiv u_B$$

This proves that ions must enter the sheath with at least the Bohm speed $u_B$.

## B.2 Debye Length Formulation
The 1D Poisson equation for a point test charge $+Q$ at the origin in a plasma is:

$$\frac{1}{r^2} \frac{d}{dr} \left( r^2 \frac{d\Phi}{dr} \right) = -\frac{e}{\epsilon_0} [n_i(r) - n_e(r)]$$

For small potentials $e\Phi \ll k_B T_e$:

$$n_e(r) \approx n_0 \left(1 + \frac{e\Phi}{k_B T_e}\right), \quad n_i(r) \approx n_0$$

$$\frac{1}{r^2} \frac{d}{dr} \left( r^2 \frac{d\Phi}{dr} \right) = \frac{e^2 n_0}{\epsilon_0 k_B T_e} \Phi = \frac{1}{\lambda_D^2} \Phi$$

Where:

$$\lambda_D \equiv \sqrt{\frac{\epsilon_0 k_B T_e}{e^2 n_0}}$$

The spherically symmetric solution is the shielded Yukawa-type potential:

$$\Phi(r) = \frac{Q}{4\pi\epsilon_0 r} \exp\left(-\frac{r}{\lambda_D}\right)$$
