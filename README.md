<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Mohit%20Manoj%20Barade&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=36&desc=MS%20Computer%20Engineering%20%C2%B7%20San%20Jos%C3%A9%20State%20University&descAlignY=58&descSize=16" width="100%"/>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mb473)
[![Gmail](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mohitbarade1@gmail.com)
[![Devpost](https://img.shields.io/badge/Devpost-003E54?style=for-the-badge&logo=devpost&logoColor=white)](https://devpost.com/mohitbarade1)

</div>

---

```
Hardware-software co-design · Edge AI & computer vision · ML research · Agentic systems
From experimental prototypes to working systems.
```

MS Computer Engineering student at **San José State University**, building at the intersection of **intelligent hardware, on-device AI, machine learning, and software systems**.

My recent work includes **FPGA acceleration on a Zybo Z7**, **open-weight generative models deployed locally on an HP ZGX Nano**, **MRI-based ML experiments**, and **a C++ CPU simulator**. I also co-researched with **Bosch Global Software Technologies** on automated legacy-code migration and validation.

---

<div align="center">

### Stack

**Hardware & Systems**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![Verilog](https://img.shields.io/badge/Verilog-4B0082?style=flat-square)
![Zynq SoC](https://img.shields.io/badge/Zynq_SoC-ED1C24?style=flat-square)
![Vivado](https://img.shields.io/badge/Xilinx_Vivado-E01F27?style=flat-square)
![HP ZGX Nano](https://img.shields.io/badge/HP_ZGX_Nano-0096D6?style=flat-square)
![NVIDIA GB10](https://img.shields.io/badge/NVIDIA_GB10-76B900?style=flat-square&logo=nvidia&logoColor=white)

**AI, ML & Research**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC6B23?style=flat-square)
![SDXL](https://img.shields.io/badge/SDXL-6A5ACD?style=flat-square)
![ControlNet](https://img.shields.io/badge/ControlNet-444444?style=flat-square)
![Qwen3](https://img.shields.io/badge/Qwen3--8B-7651FF?style=flat-square)

**Software, Cloud & Agents**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1B1B1B?style=flat-square&logo=python&logoColor=white)
![W&B](https://img.shields.io/badge/W%26B%20Weave-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)

</div>

---

### Featured Research & Hardware Projects

<table>
<tr>
<td width="50%" valign="top">

**⚙️ [FPGA-Accelerated Matrix Multiplication](https://github.com/mohiitt/Hardware_Accelerated_Matrix_Multiplication)**

Built and benchmarked a hardware-software accelerator on the **Zybo Z7 (Zynq SoC)**. Integrated a **16-processing-element Verilog array**, AXI DMA, and banked BRAM with pipelined memory transfers; achieved **5.15× speedup** over the ARM software baseline for 64×64 matrix multiplication.

`Verilog` `C` `Vivado` `Vitis` `AXI DMA` `Zynq SoC`

[→ GitHub](https://github.com/mohiitt/Hardware_Accelerated_Matrix_Multiplication)

</td>
<td width="50%" valign="top">

**🎨 ProtoSkin — On-Device Generative AI**

Built a fully local **2D sketch → material render → 3D mesh** pipeline with open-weight **SDXL + ControlNet, TripoSG, and Qwen3-8B**. Ran the system on the **HP ZGX Nano (NVIDIA GB10, 128 GB unified memory)** without cloud inference; the team reported **under 20-second** generation. **Top-6 finalist** at SJSU Edge AI Hackathon 2026.

`HP ZGX Nano` `NVIDIA GB10` `SDXL` `ControlNet` `TripoSG` `Qwen3-8B`

[→ Hackathon Showcase](https://sjsu-hackathon.web.app/teams)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🧠 [NeuroScan AI](https://github.com/mohiitt/NeuroScan-AI)**

Studied Alzheimer's disease classification with **104 structural biomarkers extracted from MRI scans** in OASIS-1. Designed **feature ablation experiments** to test dependence on cognitive assessments; an enhanced XGBoost model reported **90.5% accuracy** and reduced MMSE feature importance from **37.8% to 9.1%**.

`Python` `XGBoost` `Scikit-Learn` `MRI Analysis` `OASIS-1`

[→ GitHub](https://github.com/mohiitt/NeuroScan-AI)

</td>
<td width="50%" valign="top">

**💻 [SoftCPU — 16-bit CPU Simulator](https://github.com/mohiitt/SoftCPU)**

Implemented a **C++17 processor simulator** with a custom ISA, assembler, emulator, ALU, stack operations, and memory-mapped I/O. Built instruction-level execution traces and tests to validate memory operations, control flow, and recursive program execution.

`C++17` `CPU Architecture` `ISA` `Emulation` `Testing`

[→ GitHub](https://github.com/mohiitt/SoftCPU)

</td>
</tr>
</table>

### Additional AI & Software Projects

<table>
<tr>
<td width="50%" valign="top">

**🔍 TinyScout**

Autonomous web research agent. A Planner → Retriever → Synthesizer pipeline with evidence gating — returns structured signals instead of hallucinating when sources are weak.

`Claude API` `Python` `Streamlit` `Multi-Agent`

[→ Devpost](https://devpost.com/software/tinyscout)

</td>
<td width="50%" valign="top">

**🛡️ Vigil**

Real-time API health monitoring with push-based agents, configurable alerting policies, incident deduplication, and a full observability stack.

`Node.js` `Redis` `Kubernetes` `OpenTelemetry`

[→ Devpost](https://devpost.com/software/productionagents)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**⚔️ Rivalis**

AI-powered competitive intelligence engine and acquisition war-game simulator. Specialized agents build competitive landscapes while CEO digital twins respond to simulated acquisition decisions.

`LangGraph` `Claude API` `CopilotKit` `Redis` `W&B Weave`

[→ Devpost](https://devpost.com/software/rivalis)

</td>
<td width="50%" valign="top">

**🏥 ClinOps**

Multi-agent clinical trial management. Specialized LLM agents decompose, analyze, and transform unstructured protocol documents into structured deliverables.

`TypeScript` `Next.js` `Gemini API` `OpenTelemetry`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📈 GraphLens**

GNN recommendation engine using LightGCN on bipartite user–item graphs, with hybrid MLP metadata fusion and chronological evaluation against baseline models.

`PyTorch Geometric` `LightGCN` · **+11.8% Recall@10 vs. popularity baseline**

</td>
<td width="50%" valign="top">

**🗂️ RAGent**

Semantic search and question answering over technical documents, with a retrieval-evaluation feedback loop to assess answer quality.

`FastAPI` `Qdrant` `Docker` `Streamlit`

</td>
</tr>
</table>

---

<div align="center">

**GPA 3.53 &nbsp;·&nbsp; Graduating May 2027 &nbsp;·&nbsp; Open to Research, AI/ML & SWE Opportunities**

`San Jose, CA` &nbsp;·&nbsp; [mohitbarade1@gmail.com](mailto:mohitbarade1@gmail.com) &nbsp;·&nbsp; [linkedin.com/in/mb473](https://linkedin.com/in/mb473)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>
