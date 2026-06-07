<div align="center">

<h1>Baodewen</h1>

<p>
  <strong>Reinforcement Learning · Robot Navigation · Safe Control</strong>
</p>

<p>
  Research-oriented engineering for path planning, learning-based decision-making, and safety-aware robotic control.
</p>

<p>
  <a href="https://github.com/Baodewen">
    <img src="https://img.shields.io/badge/GitHub-Baodewen-181717?style=for-the-badge&logo=github" alt="GitHub Profile" />
  </a>
  <a href="https://github.com/Baodewen?tab=repositories">
    <img src="https://img.shields.io/badge/Repositories-Research%20Projects-0969DA?style=for-the-badge" alt="Repositories" />
  </a>
</p>

<p>
  <img src="https://img.shields.io/badge/Python-Primary-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/PPO-Reinforcement%20Learning-2EA44F?style=flat-square" alt="PPO" />
  <img src="https://img.shields.io/badge/D*%20Lite-Path%20Replanning-1F6FEB?style=flat-square" alt="D* Lite" />
  <img src="https://img.shields.io/badge/PID-Safety%20Aware%20Control-8250DF?style=flat-square" alt="PID Control" />
  <img src="https://img.shields.io/badge/FastAPI-Robot%20Workbench-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
</p>

</div>

---

## About

I focus on building small but complete research-oriented systems for robotic navigation and control.

My current work connects three ideas:

<table>
  <tr>
    <td width="33%">
      <strong>Incremental Replanning</strong><br/>
      Repairing paths efficiently when local edge states or obstacle information change.
    </td>
    <td width="33%">
      <strong>Learning-Based Navigation</strong><br/>
      Using reinforcement learning to study state design, reward shaping, policy behavior, and navigation robustness.
    </td>
    <td width="33%">
      <strong>Safety-Aware Control</strong><br/>
      Combining learned decision modules with explicit safety guards and interpretable control logic.
    </td>
  </tr>
</table>

---

## Featured Projects

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Visibility-Constrained Edge-State D* Lite Replanning</h3>
      <p>
        A grid-based incremental replanning method for near-obstacle navigation, built around visibility constraints, edge-state updates, and D* Lite-style path repair.
      </p>
      <p>
        <strong>Focus</strong><br/>
        Path planning · Incremental search · Local visibility · Dynamic edge states
      </p>
      <p>
        <a href="https://github.com/Baodewen/Visibility-Constrained-Edge-State-D-Lite-Replanning">
          <img src="https://img.shields.io/badge/Open-Repository-0969DA?style=flat-square" alt="Open Repository" />
        </a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>Safety-Guarded RL-Modulated PID Control</h3>
      <p>
        A safety-aware control prototype where reinforcement learning modulates PID behavior instead of directly replacing the controller.
      </p>
      <p>
        <strong>Focus</strong><br/>
        PPO · PID modulation · Safety guard · Corridor navigation
      </p>
      <p>
        <a href="https://github.com/Baodewen/Safety-Guarded-RL-Modulated-PID-Control">
          <img src="https://img.shields.io/badge/Open-Repository-2EA44F?style=flat-square" alt="Open Repository" />
        </a>
      </p>
    </td>
    <td width="33%" valign="top">
      <h3>RL-Based Robot Obstacle Avoidance</h3>
      <p>
        A complete reinforcement learning navigation workbench covering map generation, LiDAR-style sensing, PPO training, evaluation, visualization, and a Web console.
      </p>
      <p>
        <strong>Focus</strong><br/>
        Mobile robot · LiDAR observation · PPO · Pygame · FastAPI
      </p>
      <p>
        <a href="https://github.com/Baodewen/Reinforcement-Learning-Based-Robot-Obstacle-Avoidance">
          <img src="https://img.shields.io/badge/Open-Repository-BE4BDB?style=flat-square" alt="Open Repository" />
        </a>
      </p>
    </td>
  </tr>
</table>

---

## Research Style

<table>
  <tr>
    <td width="25%">
      <strong>Clear Problem Formulation</strong><br/>
      I prefer projects with explicit states, actions, constraints, and evaluation logic.
    </td>
    <td width="25%">
      <strong>Algorithm-Centered Design</strong><br/>
      The core method should remain visible instead of being hidden behind unnecessary interface complexity.
    </td>
    <td width="25%">
      <strong>Reproducible Workflow</strong><br/>
      Training, evaluation, visualization, and quick-start scripts should form a complete loop.
    </td>
    <td width="25%">
      <strong>Safety-Oriented Thinking</strong><br/>
      I am interested in methods where learned behavior is constrained by interpretable safety rules.
    </td>
  </tr>
</table>

---

</div>
