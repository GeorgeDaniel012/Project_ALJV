# Project ALJV - Learning Agents Shooter Prototype

## 📖 Overview
**Project ALJV** is a 2-team shooter simulation prototype built in **Unreal Engine 5**. The project focuses on emergent combat behavior by utilizing the **Learning Agents** plugin to train AI bots dynamically via Reinforcement Learning.

## 🛠 Tech Stack & Tools

* **Engine:** Unreal Engine `5.7.4`
* **AI & Machine Learning:** Learning Agents Plugin
* **Algorithm:** Proximal Policy Optimization (PPO)
* **Scripting:** Blueprints (Visual Scripting)

## ✨ Key Features

* **Multi-Agent Combat Simulation:** Features an active 8v8 battleground (Team Red vs. Team Blue), where all 16 robotic agents are driven simultaneously by reinforcement learning models.
* **Asymmetric Observation Logic:** The teams evaluate the environment differently to simulate varied tactical approaches:
  * **Team Red:** Focuses its observations on prioritizing and engaging the closest visible enemy.
  * **Team Blue:** Takes into account the spatial positioning and layout of all active enemies on the field.
* **Custom Reward Function:** Agents optimize their behavior based on a precise reward/penalty system. They receive positive rewards for successful eliminations (calculated via accurate line-trace intersections with enemies) and negative rewards (penalties) for friendly fire.
* **Continuous Runtime Learning:** Bots do not just rely on pre-trained models; they learn and adapt their policies organically over continuous epochs as the simulation plays out.
* **Real-Time Scoreboard:** Features a live UI system to track team performance, specifically kills.

## 👥 The Team

This project was created by:

* **Codarcea Alexandru-Christian**
* **Velișan George-Daniel**
