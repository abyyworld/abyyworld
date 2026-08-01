# Akbar Juraev

**Human-Computer Interaction & AI Researcher · Robot Learning & Embodied Systems**

BSc AI & Computer Science at the **University of Birmingham** · Student Researcher · Official IT ambassador between Uzbekistan and the UK under the Ministry of Digital Technologies

Four studies in preparation for **CHI** and **IEEE VR**. Founder of **[Cicatrixa](https://cicatrixa.com)**.

**[akbarjuraev.com](https://www.akbarjuraev.com)** · [CV](https://www.akbarjuraev.com/cv.pdf)

---

### Research

**Error Feedback in Immersive Voice Programming (DreamCodeVR)**
*When an AI writes your code and it breaks, can you still tell whose mistake it was? In VR, speech is the only tool you have to find out.*
Wizard-of-Oz user study on how people understand, attribute, and recover from AI-generated code errors in VR. Extends a live voice-to-code system (speech to LLM to Unity C#, compiled in-scene) with three controlled feedback conditions: none, explanatory text panel, and embodied conversational agent. I contributed to the idea, implemented most of the technical work, and am now contributing to the study design. Manuscript in preparation, targeting CHI 2027.
[Repository](https://github.com/abyyworld/Real-Time-Immersive-Speech-Programming/tree/Visualisation-DreamCodeVR-feedback-loop)

**Omni-Connect / DeviceSphere: Cross-Device Interaction**
*Close your fist over a function on the laptop, open it toward the tablet, and it is there.*
A laptop, phone, and tablet operating as one connected workspace: native Unity coordination server plus zero-install WebGL clients over the local network. Gesture-driven cross-device copy-paste captured with Meta Project Aria 2 glasses, over a real-time WebSocket-to-UDP bridge. Infrastructure for two controlled user studies. Targeting CHI 2027.
[Repository](https://github.com/abyyworld/omni-connect)

**AgenticXR: Safe Agentic Authoring Inside Immersive Environments**
*Letting an AI edit the world you are standing in is only safe if it can be tested somewhere else first.*
A person in VR creates interactive behaviour by speaking, while AI agents generate, critique, and validate that behaviour before it is allowed to change the live scene. Builds on DreamCodeVR, originally developed at UCL. I own evaluation and deployment: the within-subjects study design, the study harness merged upstream, Quest deployment, and the first live speech-to-text validation. Targeting IEEE VR.

**LLM-Designed Affective VR Environments**
*Can an LLM design a room that reliably makes you feel calm, and does the shape of the room change the answer?*
Whether an LLM, constrained to a fixed pool of interior-design parameters, can compose virtual rooms that reliably induce a target emotion, and whether room shape moderates that effect. Contributed to ideation and research meetings, and built the technical system.

### Robot Learning & ML Infrastructure

**[Correlated Perception Error in Semantic 3D Mapping](https://github.com/abyyworld/erl-semantic-mapping)**
A 70%-accurate labeller builds a better map (0.560 mIoU) than an 85%-accurate one whose errors repeat by viewing angle (0.502). Standard accuracy benchmarks do not predict map quality, and can rank two models backwards. Seven CI checks recompute the headline numbers on every push.

**[Policy Evaluation & Statistical Comparison Harness](https://github.com/abyyworld/erl-vla-evals)**
A policy that looked 78% better than a do-nothing baseline was 27% worse than repeating the previous action, a rule that fits on one line. Returns better, worse, or underpowered, the last carrying the episodes needed to settle it.

**[Teleoperation Demonstration Pipeline](https://github.com/abyyworld/erl-teleop-pipeline)**
Nine signal-level checks identify a poor demonstration from the numbers alone, with no video review. Session-aware dataset splitting; every trained model pinned to a data revision and a commit.

**Fleet Deployment and Continual Improvement**
Over eight rounds a three-node fleet moves from 32% to 94%, uploading only 16% of collected data under a bandwidth budget. Canary rollout with automatic rollback.

**[LLM Bias Mini-Evaluation](https://github.com/abyyworld/llm-bias-mini-eval)**
Independent reimplementation of a directional gender-bias evaluation method from the literature, applied across BERT, RoBERTa, and GPT-2.

### Engineering

**[Cicatrixa](https://cicatrixa.com)** (founder): point it at any GitHub repo and it works out how to build it, wires a subdomain, verifies the deployment end-to-end, then stays on call. Every push redeploys; every crash is diagnosed and repaired automatically before the developer hears about it.

**[Role Radar](https://github.com/abyyworld/internship-tracker)**: continuously re-verified tracker of ~700 research, PhD, and postdoc postings, classified by category, region, term, and work-authorisation status. One-click evidence-checked CV tailoring that runs entirely on localhost; the public repo never receives the profile or generated documents. [Dashboard](https://abyyworld.github.io/internship-tracker/)

**Wind-Turbine Health Analytics**: drone-based computer vision classifying turbine conditions and detecting operational modes from aerial imagery. Pipeline from dataset preparation through training, evaluation, and production export. Built at Turin Polytechnic University in Tashkent.

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

`HCI` · `VR / XR` · `computer vision` · `applied ML` · `robot learning` · `multi-device systems`

---

[hello@akbarjuraev.com](mailto:hello@akbarjuraev.com) · [LinkedIn](https://www.linkedin.com/in/akbarjuraev/) · [X](https://x.com/theakbarjuraev)
