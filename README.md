<div align="center">

<img src="./assets/header.svg" alt="Gaitsiwe Mathai cybercore banner" width="100%" />

<img src="https://readme-typing-svg.demolab.com?font=Press+Start+2P&size=13&duration=3200&pause=900&color=00F0FF&background=07060F00&center=true&vCenter=true&width=820&height=50&lines=BOOTING+GAITSIWE.EXE...;LOADING+EIGENVECTORS...+OK;TRAINING+NEURAL+NET...+LOSS%3A+NaN;ROUTING+PHOTONS+THROUGH+FIBRE...+OK;SEGFAULT+DETECTED+%F0%9F%90%9B+REBOOTING" alt="Boot sequence" />

![Scientific ML](https://img.shields.io/badge/SCIENTIFIC_ML-07060F?style=for-the-badge&logo=pytorch&logoColor=B44CFF)
![Embedded ML](https://img.shields.io/badge/EMBEDDED_ML-07060F?style=for-the-badge&logo=arduino&logoColor=00F0FF)
![Optical Networking](https://img.shields.io/badge/OPTICAL_NETWORKING-07060F?style=for-the-badge&logo=cisco&logoColor=B44CFF)
![HPC Networking](https://img.shields.io/badge/HPC_NETWORKING-07060F?style=for-the-badge&logo=linux&logoColor=00F0FF)

</div>

---

### 💾 `SYSTEM_INFO`

```text
┌──────────────────────────────────────────────────────────┐
│  USER      : Gaitsiwe Mathai  (gaitsiwemathai)           │
│  STATUS    : Undergraduate.exe — still compiling...      │
│  RUNTIME   : between eigenvectors, network packets,      │
│              and segmentation faults                     │
│  MODULES   : Scientific ML | Embedded ML                 │
│              Network Automation & Programmability        │
│              Optical Networking | HPC Networking         │
│  FUEL      : coffee, spite, Stack Overflow               │
│  OPEN_TO   : collaboration [TRUE]                        │
└──────────────────────────────────────────────────────────┘
```

---

### 🧠 `neural_core.sys`

<div align="center">
<img src="./assets/neural-net.svg" alt="Animated neural network" width="100%" />
</div>

**Scientific ML** · physics-informed networks, differentiable simulation, surrogate models

$$\mathcal{L}(\theta) = \underbrace{\lVert u_\theta - u_{\text{data}} \rVert^2}_{\text{data}} + \underbrace{\lVert \mathcal{N}[u_\theta] \rVert^2}_{\text{physics residual}}$$

**Embedded ML** · quantization, pruning and inference on microcontrollers with kilobytes of RAM

$$W_q = \operatorname{round}\!\left(\tfrac{W}{s}\right) + z \quad\Rightarrow\quad \text{32 bits} \to \text{8 bits}$$

🔍 Currently building: **Lightweight physics - informed neural networks for embedded systems**

---

### 🌐 `network_topology.sys`

<div align="center">
<img src="./assets/network.svg" alt="Animated network topology" width="100%" />
</div>

**Network Automation & Programmability** · configs, monitoring and deployments as code (APIs, NETCONF/YANG)
**Optical Networking** · fibre links, WDM, and moving bits as photons
**High Performance Networking** · low latency, high throughput, packet-level analysis

$$C = B \log_2\!\left(1 + \tfrac{S}{N}\right) \qquad \text{(Shannon: the speed limit of every link)}$$

🔍 Currently building: **Automated network performance monitoring and optimization for high spped optical networks**

---

### 🧮 `me.py`

```python
import numpy as np

class Gaitsiwe:
    status = "Undergraduate.exe (still compiling...)"

    def __init__(self):
        # life as a matrix
        self.life = np.array([[1, 0],    # sleep
                              [0, 1]])   # deadlines
        # det = 1 on a good day, 0 in exam week (singular)

    def scientific_ml(self, physics):
        return "teach a neural net the PDE, then argue about the boundary conditions"

    def embedded_ml(self, model):
        return model.quantize().prune().squeeze_into(kilobytes=64)

    def automate(self, network):
        return "why configure one router by hand when you can break fifty with a script"

    def debug(self, bug):
        return "printf('here');"   # no gdb was harmed
```

---

### ⚡ `toolchain.cfg`

![Python](https://img.shields.io/badge/Python-07060F?style=for-the-badge&logo=python&logoColor=00F0FF)
![C](https://img.shields.io/badge/C-07060F?style=for-the-badge&logo=c&logoColor=B44CFF)
![C++](https://img.shields.io/badge/C++-07060F?style=for-the-badge&logo=cplusplus&logoColor=00F0FF)
![Bash](https://img.shields.io/badge/Bash-07060F?style=for-the-badge&logo=gnubash&logoColor=B44CFF)
![MATLAB](https://img.shields.io/badge/MATLAB-07060F?style=for-the-badge&logo=mathworks&logoColor=00F0FF)
![PyTorch](https://img.shields.io/badge/PyTorch-07060F?style=for-the-badge&logo=pytorch&logoColor=00F0FF)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=B44CFF)
![NumPy](https://img.shields.io/badge/NumPy-07060F?style=for-the-badge&logo=numpy&logoColor=00F0FF)
![Ansible](https://img.shields.io/badge/Ansible-07060F?style=for-the-badge&logo=ansible&logoColor=B44CFF)
![Docker](https://img.shields.io/badge/Docker-07060F?style=for-the-badge&logo=docker&logoColor=00F0FF)
![Linux](https://img.shields.io/badge/Linux-07060F?style=for-the-badge&logo=linux&logoColor=B44CFF)
![Wireshark](https://img.shields.io/badge/Wireshark-07060F?style=for-the-badge&logo=wireshark&logoColor=00F0FF)
![Git](https://img.shields.io/badge/Git-07060F?style=for-the-badge&logo=git&logoColor=B44CFF)

---

### 🧭 `brain_topology.mmd`

```mermaid
%%{init: {'theme':'dark','themeVariables':{'primaryColor':'#0E0B1F','primaryBorderColor':'#B44CFF','lineColor':'#00F0FF','primaryTextColor':'#C9D6FF','fontFamily':'monospace'}}}%%
graph LR
    A[Eigenvectors] -->|SYN| B((Brain))
    S[Scientific ML] -->|gradients| B
    T[Embedded ML] -->|64KB limit| B
    O[Optical Networking] -->|photons| B
    H[HPC Networking] -->|packets| B
    D[Segfaults] -->|ERROR 11| B
    B -->|SYN-ACK| E[Degree.exe]
    E -->|loading...| F[Graduation 🎓]
```

---

### 📊 `telemetry.log`

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=gaitsiwemathai&show_icons=true&hide_border=false&bg_color=07060F&title_color=00F0FF&text_color=C9D6FF&icon_color=B44CFF&border_color=B44CFF" height="160" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=gaitsiwemathai&layout=compact&hide_border=false&bg_color=07060F&title_color=00F0FF&text_color=C9D6FF&border_color=00F0FF" height="160" />

</div>

```diff
+ models squeezed onto microcontrollers: several
+ routers automated instead of hand-configured: yes
+ photons routed: countless
- segfaults avoided: 0 (they find me)
- RAM available on the MCU: what RAM
```

---

<div align="center">

```text
> exit 0   // thanks for visiting. go touch some grass, then come back.
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:B44CFF,100:00F0FF&height=90&section=footer" width="100%" />

</div>
