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

.video-container {
  margin: 20px 0;
  padding: 20px;
  background: #f0f0f0;
  border-radius: 4px;
}

.video-title {
  font-weight: 600;
  font-size: 16px;
  margin-bottom: 10px;
  color: #333;
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

## 🎥 Demonstration Videos

<div class="video-container">
  <div class="video-title">Video 1: Center of Mass Estimation with Iterative Pushing</div>
  <a href="https://1drv.ms/v/c/02d31ff9b580407b/IQACACWMGN-BQZLJ_a4BsSRtAXn4ixXG6ToyYI6bPsZx1pk?e=BwFEZi" target="_blank" style="display: inline-block; padding: 12px 20px; background: #667eea; color: white; border-radius: 4px; text-decoration: none; font-weight: 600;">▶ Watch Video 1</a>
  
  <p style="margin-top: 15px; color: #555; font-size: 14px;">
    <strong>Description:</strong> This video demonstrates how the object center of mass (CoM) is estimated through iterative pusher-object interactions. The pushing actions are selected based on QP-EVT (Quadratic Program - Entropy and Variance Trade-off) based sampling strategy, which efficiently explores the object's contact surface to gather informative pushing "votes". The system uses vision sensing to track object motion and aggregates the voting results to accurately estimate the CoM without requiring prior knowledge of friction properties or object geometry.
  </p>
</div>

<div class="video-container">
  <div class="video-title">Video 2: Object Displacement to Target Location using Modified Zero Moment Two Edge Pushing</div>
  <a href="https://1drv.ms/v/c/02d31ff9b580407b/IQA1ZEvS36mYR7nYT-AU1wVTAeSaNV02m1zEc9mNVwlqoMk?e=VzgPez" target="_blank" style="display: inline-block; padding: 12px 20px; background: #667eea; color: white; border-radius: 4px; text-decoration: none; font-weight: 600;">▶ Watch Video 2</a>
  
  <p style="margin-top: 15px; color: #555; font-size: 14px;">
    <strong>Description:</strong> This video demonstrates how objects are efficiently displaced to target locations using modified zero moment two edge pushing. After the center of mass has been estimated using Mason Voting Theorem, the control strategy leverages this knowledge to plan and execute pushing motions that move the object to desired goal positions while maintaining stability and predictability throughout the manipulation task.
  </p>
</div>

<div class="video-container">
  <div class="video-title">Video 3: IROS 2024 Oral Presentation</div>
  <a href="https://1drv.ms/v/c/02d31ff9b580407b/IQA8_wy67Y5dSrIAtE9WOHGkAYVyVU469YfOHOUW4GiBSf4?e=d91cYS" target="_blank" style="display: inline-block; padding: 12px 20px; background: #667eea; color: white; border-radius: 4px; text-decoration: none; font-weight: 600;">▶ Watch Video 3</a>
  
  <p style="margin-top: 15px; color: #555; font-size: 14px;">
    <strong>Description:</strong> This is the oral presentation delivered at IROS 2024 introducing the paper on Mason's Voting Theorem for center of mass estimation. The presentation covers the theoretical foundations, methodological innovations, and experimental validation of the approach for robust object center of mass estimation during pure translational motion.
  </p>
</div>

## 📄 Publication Details

**Authors:** Ziyan Gao, Alp Elibol, Nak Young Chong

**Venue:** IEEE Transactions on Robotics

**Volume:** 40

**Pages:** 2656-2671

**Publication Date:** 2024-04-22

**DOI:** [Read on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10506568/)
