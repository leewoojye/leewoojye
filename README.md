## Welcome 환영해요 ようこそ Bienvenue. bienvenido 欢迎 مرحبا بكم

### ☕️ I’m currently working on
- (2026.07 ~) Korea University, Seoul (Department of Artificial Intelligence)
- (2020.03 ~ 2026.07) Dongguk University, Seoul (B.S. in Department of Computer Science and AI)

### ☕️ Research interests and current studies (Updated November 20, 2026)
- **Surgical video perception.** I study how to detect and segment regions marked by indocyanine green (ICG) in endoscopic video and track the same tissue through deformation, occlusion, and changes in fluorescence.
- **Data-efficient robot learning.** I’m interested in what first-person videos of human manipulation can teach a robot, especially when only a small set of robot demonstrations is available.
- **Motion planning and control.** I use MuJoCo to study model predictive path integral control (MPPI) for surgical manipulators. One constraint I work with is that the instrument shaft must pivot around a fixed entry point as its tip moves.
- **Medical vision–language models.** In TaSA(Target-State Matching Preference Optimization for Vision--Language Alignment in Context-Sharing Domains
), I helped construct pairs of medical images with and without a target lesion and tested whether image–text similarity changed when the lesion was removed.

### 🔬 Selected experiments (Updated November 20, 2026)
- **Tracking tissue after fluorescence fades.** I compared point tracking with SAM 2 mask propagation on endoscopic video. In one low-contrast sequence, the point tracker lost all 16 tracked points. The mask persisted longer but sometimes spread onto neighboring tissue. That distinction matters for a surgical overlay: a mask can stay visible even after it has lost the original target.
- **Needle reaching in simulation.** I built a teleoperation demo for the da Vinci Research Kit’s patient-side manipulator. The demo displays two errors as the instrument moves: how far the tip is from the needle target and how far the shaft deviates from its intended pivot. [Explore the MuJoCo demo](https://github.com/leewoojye/myjoco_playground)
- **Predicting surgical video from a single frame.** I compared DreamDojo-2B and Cosmos-Predict 2.5 on the same surgical clips, giving each model the first frame and asking it to predict the next 12. Using the same training budget let me examine what a model pretrained on first-person human video could transfer to a surgical scene.

⭐️ I write about my experiments and the papers behind them on my [research blog](https://leewoojye.github.io/blog). ⭐️

### ☕️ Other research topics of interest (Updated Jun 28, 2026)
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
