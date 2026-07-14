---
layout: default
title: Home
---

RobuO is the Robotics at uOttawa research cluster. We are an interdisciplinary group of uOttawa faculty and students focused on robotics, control and intelligent systems. We develop deployable robotic and control systems with combined sensing, control, and learning. Our cluster maintains a strong engagement in industry and government applications.

RobuO brings together faculty across Mechanical Engineering, Electrical Engineering and Computer Science working on applied robotics and AI.

---

## People


<div class="grid">
{% for pi in site.data.pis %}
  <div class="card">
    <h3>
      <a href="{{ pi.url }}">
        {{ pi.name }}
      </a>
    </h3>
    <p>{{ pi.lab }}</p>
  </div>
{% endfor %}
</div>



---

## Research Areas

- **Robotic Systems & Automation**  
  Autonomous navigation, manipulation, and multi-agent systems

- **AI & Robot Learning**  
  Reinforcement learning, adaptive control, and sim-to-real transfer

- **Sensing & Perception**  
  Machine vision, multimodal sensing, and instrumentation

---

## Opportunities

We train undergraduate and graduate students in robotics and AI through hands-on projects, industry collaborations, and applied research.

We welcome partnerships with industry and government organizations.

---