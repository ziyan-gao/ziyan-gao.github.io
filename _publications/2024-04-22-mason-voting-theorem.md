---
title: "On the generality and application of mason's voting theorem to center of mass estimation for pure translational motion"
collection: publications
category: manuscripts
author_position: "First Author"
permalink: /publication/2024-04-22-mason-voting-theorem
excerpt: 'Extends Mason Voting Theorem to object center of mass estimation in the absence of accurate information on friction and object shape using a position-controlled robot arm and vision sensor.'
date: 2024-04-22
venue: 'IEEE Transactions on Robotics'
volume: 40
pages: '2656-2671'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10506568/'
citation: 'Gao, Z., Elibol, A., & Chong, N. Y. (2024). On the generality and application of mason''s voting theorem to center of mass estimation for pure translational motion. IEEE Transactions on Robotics, 40, 2656-2671.'
---

<style>
.project-header {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 30px 20px;
  border-radius: 8px;
  margin-bottom: 30px;
}

.project-header h1 {
  margin: 0;
  font-size: 28px;
  font-weight: 600;
}

.tags {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 15px;
}

.tag {
  background: rgba(255, 255, 255, 0.2);
  color: white;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 13px;
  font-weight: 500;
}

.section-box {
  border-left: 4px solid #667eea;
  padding: 20px;
  margin-bottom: 25px;
  background: #f8f9fa;
  border-radius: 4px;
}

.section-box h2 {
  margin-top: 0;
  color: #333;
  font-size: 20px;
}

.highlight-box {
  background: #fff3cd;
  border: 1px solid #ffeaa7;
  padding: 15px;
  border-radius: 4px;
  margin: 15px 0;
}

.features {
  list-style: none;
  padding-left: 0;
}

.features li {
  padding: 8px 0;
  padding-left: 30px;
  position: relative;
}

.features li:before {
  content: "✓";
  position: absolute;
  left: 0;
  color: #667eea;
  font-weight: bold;
  font-size: 16px;
}
</style>

<div class="project-header">
  <h1>🤖 Mason's Voting Theorem for Center of Mass Estimation</h1>
  <p style="margin: 10px 0 0 0; font-size: 16px;">Extending Mason Voting Theorem to robust center of mass estimation under uncertainty in friction and object geometry</p>
  <div class="tags">
    <span class="tag">Robot Manipulation</span>
    <span class="tag">Pushing</span>
    <span class="tag">Center of Mass Estimation</span>
    <span class="tag">Motion Planning</span>
    <span class="tag">Robotic Vision</span>
  </div>
</div>

## 📋 Overview

This work extends Mason's Voting Theorem to object center of mass estimation during pure translational motion, addressing the challenge of estimating center of mass when accurate information on friction and object shape is unavailable. By leveraging a position-controlled robot arm combined with vision sensing, the method provides a robust and generalizable approach to center of mass estimation.

<div class="section-box">
  <h3>Key Contributions</h3>
  <ul class="features">
    <li>Theoretical generalization of Mason Voting Theorem for center of mass estimation</li>
    <li>Robust estimation methodology independent of friction model and object geometry</li>
    <li>Integration of vision-based sensing with robotic manipulation</li>
    <li>Position-controlled pushing experiments validating the approach</li>
    <li>Practical applicability for robotic object manipulation tasks</li>
  </ul>
</div>

## 🎨 Methodology Overview

![Methodology Overview](https://ziyan-gao.github.io/images/2024-04-22-mason-voting-theorem.png)

<div class="highlight-box">
  <strong>Figure 1: Mason Voting Theorem Application</strong><br>
  The proposed approach demonstrates how Mason Voting Theorem can be generalized to estimate the center of mass of objects under pure translational motion. By applying pushing motions at various contact points and observing the resulting object trajectories using vision sensing, the method aggregates these "votes" to accurately determine the center of mass, even without precise knowledge of friction coefficients or object geometry. This voting-based approach provides robustness and generalizability across different object shapes and surface properties.
</div>

## 📄 Publication Details

**Authors:** Ziyan Gao, Alp Elibol, Nak Young Chong

**Venue:** IEEE Transactions on Robotics

**Volume:** 40

**Pages:** 2656-2671

**Publication Date:** 2024-04-22

**DOI:** [Read on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10506568/)
