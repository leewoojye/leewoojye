## Welcome 환영해요 ようこそ Bienvenue. bienvenido 欢迎 مرحبا بكم

### ☕️ I’m currently working on
- (2026.07 ~) Korea University, Seoul (Department of Artificial Intelligence)
- (2020.03 ~ 2026.07) Dongguk University, Seoul (B.S. in Department of Computer Science and AI)

### ☕️ Research interests and current studies (Updated November 20, 2026)
- Surgical video perception. I study how to detect and segment regions marked by indocyanine green (ICG) in endoscopic video, then track the same tissue as it deforms, moves behind an instrument, or loses its visible fluorescence.
- Data-efficient robot learning. I’m interested in which cues from first-person human demonstrations transfer to robotic manipulation, especially when only a small set of robot videos is available.
- Motion planning and control. I study model predictive path integral control (MPPI) in MuJoCo, with a focus on planning smooth tool motion under the kinematic constraints of surgical manipulators.
- Medical vision–language models. I study whether a model’s response changes when a lesion is removed but the surrounding anatomy stays the same. In TaSA, I worked on constructing these image pairs and evaluating whether image–text similarity reflected lesion presence.

### 🔬 Selected experiments (Updated November 20, 2026)
- Tracking tissue after the fluorescence fades. I compared point tracking with SAM 2 mask propagation on endoscopic video. In one low-contrast sequence, the point tracker lost all its tracked points, while the propagated mask sometimes expanded onto neighboring tissue. That observation shapes how I evaluate tracking: a mask can persist even when it follows the wrong tissue.
- Needle reaching in simulation. I built a teleoperation demo for the da Vinci Research Kit’s patient-side manipulator. It reports both tool-tip error and deviation from the remote center of motion, so I can see when improving one comes at the expense of the other. MuJoCo demo
- Learning from first-person video. I compared DreamDojo-2B and Cosmos-Predict 2.5 on the same surgical clips, using the first frame to predict the next 12. Holding the training budget fixed let me test how much the choice of pretrained model mattered on a small dataset.

### ☕️ Research interests and current studies (Jun 28, 2026)
- Robot Intelligence: physics-based simulation, trajectory optimization, and motion learning.
- Human-Robot Alignment: imitation learning, VLA models, and embodiment-agnostic representations.
- Medical AI & Computer Vision: medical vision-language models and data-efficient segmentation.
- Analogical Reasoning: cross-domain methods inspired by robotics, physics, and nature.
 
###  ☕️ Here's my favorite STA buCKS menu ☕️ 
<p float="left">
<img src="https://img.shields.io/badge/huggingface-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black">
<img src="https://img.shields.io/badge/buymeacoffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black">
<br>
<img src="https://img.shields.io/badge/pytorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white">
<img src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=Swift&logoColor=white"/>
<br>
<img src="https://img.shields.io/badge/c++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white">
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/mujoco-0F4C81?style=for-the-badge&logo=deepmind&logoColor=white" alt="MuJoCo badge">
<br>
<img src="https://img.shields.io/badge/coffeescript-2F2625?style=for-the-badge&logo=coffeescript&logoColor=white">
</p>

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=whitehole36)](https://solved.ac/whitehole36/)

<!-- [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=leewoojye&layout=compact&theme=dark)](https://github.com/anuraghazra/github-readme-stats)
-->

<!--
**leewoojye/leewoojye** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
[![leewoojye's GitHub stats](https://github-readme-stats.vercel.app/api?username=leewoojye&show_icons=true&theme=dark)](https://github.com/anuraghazra/github-readme-stats)
Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
