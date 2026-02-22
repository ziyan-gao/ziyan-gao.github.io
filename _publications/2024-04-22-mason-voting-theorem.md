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

.video-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
  margin: 20px 0;
}

.video-card {
  background: white;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
  transition: transform 0.3s ease;
}

.video-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 4px 16px rgba(0, 0, 0, 0.15);
}

.video-frame {
  width: 100%;
  height: 250px;
  border: none;
}

.video-info {
  padding: 15px;
}

.video-info h3 {
  margin: 0 0 10px 0;
  font-size: 16px;
  color: #333;
  font-weight: 600;
}

.video-info p {
  margin: 0;
  font-size: 13px;
  color: #666;
  line-height: 1.5;
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

<div class="video-grid">
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1zIFgAjFvJ-sTZPEceSKhlwwCW_vCPm2a/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Video 1</h3>
      <p>Center of Mass Estimation with Iterative Pushing demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1zXisrv5v5BCrk7-24e8J5M6QbaClIZQF/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Video 2</h3>
      <p>Center of Mass Estimation with Iterative Pushing demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1aTa6SsWfE-DLuSPWleAzKINX-BRgyG8X/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Video 3</h3>
      <p>Center of Mass Estimation with Iterative Pushing demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1WnkGDtclRXXZZsDXie-ZdHbkn5RWZFV2/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Video 4</h3>
      <p>Center of Mass Estimation with Iterative Pushing demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1k8v-mnx2H5hh896nN9bOGuYRvztORY7O/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Video 5</h3>
      <p>Center of Mass Estimation with Iterative Pushing demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1TdB7I0KibhH6A98gS_y_n_aIcYFhNGfM/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Video 6</h3>
      <p>Center of Mass Estimation with Iterative Pushing demonstration</p>
    </div>
  </div>
</div>

<p style="margin-top: 20px; color: #555; font-size: 14px; line-height: 1.6;">
  <strong>Description:</strong> This video demonstrates how the object center of mass (CoM) is estimated through iterative pusher-object interactions. The pushing actions are selected based on QP-EVT (Quadratic Program - Entropy and Variance Trade-off) based sampling strategy, which efficiently explores the object's contact surface to gather informative pushing "votes". The system uses vision sensing to track object motion and aggregates the voting results to accurately estimate the CoM without requiring prior knowledge of friction properties or object geometry.
</p>

## 🎬 Object Translation Videos

<div class="video-grid">
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1HMyeN1WHSbfIPQrga6ogmKWSSzyLQd6l/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Translation 1</h3>
      <p>Pure translational motion demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1yThwouZHcu5kH-oDD3LDYdp6vWrwLo_g/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Translation 2</h3>
      <p>Pure translational motion demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/17m1jSJtREG3CizrNqUutRcXrQC5q2fj4/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Translation 3</h3>
      <p>Pure translational motion demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1ALwpiMiLoB4criFoXO6XFkTU1gQWi5m5/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Translation 4</h3>
      <p>Pure translational motion demonstration</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1uuVp1B9Y5f4xR_EI_kKm_rAtDq2O2bz0/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Translation 5</h3>
      <p>Pure translational motion demonstrationn</p>
    </div>
  </div>
  <div class="video-card">
    <iframe class="video-frame" src="https://drive.google.com/file/d/1sncVoxXMFHATGlHRE5Sw2ZAdMY1AYftR/preview" allow="autoplay"></iframe>
    <div class="video-info">
      <h3>Translation 6</h3>
      <p>Pure translational motion demonstration</p>
    </div>
  </div>
</div>

<p style="margin-top: 20px; color: #555; font-size: 14px; line-height: 1.6;">
  <strong>Description:</strong> These videos showcase pure translational motion of objects during pushing interactions. The contact configurations between the pusher and the object were sampled based on modified Zero Moment Two Edge Pushing (ZMTEP) method.
</p>

## 📄 Publication Details

**Authors:** Ziyan Gao, Alp Elibol, Nak Young Chong

**Venue:** IEEE Transactions on Robotics

**Volume:** 40

**Pages:** 2656-2671

**Publication Date:** 2024-04-22

**DOI:** [Read on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/10506568/)
