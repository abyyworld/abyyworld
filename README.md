# Akbar Juraev

**Robotics & Software Engineer · Human-AI Interaction Researcher @ Birmingham**

BSc AI & CS @ **UoB** · HCI research @ **VR Lab** · **BhamXR** · **IEEE VR**

Co-author on a paper under review at **IEEE VR 2027**; **first author** on one in preparation for **ACM UIST 2027**.

**[akbarjuraev.com](https://www.akbarjuraev.com)** · [CV](https://www.akbarjuraev.com/cv.pdf) · [ORCID](https://orcid.org/0009-0008-7883-6699)

---

### Research

**Error Feedback in Immersive Voice Programming (DreamCodeVR)**
*When an AI writes your code and it breaks, can you still tell whose mistake it was? In VR, speech is the only tool you have to find out.*
Wizard-of-Oz user study on how people understand, attribute, and recover from AI-generated code errors in VR. Extends a live voice-to-code system (speech to LLM to Unity C#, compiled in-scene) with three controlled feedback conditions: none, explanatory text panel, and embodied conversational agent. I contributed to the idea, implemented most of the technical work, and am now contributing to the study design. Manuscript in preparation.
[Repository](https://github.com/abyyworld/say-it-again/tree/Visualisation-DreamCodeVR-feedback-loop)

**Omni-Connect / DeviceSphere: Cross-Device Interaction**
*Close your fist over a function on the laptop, open it toward the tablet, and it is there.*
A laptop, phone, and tablet operating as one connected workspace: native Unity coordination server plus zero-install WebGL clients over the local network. Gesture-driven cross-device copy-paste captured with Meta Project Aria 2 glasses, over a real-time WebSocket-to-UDP bridge. Infrastructure for two controlled user studies. In preparation, targeting **ACM UIST 2027**.
[Repository](https://github.com/abyyworld/omni-connect)

**AgenticXR: Safe Agentic Authoring Inside Immersive Environments**
*Letting an AI edit the world you are standing in is only safe if it can be tested somewhere else first.*
A person in VR creates interactive behaviour by speaking, while AI agents generate, critique, and validate that behaviour before it is allowed to change the live scene. Generated code runs against a hidden clone of its target before it can touch the live scene. Builds on DreamCodeVR, originally developed at UCL. I'm a co-author; my code contribution made the server install on Apple Silicon and documented the macOS host setup. Submitted to **IEEE VR 2027**, under review.

**LLM-Designed Affective VR Environments**
*Can an LLM design a room that reliably makes you feel calm, and does the shape of the room change the answer?*
Whether an LLM, constrained to a fixed pool of interior-design parameters, can compose virtual rooms that reliably induce a target emotion, and whether room shape moderates that effect. Contributed to ideation and research meetings, and built the technical system.

### Robot Learning & ML Infrastructure

**[Credit Assignment in Interactive Imitation Learning](https://github.com/abyyworld/Interactive-correction-for-manipulation)**
Correcting a robot where a failure first becomes visible reached 42.0% success, over 9x correcting at its cause, across 1,000 episodes (250 per condition, p = 2.2e-17): the robot has to see the failure to learn the recovery. Holding demonstration coverage fixed across all four conditions is the control that settled the ordering.

**[Vision-Based Grasping and the Generalisation Gap](https://github.com/abyyworld/Simulated-grasping)**
A fully convolutional network scores grasps at every pixel and 12 gripper angles from a single depth image, trained on 15,000 self-supervised grasp labels with no human annotation. An ablation showed where to grip transfers to new objects, while grip angle needs its own signal.

**[Correlated Perception Error in Semantic 3D Mapping](https://github.com/abyyworld/erl-semantic-mapping)**
A 70%-accurate labeller builds a better map (0.560 mIoU) than an 85%-accurate one whose errors repeat by viewing angle (0.502). Standard accuracy benchmarks do not predict map quality, and can rank two models backwards. Seven CI checks recompute the headline numbers on every push.

**[Policy Evaluation & Statistical Comparison Harness](https://github.com/abyyworld/vla-evals)**
Diagnosed from the data why offline accuracy (98.0% on gripper actions) does not predict closed-loop success: the teleoperation demonstrations never recorded the goal. The harness catches this: provenance-checked checkpoints, four closed-loop benchmark tasks, and paired comparisons that name a winner only when the difference is resolved.

**[Teleoperation Demonstration Pipeline](https://github.com/abyyworld/teleop-pipeline)**
Signal-level checks identify a poor demonstration from the numbers alone, with no video review. Session-aware dataset splitting; every trained model pinned to a data revision and a commit.

**[Fleet Learning Loop](https://github.com/abyyworld/robot-fleet-loop)**
A simulated three-node fleet moved from 32% to 94% success over eight rounds while uploading only 16% of the data it collected. Canary rollout with automatic rollback.

**[LLM Bias Mini-Evaluation](https://github.com/abyyworld/llm-bias-mini-eval)**
Independent reimplementation of a directional gender-bias evaluation method from the literature, applied across BERT, RoBERTa, and GPT-2.

### Engineering

**[Cicatrixa](https://github.com/abyyworld/Cicatrixa)**: a self-healing deployment system. It detects a crash in an app and pins the cause to a line, refuses to patch until it has written a failing test that reproduces the bug in a throwaway container, and accepts the patch only once that test passes and the existing suite stays green. The fix ships behind a canary that promotes or rolls back on error rate.

**[Role Radar](https://github.com/abyyworld/internship-tracker)**: job tracker with over 3,000 open roles re-checked daily against each employer's own board, so closed roles drop out on their own, classified by category, region, term, and work-authorisation status. One-click evidence-checked CV tailoring that runs entirely on localhost; the public repo never receives the profile or generated documents. [Dashboard](https://abyyworld.github.io/internship-tracker/)

**Drone EduTrain** (Robotics & Software Engineer, Tashkent): built the drone inspection app the company demos to investors. Detection runs on the handheld itself with no network, as an Android build and an offline browser version, and tracking counts each person once rather than once per frame.

**[Wind-Turbine Health Analytics](https://github.com/abyyworld/Drone-visualisation-training)**: drone-based computer vision classifying turbine conditions and detecting operational modes from aerial imagery. Pipeline from dataset preparation through training, evaluation, and production export. Built at Turin Polytechnic University in Tashkent.

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-000000?style=flat&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat&logo=c-sharp&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=cplusplus&logoColor=white)
![ROS](https://img.shields.io/badge/ROS_2-22314E?style=flat&logo=ros&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

`software engineering` · `applied ML` · `robot learning` · `computer vision` · `HCI` · `VR / XR` · `deployment & MLOps`

---

[hello@akbarjuraev.com](mailto:hello@akbarjuraev.com) · [LinkedIn](https://www.linkedin.com/in/akbarjuraev/) · [X](https://x.com/theakbarjuraev)
