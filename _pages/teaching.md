---
layout: page
permalink: /research/
title: research
description: 
nav: true
nav_order: 1
---
My research focuses on leveraging a synergistic combination of `Hardware` and `AI` to enable user-independent, data-efficient recognition of diverse time-series signals, including Force, IMU, and EMG from body joints and muscles. <br>
The goal is to develop, energy-efficient wearable devices that enhance human-computer interaction, leveraging high-quality sensor datasets and `adaptable AI models` for `user-agnostic`, `data-efficient` performance



---
<h3 class="mb-4">Generalizable Wearable Human-Computer Interface</h3>

<div class="row align-items-center">
  <!-- 왼쪽: 텍스트 영역 -->
  <div class="col-md-7">
    <p>
      This research demonstrates advanced gestural interface capabilities enabled by high-quality datasets collected from newly developed wearable sensors.
      It features co-developed AI models that adapt to multiple users and tasks with limited training data.
    </p>
    <p>
      The model leverages Transformer-based Few-shot learning for multi-task interaction, showcasing keyboard-less virtual typing and object/gesture recognition. 
      <a href="https://www.nature.com/articles/s41928-022-00888-7" target="_blank">Nature Electronics, 2023 </a>
    </p>
  </div>

  <!-- 오른쪽: 이미지 -->
  <div class="col-md-5 text-center">
    {% include figure.liquid 
      loading="eager" 
      path="assets/img/Nat_elec.gif" 
      title="Skin sensor project" 
      class="img-fluid rounded shadow"
    %}
  </div>
</div>
---

<h3 class="mb-4">AI-Augmented Wristband for Gesture Recognition</h3>
<div class="row align-items-center">
  <!-- 왼쪽: 이미지 -->
  <div class="col-md-5 text-center">
    {% include figure.liquid 
      loading="eager" 
      path="assets/img/deep-learned.gif" 
      title="Skin sensor project" 
      class="img-fluid rounded shadow"
    %}
  </div>

  <!-- 오른쪽: 텍스트 -->
  <div class="col-md-7">
    <p>
      This research introduces a wrist-mounted single sensor that captures subtle skin deformations caused by finger movements, inspired by visible ligament shifts on the wrist.
    </p>
    <p>
     The analog signal output enables low-latency processing, with an LSTM-based model predicting both finger identity and bending angle. The system was designed for adaptability across users using transfer learning and fine-tuning with minimal new data. <br>
      <a href="https://www.nature.com/articles/s41467-020-16040-y" target="_blank">Nature Communications, 2021</a>
    </p>
  </div>
</div>
