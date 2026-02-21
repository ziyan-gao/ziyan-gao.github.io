---
title: "Zero moment two edge pushing of novel objects with center of mass estimation"
collection: publications
category: manuscripts
author_position: "First Author"
permalink: /publication/2022-09-29-zero-moment-two-edge-pushing
excerpt: 'Pushing is one of the fundamental nonprehensile manipulation skills. This work estimates the center of mass of an object and proposes the Zero Moment Two Edge Pushing method to translate a novel object without rotation to a goal pose.'
date: 2022-09-29
venue: 'IEEE Transactions on Automation Science and Engineering'
volume: 20
issue: 3
pages: '1487-1499'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/9905658/'
citation: 'Gao, Z., Elibol, A., & Chong, N. Y. (2022). Zero moment two edge pushing of novel objects with center of mass estimation. IEEE Transactions on Automation Science and Engineering, 20(3), 1487-1499.'
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

.section-box h3 {
  margin-top: 0;
  color: #333;
  font-size: 18px;
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
  <h1>🤖 Zero Moment Two Edge Pushing (ZMTEP)</h1>
  <p style="margin: 10px 0 0 0; font-size: 16px;">Nonprehensile manipulation for precise object translation without rotation using center of mass estimation</p>
  <div class="tags">
    <span class="tag">Robot Manipulation</span>
    <span class="tag">Pushing</span>
    <span class="tag">Nonprehensile Manipulation</span>
    <span class="tag">Center of Mass Estimation</span>
    <span class="tag">Motion Control</span>
  </div>
</div>

## 📋 Overview

This work addresses the challenge of translating novel objects to goal positions without causing undesired rotations. By combining center of mass estimation with the Zero Moment Two Edge Pushing (ZMTEP) strategy, the method enables a robot manipulator to achieve precise object positioning even with unknown object properties. The approach leverages the concept of zero moment manipulation, where pushing forces are applied at specific contact points to ensure pure translational motion.

<div class="section-box">
  <h3>Key Contributions</h3>
  <ul class="features">
    <li>Development of Zero Moment Two Edge Pushing (ZMTEP) method for rotation-free translation</li>
    <li>Integration of center of mass estimation with pushing strategy selection</li>
    <li>Methodology applicable to novel objects without prior geometric or physical knowledge</li>
    <li>Experimental validation on diverse object geometries</li>
    <li>Practical framework for robotic nonprehensile manipulation tasks</li>
  </ul>
</div>

## 🎨 Methodology

The Zero Moment Two Edge Pushing method selects pushing configurations based on the estimated center of mass and desired motion direction. By applying forces at two strategically chosen contact edges while maintaining zero moment about the object's center, the method ensures pure translational motion without rotation.

<div class="highlight-box">
  <strong>Key Concept:</strong> The method pushes at two contact points positioned symmetrically with respect to the center of mass projection, creating equal and opposite moment components that cancel out, resulting in pure translation to the goal position.
</div>

## 🎥 Demonstration Videos

<div class="video-container">
  <div class="video-title">Video 2: Object Displacement to Target Position using Modified ZMTEP</div>
  <iframe src="https://1drv.ms/v/c/02d31ff9b580407b/IQA1ZEvS36mYR7nYT-AU1wVTAeSaNV02m1zEc9mNVwlqoMk?e=bWoSHL&embed=true" width="100%" height="480" allow="autoplay"></iframe>
  
  <p style="margin-top: 15px; color: #555; font-size: 14px;">
    <strong>Description:</strong> This video demonstrates the Zero Moment Two Edge Pushing (ZMTEP) method in action. Objects are precisely displaced from their initial positions to target locations marked by red dots. The pushing configuration at each step is selected based on the modified ZMTEP strategy, which uses the estimated center of mass to determine optimal contact points. The robot executes a series of coordinated pushing actions to navigate the object to the goal pose while maintaining rotational stability throughout the manipulation process.
  </p>
</div>

## 📄 Publication Details

**Authors:** Ziyan Gao, Alp Elibol, Nak Young Chong

**Venue:** IEEE Transactions on Automation Science and Engineering

**Volume:** 20

**Issue:** 3

**Pages:** 1487-1499

**Publication Date:** 2022-09-29

**DOI:** [Read on IEEE Xplore](https://ieeexplore.ieee.org/abstract/document/9905658/)
