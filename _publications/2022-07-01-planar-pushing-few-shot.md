---
title: "A few-shot learning framework for planar pushing of unknown objects"
collection: publications
category: manuscripts
author_position: "First Author"
permalink: /publication/2022-07-planar-pushing-few-shot
excerpt: 'Presents a few-shot learning framework for robot planar pushing with a new large dataset and novel representation for pushing primitives, including computation efficient planning method.'
date: 2022-07-01
venue: 'Intelligent Service Robotics'
volume: 15
issue: 3
pages: '335-350'
paperurl: 'https://link.springer.com/article/10.1007/s11370-022-00425-7'
citation: 'Gao, Z., Elibol, A., & Chong, N. Y. (2022). A few-shot learning framework for planar pushing of unknown objects. Intelligent Service Robotics, 15(3), 335-350.'
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

.summary-box {
  background: #f0f7ff;
  border-left: 4px solid #667eea;
  padding: 20px;
  margin-bottom: 25px;
  border-radius: 4px;
  line-height: 1.8;
}

.summary-box p {
  margin: 12px 0;
  color: #333;
  font-size: 15px;
}

.video-container {
  margin: 30px 0;
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

.highlight-box {
  background: #fff3cd;
  border: 1px solid #ffeaa7;
  padding: 15px;
  border-radius: 4px;
  margin: 15px 0;
}
</style>

<div class="project-header">
  <h1>🤖 Few-Shot Learning for Planar Pushing</h1>
  <p style="margin: 10px 0 0 0; font-size: 16px;">Learning to push novel objects with limited prior interactions using simulation and few-shot learning</p>
  <div class="tags">
    <span class="tag">Few-Shot Learning</span>
    <span class="tag">Robot Pushing</span>
    <span class="tag">Motion Prediction</span>
    <span class="tag">Simulation-to-Reality</span>
    <span class="tag">Deep Learning</span>
  </div>
</div>

## 📋 Overview

<div class="summary-box">
  <p>This work presents a <strong>few-shot learning framework for planar pushing of novel objects</strong> with unknown physical properties, including center of mass (CoM), friction, and inertia.</p>
  
  <p>We introduce <strong>SimPush</strong>, a large-scale simulation dataset containing <strong>over two million pushes</strong> across diverse object shapes and physical configurations.</p>
  
  <p>Based on this dataset, we develop an <strong>attention-based encoder–decoder model</strong> that leverages a small number of prior push interactions to predict object motion (Δx, Δy, Δθ) together with uncertainty estimates.</p>
  
  <p>Building on the predicted push affordances, we propose an <strong>uncertainty-aware planning strategy</strong> that efficiently selects pushing actions to translate objects to target poses.</p>
  
  <p>The method achieves <strong>accurate motion prediction in simulation</strong> and <strong>successfully transfers to real-world experiments without real-data training</strong>, while requiring fewer push steps than baseline methods.</p>
</div>

## 🎯 Key Contributions

<div class="highlight-box">
  <ul style="margin: 0; padding-left: 20px; color: #333;">
    <li>Large-scale SimPush dataset with over 2 million pushing interactions</li>
    <li>Few-shot learning framework that adapts to novel objects with minimal prior interactions</li>
    <li>Attention-based encoder-decoder architecture for motion prediction with uncertainty estimation</li>
    <li>Uncertainty-aware planning strategy for efficient object manipulation</li>
    <li>Successful sim-to-real transfer without requiring real-world training data</li>
  </ul>
</div>

## 🎥 Demonstration Videos

<div class="video-container">
  <div class="video-title">Planning Strategy Comparison: Proposed Method vs. Greedy Strategy</div>
  <iframe src="https://drive.google.com/file/d/1c5nbvpmIMkNyRGXL-AqVLPwwoGBe-c5j/preview" style="width: 100%; height: 480px; border: none;" allow="autoplay"></iframe>
  
  <p style="margin-top: 15px; color: #555; font-size: 14px;">
    <strong>Description:</strong> This video demonstrates the benefits of the proposed uncertainty-aware pushing planning method compared with a greedy pushing strategy. The comparison shows how our method, which leverages predicted motion affordances and uncertainty estimates, can achieve the goal more efficiently with fewer pushing steps. The greedy strategy, which selects actions based only on immediate progress toward the goal, requires significantly more interactions. This highlights the value of considering uncertainty in planning and making more informed pushing decisions to guide objects to target poses.
  </p>
</div>

## 📄 Publication Details

**Authors:** Ziyan Gao, Alp Elibol, Nak Young Chong

**Venue:** Intelligent Service Robotics

**Volume:** 15

**Issue:** 3

**Pages:** 335-350

**Publication Date:** 2022-07-01

**DOI:** [Read on Springer Link](https://link.springer.com/article/10.1007/s11370-022-00425-7)
