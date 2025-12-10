# Hi, I'm Allie! 👋

I am an IT professional, Home Lab enthusiast, and Junior Developer passionate about **server infrastructure**, **private AI orchestration**, and **hybrid cloud environments**.

I don't just manage servers; I build distributed systems that turn hardware into helpful home services.

### 🎓 Certifications in Progress
I am actively upskilling to formalize my experience:
* **Google IT Support Professional Certificate:** *Currently completing Course 1 (Technical Support Fundamentals) and moving rapidly through the six-course specialization.*
* **ISC2 Certified in Cybersecurity (CC):** *Enrolled and preparing for examination.*

---

### 🚀 Featured Projects

#### 🧠 CORTEX (Private AI Ecosystem)
A distributed, private AI assistant ecosystem designed for the Samsung S25 Ultra and local server infrastructure.
* **Architecture:** Service-Oriented Architecture (SOA) bridging mobile edge devices with high-power backend servers.
* **The Stack:** Kotlin (Android Service), Python (FastAPI Backend), and TensorFlow Lite (Edge Inference).
* **Hardware Optimization:** Deployed on a GMKtec EVO-X2 (96GB RAM), pushing the hardware limits to serve 120B+ parameter models (e.g., openai GPT-OSS:120B) at ~19-40 t/s.
      * Engineering Feat: Achieved stability by forcing GTT (Graphics Translation Table) allocation to bypass stock BIOS memory locks.
      * Backend Tuning: Actively benchmarking and switching between ROCm and Vulkan backends per model to maximize inference throughput.

#### 📚 GLEH (Gammon's Landing Educational Hub)
[View Repository](https://github.com/allie-rae-devop/GLEH)
A self-hosted, Dockerized learning management portal designed to serve educational resources to the public web.
* **Deployment:** Hosted on Oracle Cloud Infrastructure (OCI) using Docker containers.
* **Content Strategy:** Public-facing instances serve MIT OpenCourseWare and Creative Commons licensed textbooks, while internal instances handle private, copyrighted libraries.
* **Networking:** Utilizes **Nginx Proxy Manager** for SSL termination and reverse routing.

---

### 🔧 Lab Infrastructure (Hybrid Cloud)
My lab environment simulates enterprise operations, spanning on-premise hardware and cloud virtual machines.

**☁️ Cloud Infrastructure (OCI)**
* **Oracle Cloud:** Managing a remote **Quad-Core ARM Ampere VM (24GB RAM / 200GB Storage)**.
* **Use Case:** Acts as the public-facing gateway for web services, leveraging the "Always Free" tier for high-performance, cost-effective hosting.

**🏠 On-Premise Infrastructure**
* **AI Research & Training Node:** High-RAM compute nodes utilizing Oobabooga (Text Generation WebUI) and LLaMA Factory. Currently moving beyond simple inference into model fine-tuning and training workflows, alongside image generation pipelines using ComfyUI.
* **Virtualization Cluster:** **Dell PowerEdge (R610)** and USFF nodes running **Proxmox VE** for high availability.
* **Storage:** Transitioning from bare metal Unraid to ZFS-backed storage arrays with enterprise-grade permissions.
* **Networking:** VLAN segmentation and network security managed via **TP-Link Omada** software controllers.

### 🛠 Tech Stack

**Infrastructure & OS**
* **Virtualization:** Proxmox VE, Docker, Unraid
* **Cloud:** Oracle Cloud Infrastructure (OCI)
* **Server OS:** Ubuntu Server, Debian, Windows Server
* **Networking:** Nginx / Nginx Proxy Manager, TP-Link Omada

**Development & AI Engineering**
* **Languages:** Python (FastAPI), Kotlin (Android), Java, HTML5/CSS
* **AI Training & Ops:** LLaMA Factory (Fine-tuning), Oobabooga, Ollama, ComfyUI
* **Edge & Optimization:** TensorFlow Lite, ROCm, Vulkan, Quantization, Local RAG
* **Tools:** Git/GitHub, Android Studio, VS Code, Bash Scripting, n8n

---

📫 **Open to connecting:** I am always interested in discussing new opportunities, collaborations, or deep-diving into local AI infrastructure. Feel free to reach out!
