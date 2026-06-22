<!--
  GitHub Profile README for github.com/shahzeb-jadoon
  This file must live in a PUBLIC repo named exactly:  shahzeb-jadoon
  (i.e. github.com/shahzeb-jadoon/shahzeb-jadoon)
  See SETUP_INSTRUCTIONS.md in this folder for how to deploy it.
-->

<!-- ============================ HEADER ============================ -->
<div align="center">

<a href="https://github.com/shahzeb-jadoon">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&pause=1000&color=6AA1FF&center=true&vCenter=true&width=820&lines=Shahzeb+Jadoon;ML+%26+Edge-AI+Engineer;Neuromorphic+%2B+Autonomous+Systems+%2B+LLM+Agents;I+build+models+that+run+on+the+edge." alt="typing banner" />
</a>

<p>
  <a href="https://www.linkedin.com/in/shahzebkjadoon"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:shahzeb.jadoon.sj@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=shahzeb-jadoon&label=Profile%20views&color=6aa1ff&style=for-the-badge" alt="profile views"/>
</p>

<p>
  <img src="https://img.shields.io/badge/Focus-Edge%20%26%20Neuromorphic%20AI-6AA1FF?style=flat-square"/>
  <img src="https://img.shields.io/badge/Currently-Vision--RWKV%20%2F%20Autonomous%20Driving-9D7CD8?style=flat-square"/>
  <img src="https://img.shields.io/badge/Hardware-Akida%20%C2%B7%20Jetson%20%C2%B7%20STM32-22C55E?style=flat-square"/>
  <img src="https://img.shields.io/badge/Based%20in-Rochester%2C%20NY-F59E0B?style=flat-square"/>
</p>

</div>

<!-- ============================ ABOUT ============================ -->
## 👋 About me

I'm an **ML / Edge-AI engineer** with an **MS in Computer Engineering from RIT** (Kate Gleason College of Engineering) who likes the hard part: making capable models actually *run* under real-world memory, latency, and power budgets.

- 🧠 **Research focus:** neuromorphic & edge AI — spiking neural networks, RWKV/linear-attention, model quantization & sparsity, on-device deployment (BrainChip **Akida**, NVIDIA **Jetson**).
- 🚗 **Building:** a **Vision-RWKV autonomous-driving** stack (CARLA → edge) for my MS capstone, and a **production LLM multi-agent platform** for robot-robot interaction research.
- 🔬 **NSF AWARE-AI NRT Trainee** · ex-**Machine Learning Engineer Intern @ BrainChip** (neuromorphic semantic segmentation).
- 🛠️ I also self-host my own ML infrastructure — a multi-node WSL2 + Tailscale homelab, an n8n+Gemini agentic assistant, and a Nextcloud private cloud.
- ⚡ Interests across the stack: **LLM orchestration/agents, quantum ML, robotics (ROS2), embedded/real-time systems, and HPC/CUDA.**

<!-- ============================ FEATURED PROJECTS ============================ -->
## 🚀 Featured projects

| Project | What it is | Stack |
|---|---|---|
| 🧠🚗 **[neuromorphic-vision-rwkv](https://github.com/shahzeb-jadoon/neuromorphic-vision-rwkv)** | MS capstone — an **RWKV linear-attention** autonomous-driving model trained on a 3.6 TB CARLA corpus; **6.88 ms** median inference, 13.4 M params, targeting Akida/Jetson edge deployment. | `PyTorch` `CARLA` `RWKV` `Edge AI` |
| 🤖💬 **[rri_orchestrator](https://github.com/shahzeb-jadoon/rri_orchestrator)** | Production-deployed **LLM multi-agent platform** for robot-robot interaction research — async FastAPI + NiceGUI, PostgreSQL, LiteLLM (GPT-4o/Gemini/Claude), RBAC, batch automation, self-hosted via Cloudflare Tunnel. | `FastAPI` `LiteLLM` `PostgreSQL` `Docker` |
| ⚡🖥️ **[VGG16_Optimization](https://github.com/shahzeb-jadoon/VGG16_Optimization)** | CMPE 755 final — custom **CUDA C++** kernels for VGG-16 inference (shared-memory tiling, memory coalescing, cuBLAS); Nsight Compute roofline/**CGMA** analysis pinned the FC layers memory-bound (~**41.5 GFLOPS** @ batch=16). 6-person team. | `CUDA` `cuBLAS` `Nsight Compute` `C++` |
| ⚛️🎮 **[Quantum_Policy_Gradient_for_CartPole](https://github.com/shahzeb-jadoon/Quantum_Policy_Gradient_for_CartPole)** | A 4-qubit **variational quantum circuit** RL agent benchmarked head-to-head against a parameter-matched classical net — statistical parity at **18% fewer params**, validated with the hardware-compatible parameter-shift rule. | `PennyLane` `PyTorch` `Gymnasium` |

> 💡 More context on my work, research, and experience: **[linkedin.com/in/shahzebkjadoon](https://www.linkedin.com/in/shahzebkjadoon)**

<!-- ============================ TECH STACK ============================ -->
## 🧰 Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-FF7A00?style=flat-square&logo=mathworks&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**ML / Deep Learning**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

**Edge AI / Neuromorphic**

![BrainChip Akida](https://img.shields.io/badge/BrainChip%20Akida-EC1C24?style=flat-square)
![NVIDIA Jetson](https://img.shields.io/badge/NVIDIA%20Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Quantization](https://img.shields.io/badge/QAT%20%2F%20INT8-555555?style=flat-square)
![SNN](https://img.shields.io/badge/Spiking%20Neural%20Nets-8B5CF6?style=flat-square)
![RWKV](https://img.shields.io/badge/RWKV%20%2F%20Linear%20Attention-1F6FEB?style=flat-square)

**LLM / Agentic AI**

![LiteLLM](https://img.shields.io/badge/LiteLLM-1F6FEB?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![LangChain-style Agents](https://img.shields.io/badge/Multi--Agent%20Orchestration-9D7CD8?style=flat-square)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square)
![MCP](https://img.shields.io/badge/Model%20Context%20Protocol-555555?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

**Robotics / Autonomy / Embedded**

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![CARLA](https://img.shields.io/badge/CARLA%20Simulator-000000?style=flat-square)
![STM32](https://img.shields.io/badge/STM32-03234B?style=flat-square&logo=stmicroelectronics&logoColor=white)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-1FA23F?style=flat-square)
![Simulink](https://img.shields.io/badge/MATLAB%2FSimulink-0076A8?style=flat-square&logo=mathworks&logoColor=white)

**Quantum ML**

![PennyLane](https://img.shields.io/badge/PennyLane-43A5BE?style=flat-square)
![Qiskit](https://img.shields.io/badge/Qiskit-6929C4?style=flat-square&logo=qiskit&logoColor=white)

**Infra / DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Tailscale](https://img.shields.io/badge/Tailscale-242424?style=flat-square&logo=tailscale&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

<!-- ============================ GITHUB STATS ============================ -->
## 📊 GitHub stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=shahzeb-jadoon&show_icons=true&hide_border=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="github stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shahzeb-jadoon&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="top languages" />

<br/>

<img height="165" src="https://streak-stats.demolab.com/?user=shahzeb-jadoon&hide_border=true&theme=tokyonight" alt="streak" />

<!--
  Trophies removed on purpose: the public github-profile-trophy.vercel.app instance
  frequently returns "Invalid upstream response (402)" because its shared GitHub API
  token is rate-limited. If you want trophies back, self-host the service with your own
  GITHUB token (https://github.com/ryo-ma/github-profile-trophy#deploy-to-vercel-) and
  point the URL at YOUR-deployment.vercel.app.
-->

</div>

<!-- ============================ CONTRIBUTION SNAKE ============================ -->
<!-- Powered by .github/workflows/snake.yml — see SETUP_INSTRUCTIONS.md -->
<div align="center">

  <img src="https://raw.githubusercontent.com/shahzeb-jadoon/shahzeb-jadoon/output/snake.svg" alt="contribution snake animation" />

</div>

<!-- ============================ FOOTER ============================ -->
<div align="center">

  <sub>⚡ <em>"Train dense, deploy sparse."</em> - currently teaching big models to live on small chips.</sub>

</div>
