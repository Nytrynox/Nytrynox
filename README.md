<div align="center">

# Karthik Idikuda

**I build AI systems and fix bugs in software used by millions.**

[![Portfolio](https://img.shields.io/badge/karthikidikuda.dev-0d1117?style=flat-square&logo=safari&logoColor=58a6ff)](https://www.karthikidikuda.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=58a6ff)](https://linkedin.com/in/karthik129259)
[![ORCID](https://img.shields.io/badge/ORCID-0d1117?style=flat-square&logo=orcid&logoColor=58a6ff)](https://orcid.org/0009-0008-2949-5592)

</div>

---

### Shipped in Production

My code runs in **Grafana v13.0.0** — used by Netflix, Microsoft, PayPal, and over 20M+ users worldwide.

| What I Fixed | Where | Impact |
|:---|:---|:---|
| MySQL query builder was stripping `#` inside quoted strings, silently breaking queries with hex colors and anchor refs | [**Grafana**](https://github.com/grafana/grafana/pull/121535) · 65k+ ★ | **Merged** · Shipped in v13.0.0 |
| Async checkpoint plugin cloned tensors but kept them on GPU — CUDA memory leak + cross-device crash | [**PyTorch Lightning**](https://github.com/Lightning-AI/pytorch-lightning/pull/21631) · 28k+ ★ | Under Review |
| CSS Color Level 4 formats (oklch, lab, display-p3) crash `color2k` → full app crash | [**Streamlit**](https://github.com/streamlit/streamlit/pull/14583) · 40k+ ★ | Under Review |
| `st.video` and `st.map` missing border-radius rounding, toolbar clipped by overflow fix | [**Streamlit**](https://github.com/streamlit/streamlit/pull/14582) · 40k+ ★ | Under Review |
| `NavLink` applying active class to non-matching routes when search params overlap | [**React Router**](https://github.com/remix-run/react-router/pull/14942) · 54k+ ★ | Under Review |
| Edge-case fixes and improvements | [**Vercel AI SDK**](https://github.com/vercel/ai/pull/13961) · [**Fastify**](https://github.com/fastify/fastify/pull/6628) · [**Drizzle ORM**](https://github.com/drizzle-team/drizzle-orm/pull/5566) · [**AutoGen**](https://github.com/microsoft/autogen/pull/7497) | Under Review |

> **12 PRs** across **10 repos**. Every one is a real bug I found, diagnosed, and fixed — not documentation or typo patches.

---

### What I Build

<table>
<tr>
<td width="50%">

**[NEURON-X Omega](https://github.com/karthik-idikuda/memory)**
<br/>
Biologically-inspired AI memory system. Custom SOMA-DB storage engine, Ebbinghaus decay curves for memory retention, contradiction detection across memory layers.
<br/><br/>
`Python` `Anthropic Claude` `FastAPI` · **8,200+ files**

</td>
<td width="50%">

**[NeuroXAI](https://github.com/karthik-idikuda/NeuroXAI)**
<br/>
Explainable AI for Alzheimer's detection from MRI scans. Grad-CAM visualizations that show doctors exactly which brain regions triggered the diagnosis.
<br/><br/>
`TensorFlow` `React` `Jupyter` · **10,600+ files**

</td>
</tr>
<tr>
<td width="50%">

**[AI Gesture Control](https://github.com/karthik-idikuda/AI-Gesture-Control-System)**
<br/>
Touch-free laptop control using hand gestures. Real-time hand tracking for cursor movement, clicks, scrolling, and media playback — no special hardware needed.
<br/><br/>
`OpenCV` `MediaPipe` `PyAutoGUI` · **210,000+ files**

</td>
<td width="50%">

**[AadhaarInsight360](https://github.com/karthik-idikuda/AadhaarInsight360)**
<br/>
Analytics platform for UIDAI Data Hackathon 2026. Real-time geospatial insights into Aadhaar enrolment patterns across India.
<br/><br/>
`Streamlit` `Plotly` `Pandas` · **39,000+ files**

</td>
</tr>
<tr>
<td width="50%">

**[Self-Evolving Agent](https://github.com/karthik-idikuda/AI-Self-Evolving-Learning-Agent)**
<br/>
Autonomous AI agent that modifies its own code based on performance feedback. Runs in a sandboxed Docker environment with rollback safety.
<br/><br/>
`GPT-4` `Docker` `Python`

</td>
<td width="50%">

**[Nexara Blockchain](https://github.com/karthik-idikuda/crypto)**
<br/>
Layer-1 blockchain built from scratch in Rust. Custom VM (NXVM), smart contract language (NexLang), sharding, mempool, and consensus layer.
<br/><br/>
`Rust` `Custom VM` `Smart Contracts`

</td>
</tr>
</table>

<details>
<summary><strong>All 77 projects →</strong></summary>
<br/>

**AI & Machine Learning** — 26 projects

| Project | What it does | Built with |
|:---|:---|:---|
| NeuroXAI | Alzheimer's detection from MRI scans | TensorFlow, Grad-CAM, React |
| Self-Evolving Agent | Recursive self-improvement AI agent | GPT-4, Claude, Docker |
| AI Wildfire Prevention | Early warning via satellite imagery + IoT | CNN, NASA FIRMS, GIS |
| Adversarial Inverse RL | Reinforcement learning with adversarial training | PyTorch, OpenAI Gym |
| Few-Shot Multi-Task | Universal AI assistant with few-shot learning | Transformers, Meta-Learning |
| Student Predictor | Academic performance prediction | Scikit-learn, Pandas |
| Drought Early Warning | NDDI-LSTM model for drought prediction | LSTM, Remote Sensing |
| AI Research Report | Automated research paper summarization | NLP, Transformers |
| Federated Cloud | Energy-efficient resource allocation | TensorFlow Federated, PySpark |
| High-Dim Clustering | Deep learning for big data clustering | Autoencoders, Spark |
| OS Agent | Operating system automation agent | Python, System APIs |
| Gemini Full Project | Google Gemini API integrations | Gemini API, Python |
| Gemini DevPost | Hackathon Gemini project | Gemini, Web |
| Laptop Control Agent | Autonomous laptop control | Computer Vision, LLM |
| Browser Project | Intelligent browser automation | Selenium, LLM |
| Deep Research Agent | AI research across 7 trusted sources | JavaScript, APIs |
| Pandi-GPT | Custom GPT conversational assistant | GPT, NLP |
| Alzheimers Detection | CNN-based medical imaging | TensorFlow, Keras |
| NEURON-X Omega | Self-sovereign permanent AI memory system | Python, Anthropic Claude |
| Conversational HCI | LLM evaluation pipeline for HCI research | Flask, OpenAI, scikit-learn |
| PRAJNA Satellite AI | Satellite data processing for ISRO/ISTRAC | Python, Graph Processing |
| Brain Tumor Detection | MRI-based tumor classification | FastAPI, TensorFlow, React |
| VAYU AI | Pollution death risk predictor with AQI forecast | Streamlit, NASA APIs |
| AI Team Orchestrator | Multi-AI collaboration (GPT+Gemini+Claude) | Node.js, Express |
| NeuroGraphis | Neural network visualization and analysis | Python, Graph Analysis |
| AI Image Recognition | Multi-class image classification | TensorFlow, Transfer Learning |

**Computer Vision** — 17 projects

| Project | What it does | Built with |
|:---|:---|:---|
| AI Gesture Control | Touch-free laptop control via hand gestures | OpenCV, MediaPipe, PyAutoGUI |
| Gesture Control System | Mouse/keyboard via hand gestures | OpenCV, MediaPipe |
| Driver Monitoring | Drowsiness and distraction detection | Dlib, TensorFlow, OpenCV |
| Bus Attendance | Automated student attendance on buses | Face Recognition, IoT |
| Attendance v1.0 | Face recognition with liveness detection | DeepFace, Flask |
| Attendance v2.0 | Cloud-synced attendance with mobile app | MongoDB Atlas, Flutter |
| Invisibility Cloak | Harry Potter style invisibility effect | OpenCV, NumPy |
| Sign Language | Sign language gesture recognition | MediaPipe, TensorFlow |
| CCTV Google | Smart CCTV with cloud integration | Cloud Vision, Python |
| Gesture Calculator | Calculator controlled by hand gestures | OpenCV, MediaPipe |
| MirrorBody-X | AI body analysis and fitness tracking | Computer Vision |
| Neuro Mirror AI | Facial expression and emotion recognition | Deep Learning |
| Gesture 3D Web | Browser-based 3D gesture recognition | WebGL, ML |
| GuardianAI | On-device Android malware detector | TensorFlow Lite, Kotlin |
| Cloud Referee Kiro | AI sports referee for foul detection | Video Analysis, Python |
| SmartRoadGuardian | Road safety and hazard detection | Computer Vision |
| 3D Gesture Web | 3D hand tracking in browser | WebGL, MediaPipe |

**Web Development** — 14 projects

| Project | What it does | Built with |
|:---|:---|:---|
| Personal Portfolio | Professional portfolio website | HTML, CSS, JavaScript |
| Karthik Config | GitHub profile and config files | TypeScript |
| Xerironx Studio | Creative studio website | TypeScript, Modern Web |
| Skylight Landing | Premium landing page | HTML, CSS, JavaScript |
| Cloths Landing | E-commerce fashion landing | Responsive Design |
| OriMind | Interactive 3D mental health platform | HTML, Canvas |
| Infinall Next.js | SaaS platform for AI agents | Next.js, TypeScript |
| Radio Streaming | Online radio player | TypeScript, Audio APIs |
| Sync Watch | Synchronized remote video platform | JavaScript |
| TerraView OS | Open-source 3D mapping platform | Vite, TypeScript, deck.gl |
| TerraView Next | Next.js geospatial mapping app | Next.js, MapLibre GL |
| PropScore Redesign | Property scoring analytics platform | Full Stack |
| Road Career Guidance | AI career roadmap platform | HTML |
| 3D Euler Path Finder | 3D graph algorithm visualization | Python, WebGL |

**Cloud & Distributed Systems** — 5 projects

| Project | What it does | Built with |
|:---|:---|:---|
| Federated Cloud | Privacy-preserving energy optimization | TensorFlow Federated, PySpark |
| High-Dim Clustering | Scalable clustering for big data | Autoencoders, Spark |
| AI E-Governance | Secure AI government services | AWS, NLP, Security |
| AWS Crowd Agent | Serverless scaling and cost optimization | AWS Services, Python |
| Cloud Referee Kiro | Cloud-based AI monitoring | GCP, Real-time Processing |

**Hackathon & Government** — 3 projects

| Project | What it does | Built with |
|:---|:---|:---|
| AadhaarInsight360 | UIDAI Hackathon 2026 analytics | Streamlit, Plotly, Pandas |
| UIDAI Hackathon Solution | Team submission with policy simulation | Python, Data Analysis |
| PRISM | AI for pharma manufacturing (AVEVA x IIT Hyderabad) | LightGBM, DWT, Streamlit |

**Tools, Security & Utilities** — 12 projects

| Project | What it does | Built with |
|:---|:---|:---|
| DocTools Pro | Document processing toolkit | Full Stack |
| Complete PDF | PDF manipulation tool | Python |
| VSCode Hack Extension | Productivity VS Code extension | TypeScript |
| Chrext Chrome Extension | Browser automation extension | JavaScript, Chrome APIs |
| Telegram Bot | Automated bot with command handling | Python |
| Calc Python | CLI calculator | Python |
| Prescription System | Digital prescription management | Dart, Flutter |
| Library Management v2.0 | Advanced library system | Full Stack |
| No-Track Anti-Spyware | Tracker and spyware blocker | Dart |
| Vulnerability Checker | Web security scanner | Python |
| AI Cyber Surveillance | Network intrusion detection toolkit | Python |
| Nexara Blockchain | Layer-1 blockchain with custom VM | Rust |

</details>

---

### Tech

<div align="center">

`Python` `TypeScript` `JavaScript` `Rust` `Kotlin` `Dart` `Java`

`TensorFlow` `PyTorch` `OpenCV` `MediaPipe` `Scikit-learn` `Hugging Face`

`React` `Next.js` `Flutter` `Flask` `FastAPI` `Streamlit`

`AWS` `GCP` `Firebase` `Docker` `MongoDB`

`Figma` `VS Code` `Git`

</div>

---

<div align="center">

📍 Hyderabad, India · 🎓 Marwadi University · ✉️ [idikudakarthik55@gmail.com](mailto:idikudakarthik55@gmail.com)

**Open to full-time roles, internships, and freelance work.**

[![Portfolio](https://img.shields.io/badge/Portfolio-0d1117?style=flat-square&logo=google-chrome&logoColor=58a6ff)](https://www.karthikidikuda.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0d1117?style=flat-square&logo=linkedin&logoColor=58a6ff)](https://linkedin.com/in/karthik129259)
[![Twitter](https://img.shields.io/badge/Twitter-0d1117?style=flat-square&logo=twitter&logoColor=58a6ff)](https://twitter.com/Karthik64066151)
[![Instagram](https://img.shields.io/badge/Instagram-0d1117?style=flat-square&logo=instagram&logoColor=58a6ff)](https://instagram.com/_karthik.z_)
[![Reddit](https://img.shields.io/badge/Reddit-0d1117?style=flat-square&logo=reddit&logoColor=58a6ff)](https://reddit.com/user/Conscious-Gain29)
[![ORCID](https://img.shields.io/badge/ORCID-0d1117?style=flat-square&logo=orcid&logoColor=58a6ff)](https://orcid.org/0009-0008-2949-5592)

<br/>

<img src="https://komarev.com/ghpvc/?username=karthik-idikuda&label=visitors&color=58a6ff&style=flat-square&labelColor=0d1117" alt="Profile Views"/>

</div>
