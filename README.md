<h1 align="center">🌞🌬️🔋 PV-Wind-Battery Based DC Microgrid</h1>

<p align="center">
  <img src="https://img.shields.io/badge/MATLAB-Simulink-orange?logo=mathworks" alt="MATLAB"/>
  <img src="https://img.shields.io/badge/Microgrid-DC-blue" alt="Microgrid"/>
  <img src="https://img.shields.io/badge/Renewables-Solar%20%7C%20Wind-green" alt="Renewables"/>
</p>

<p align="center">
  <b>Graduate project (ENEL 676 – Distributed Energy Resources)</b><br>
  Design and simulation of a hybrid <b>DC Microgrid</b> integrating PV, Wind, and Battery using MATLAB/Simulink.
</p>

---

<h2>📌 Project Overview</h2>
<p>
This project develops a <b>standalone DC microgrid</b> that combines photovoltaic panels, wind turbines, and a battery storage system.  
The system addresses the challenges of variability in renewable energy and ensures <b>voltage stability, power reliability, and high renewable penetration</b>.  
A <b>Neural Network-based Maximum Power Point Tracking (MPPT)</b> controller was implemented to optimize energy harvesting, outperforming traditional MPPT methods under dynamic conditions:contentReference[oaicite:1]{index=1}.
</p>

---

<h2>⚡ Features</h2>
<ul>
  <li>🌞 <b>PV System</b> – custom PV module with neural-network MPPT</li>
  <li>🌬️ <b>Wind Turbine System</b> – DC generator with boost converter</li>
  <li>🔋 <b>Battery Storage</b> – lithium-ion, bidirectional DC-DC converter</li>
  <li>🧠 <b>Neural Network MPPT</b> – trained using NASA POWER dataset (2021)</li>
  <li>🔀 <b>Energy Flow</b> – renewable priority → battery buffer → load</li>
  <li>🖥️ <b>MATLAB/Simulink Simulation</b> – tested under varying irradiance, wind, and load conditions</li>
</ul>

---

<h2>📂 Repository Structure</h2>


---

<h2>⚙️ Technical Specifications</h2>
<ul>
  <li><b>DC Bus Voltage:</b> 400 V ±2%</li>
  <li><b>PV Module:</b> 250 W, 3 parallel strings × 8 modules each</li>
  <li><b>Wind Turbine:</b> 6.5 kW nominal mechanical power</li>
  <li><b>Battery:</b> Li-ion, 240 V, 48 Ah, SOC = 50% nominal</li>
  <li><b>Converters:</b> Boost (PV & Wind), Bidirectional DC-DC (Battery)</li>
  <li><b>Switching Frequency:</b> 10 kHz (PV/Battery), 5 kHz (Wind)</li>
</ul>

---

<h2>📊 Simulation Results</h2>
<ul>
  <li>✅ Stable DC bus voltage at 400 V under varying conditions</li>
  <li>⚡ MPPT efficiency > 98% (PV & Wind)</li>
  <li>🌍 Renewable energy supplied > 85% of total load</li>
  <li>📈 Converter efficiency: 92–96%</li>
  <li>⏱️ Dynamic response: < 0.5s to irradiance, wind, or load changes</li>
</ul>

---

<h2>🌟 Future Improvements</h2>
<ul>
  <li>🔧 Hardware prototyping for real-time validation</li>
  <li>📡 Grid-connected operation with peak shaving/net metering</li>
  <li>🧠 Advanced EMS: fuzzy logic, reinforcement learning, MPC</li>
  <li>☁️ Forecast-based scheduling (weather & load)</li>
  <li>📐 IoT integration for remote monitoring & control</li>
</ul>

---

<h2>👨‍💻 Authors</h2>
<p>
Group 30 – ENEL 676 Distributed Energy Resources  
<ul>
  <li>Md Mahadi Hasan Moon</li>
  <li>Anik Kumar Paul</li>
  <li>Md Imran Hossain</li>
</ul>
</p>

<p align="center">
  <i>“Harnessing solar, wind, and storage for a reliable standalone microgrid ✨”</i>
</p>
