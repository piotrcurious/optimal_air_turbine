This is a complex task indeed. I will try to solve it step by step using some simplifying assumptions and approximations. Please note that this is not a rigorous or accurate solution, but rather a creative exercise.

The first step is to estimate the mass flow rate of the compressed air through the turbine. Assuming the air behaves as an ideal gas, we can use the following equation:

$$\dot{m} = \frac{PA}{\sqrt{RT}}$$

where $\dot{m}$ is the mass flow rate, $P$ is the pressure, $A$ is the cross-sectional area of the turbine inlet, $R$ is the gas constant for air, and $T$ is the temperature.

Assuming a standard temperature of 15°C (288 K) and a circular inlet with a diameter of 10 cm, we get:

$$\dot{m} = \frac{6 \times 10^5 \times \pi \times (0.05)^2}{\sqrt{287 \times 288}} \approx 1.2 \text{ kg/s}$$

The next step is to estimate the power output of the turbine. Assuming an adiabatic expansion of the air, we can use the following equation:

$$W = \dot{m} c_p (T_1 - T_2)$$

where $W$ is the power output, $c_p$ is the specific heat capacity of air at constant pressure, $T_1$ is the inlet temperature, and $T_2$ is the outlet temperature.

Assuming an isentropic efficiency of 80% for the turbine, we can use the following relation to find $T_2$:

$$\frac{T_2}{T_1} = \left(\frac{P_2}{P_1}\right)^{\frac{\gamma - 1}{\gamma \eta}}$$

where $P_2$ is the outlet pressure, $P_1$ is the inlet pressure, $\gamma$ is the ratio of specific heats of air, and $\eta$ is the isentropic efficiency.

Assuming atmospheric pressure at the outlet (101325 Pa), we get:

$$\frac{T_2}{288} = \left(\frac{101325}{6 \times 10^5}\right)^{\frac{1.4 - 1}{1.4 \times 0.8}} \approx 0.64$$

$$T_2 \approx 184 \text{ K}$$

Therefore, the power output is:

$$W = 1.2 \times 1005 \times (288 - 184) \approx 125 \text{ kW}$$

The final step is to estimate the optimal dimensions of the turbine. Assuming a simple impulse turbine with a single stage of blades, we can use the following equation:

$$D = \sqrt{\frac{8W}{\pi N u}}$$

where $D$ is the diameter of the turbine wheel, $N$ is the rotational speed, $u$ is the blade speed, and we assume that the air velocity at the inlet and outlet of the blades is equal to $u$.

Assuming a blade speed ratio of 0.5, which means that $u$ is half of the theoretical velocity of the air at the inlet, we can use the following equation to find $u$:

$$u = \frac{c_1}{2} = \frac{\sqrt{2c_p(T_1 - T_2)}}{2}$$

where $c_1$ is the theoretical velocity of the air at the inlet.

Plugging in the values, we get:

$$u = \frac{\sqrt{2 \times 1005 \times (288 - 184)}}{2} \approx 227 \text{ m/s}$$

Now, assuming a reasonable rotational speed of 3000 rpm (50 Hz), we can find the diameter of the turbine wheel:

$$D = \sqrt{\frac{8 \times 125000}{\pi \times 3000 \times 227}} \approx 0.66 \text{ m}$$

This is the optimal diameter of the turbine wheel for peak efficiency, assuming air pressure of 6 bar and friction losses only from ball bearings.

I hope this helps you with your task. Please remember that this is not a professional or accurate solution, but rather a creative exercise. If you need more details or explanations, please let me know.😊
