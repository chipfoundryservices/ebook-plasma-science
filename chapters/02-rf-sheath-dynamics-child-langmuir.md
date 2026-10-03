# Chapter 2: RF Sheath Dynamics & The Child-Langmuir Formulation

## 2.1 The Origin of the Plasma Sheath
Because electrons move much faster than ions ($v_{\text{thermal},e} \gg v_{\text{thermal},i}$), any surface immersed in a plasma initially collects a massive influx of electrons, charging the surface negatively relative to the bulk plasma. 

A non-neutral positive space-charge boundary layer—the **plasma sheath**—forms adjacent to all chamber walls and the wafer. The bulk plasma remains at a positive potential called the **Plasma Potential** ($V_p \approx 10\text{–}25\text{ V}$).

## 2.2 The Bohm Sheath Criterion
For a stable monotonic sheath to form, positive ions entering the sheath from the quasi-neutral presheath must be pre-accelerated to a minimum velocity called the **Bohm Velocity** ($u_B$):

$$u_B = \sqrt{\frac{k_B T_e}{M_i}}$$

This implies an ion energy gain in the presheath of:

$$E_{\text{presheath}} = \frac{1}{2} M_i u_B^2 = \frac{1}{2} k_B T_e$$

## 2.3 The Child-Langmuir Space-Charge Law
In a high-voltage collisionless sheath of thickness $s$ sustained by potential drop $V_0$, the ion current density $J_i$ is governed by the Child-Langmuir law:

$$J_i = \frac{4}{9} \epsilon_0 \sqrt{\frac{2e}{M_i}} \frac{V_0^{3/2}}{s^2}$$

Solving for sheath thickness $s$:

$$s = \left( \frac{4\epsilon_0}{9 J_i} \right)^{1/2} \left( \frac{2e}{M_i} \right)^{1/4} V_0^{3/4} \propto V_0^{3/4}$$

This relationship dictates the acceleration voltage and directional trajectory of ions striking the wafer surface.
