# Electron cyclotron resonance simulation

This is a small experiment to model electron cyclotron resonance. The code includes simulation functions for the path of an electron in an  ECR setup, i. e. a static magnetic field perpendicular to an oscillating electric field. If the ECR condition
<p>
$$ \omega_c = \frac{eB}{m_e}$$
</p>
is met, the electron efficiently absorbs energy from the electric field.
The velocity of the electron can be described by the following differential equation:
<p>
$$ \frac{\text{d}\mathbf{v}}{\text{d}t}=\frac{e}{m_e}(\mathbf{E}(t)+\mathbf{v}(t)\times\mathbf{B})$$
</p>

![out/ECR_0,0875T_2450000000Hz.png](https://github.com/VioletSpace/ECR-Simulation/blob/06663b01ab88d6e6745d13ce3a4a548145f9e132/out/ECR_0%2C0875T_2450000000Hz.png)
![out/ECR_0,0875T_850000000Hz.png](https://github.com/VioletSpace/ECR-Simulation/blob/06663b01ab88d6e6745d13ce3a4a548145f9e132/out/ECR_0%2C0875T_850000000Hz.png)