<div align="center">

# Hi, I'm John Garrison 👋
### Land Survey Intern (LSI) | CAD & Geomatics Specialist | Python & GPU Developer  
**Oregon PLS Candidate** — *NCEES FS & PS Exams Passed (State-Specific Exam Pending)*  

[![Location](https://img.shields.io/badge/Location-Eugene%2C%20OR-2ea44f?style=flat-square&logo=googlemaps&logoColor=white)](https://www.google.com/maps/place/Eugene,+OR)
[![GitHub](https://img.shields.io/badge/GitHub-jlggnss-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/jlggnss)

</div>

---
<div align="left">
  
### 🧭 About Me  

I bridge the gap between **Civil Infrastructure / Geomatics** and **Software Engineering**.  By day, I tackle complex surveying, CAD, and subsurface utility engineering projects under the direction of Registered Professional Engineers (PE) and Professional Land Surveyors (PLS).  By night, I build automation pipelines, run GPU-accelerated distributed computing, design custom hardware modifications, and experiment with local AI orchestration.  

- 🔭 **Currently Building:** Custom Python and mVBA automation tools for **Bentley OpenRoads Designer (ORD)** and **MicroStation CONNECT**, plus **ORD-Admin-Master**—an AI assistant powered by local LLMs and the Model Context Protocol (MCP).  
- 🧮 **Distributed Computing:** Hunting for record primes with the **Great Internet Mersenne Prime Search (GIMPS)** using custom-compiled `PRPLL` and `mfaktc` builds across dedicated NVIDIA compute GPUs.  
- ⚡ **Hardware & Making:** Micro-soldering & BGA/SMD rework, 3D printing inside custom HEPA-filtered enclosures, and self-hosting web infrastructure.  
- 📈 **Algorithmic Trading:** Developing automated post-only limit order strategies in Python using Ed25519 authentication and exchange APIs.  

---

### 🛠️ Tech Stack & Domain Tools   

#### **Geomatics, CAD & GIS**
![OpenRoads Designer](https://img.shields.io/badge/Bentley_OpenRoads_Designer-0076A8?style=for-the-badge&logo=bentley&logoColor=white)
![MicroStation](https://img.shields.io/badge/MicroStation_CONNECT-005A8B?style=for-the-badge&logo=bentley&logoColor=white)
![Trimble Business Center](https://img.shields.io/badge/Trimble_Business_Center-0063A3?style=for-the-badge)
![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=for-the-badge&logo=python&logoColor=white)
![NumPy & Pandas](https://img.shields.io/badge/NumPy_%26_Pandas-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

#### **Languages, Automation & AI**
![Python](https://img.shields.io/badge/Python_3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama_&_MCP-000000?style=for-the-badge)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Zig](https://img.shields.io/badge/Zig_&_Nuitka-F7A41D?style=for-the-badge&logo=zig&logoColor=white)

#### **Compute & Workstation Hardware**
![NVIDIA CUDA](https://img.shields.io/badge/NVIDIA_CUDA_Compute-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Tesla V100 / V100S](https://img.shields.io/badge/Tesla_V100_&_V100S_32GB-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![RTX Ada & Blackwell](https://img.shields.io/badge/RTX_PRO_4000_Blackwell_&_4000_Ada-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![RTX 4090](https://img.shields.io/badge/GeForce_RTX_4090_24GB-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Windows](https://img.shields.io/badge/Windows_Workstation-0078D6?style=for-the-badge&logo=windows&logoColor=white)

<details>
<summary><b>🖥️ Full GPU Compute Inventory (Click to expand)</b></summary>  
<br>

- **Datacenter & Compute:** Liquid Cooled NVIDIA Tesla V100 & V100S (32GB) [HPE, Cisco, Dell and PNY OEM variants]  
- **Workstation (Blackwell / Ada / Ampere / Turing):** NVIDIA RTX PRO 4000 Blackwell (24GB), RTX 4000 Ada Generation (20GB), RTX A4000 (16GB), RTX A2000 (12GB), Quadro RTX 4000  
- **Enthusiast:** MSI GeForce RTX 4090 Suprim Liquid X (24GB)  

</details>

---

<details>
<summary><b>🏅 Google Cloud Skill Badges (Click to expand)</b></summary>
<br>

<p align="left">
  <a href="https://www.skills.google/public_profiles/ed715ef4-a667-4fd9-a595-de184f5f3e31">
    <img src="https://cdn.qwiklabs.com/vRDTuK%2BEWvMNr%2BRMjnXhrxqum6X%2FfUuYurBBS3Cqf%2B0%3D" alt="Introduction to Vertex AI Studio" width="145" />
  </a>
  &nbsp;&nbsp;
  <a href="https://www.skills.google/public_profiles/ed715ef4-a667-4fd9-a595-de184f5f3e31">
    <img src="https://cdn.qwiklabs.com/dqjA9FlkzcMati%2B7a4Kfl1rQcvtcerH0v5hsFWEBzNM%3D" alt="Prompt Design in Agent Platform" width="145" />
  </a>
</p>

*(Click either badge to verify on my Google Cloud Skills public profile.)*
</details>
---

### 🚀 Featured Projects & Workflows

- **📐 Interactive Linear Analysis Tool (ILAT) v5.0:**
  - Desktop GUI (`Tkinter` + `Matplotlib` + `NumPy`/`Pandas`) that segments noisy 2D survey point clouds (Easting/Northing) into clean, connected linear geometry using orientation-independent **Total Least Squares (PCA)** and robust inlier-only refitting.  Features real-time offset/outlier threshold sliders, 2D line-intersection vertex snapping, interactive hover telemetry, and direct export of **MicroStation** `Place Line` / `XY=` keyins and feature-named CSVs.  
- **🗺️ Survey & CAD Automation Suite:**  
  - **GAF Coordinate Rescaler:** High-precision (`decimal.Decimal`) batch Northing/Easting Grid-to-Ground Adjustment Factor rescaling for survey CSV datasets.  
  - **811 Utility Locate Parser:** Automated ticket extraction converting raw utility locate data into standardized Excel workbooks via `openpyxl`.  
  - **PDF Raster Optimizer:** GUI utility (`Tkinter` + `PyMuPDF` + `pikepdf`) for downsampling heavy aerial background rasters in civil plan sets.  
  - **GIS Graph Coloring:** Spatial adjacency polygon coloring using `GeoPandas` to assign distinct RGB palettes across municipal layers.  
- **🤖 Local AI & MCP Tooling:**
  - **ORD-Admin-Master:** Bridging local Ollama models with OpenRoads/MicroStation documentation via Filesystem MCP servers.  
- **🔢 GIMPS & GPU Compute:**
  - Custom-compiled CUDA trial factoring (`mfaktc`) and PRP primality testing (`PRPLL`) orchestrated via `AutoPrimeNet` across Tesla, Quadro/RTX Workstation, and Ada/Blackwell GPUs.  

---
</div>

### 📊 GitHub Stats  

<div align="center">

![jlggnss's GitHub stats](https://github-readme-stats.vercel.app/api?username=jlggnss&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=jlggnss&layout=compact&theme=tokyonight&hide_border=true)

</div>
