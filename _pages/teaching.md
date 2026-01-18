---
layout: page
permalink: /research/
title: research
description: 
nav: true
nav_order: 1
---
My research focuses on leveraging a synergistic combination of `AI` and `Hardware` to enable user-independent, data-efficient recognition of diverse time-series signals, including Force, IMU, strain, and EMG from body joints and muscles. <br>
The goal is to develop, energy-efficient wearable devices that enhance human-computer interaction, leveraging high-quality sensor datasets and `adaptable AI models` for `user-agnostic`, `data-efficient` performance


---

<h3 class="mb-4">A simplified low‑channel EMG gesture interface</h3>
<div class="row align-items-center">
  <!-- 왼쪽: 이미지 -->
  <div class="col-md-5 text-center">
    {% include figure.liquid 
      loading="eager" 
      path="assets/img/publication_preview/emg_sensor.gif" 
      title="Skin sensor project" 
      class="img-fluid rounded shadow"
    %}
  </div>

  <!-- 오른쪽: 텍스트 -->
  <div class="col-md-7">
    <p>
      This research propose a self-supervised learning framework for wearable sensing that enables low-channel EMG devices to capture rich body kinematics traditionally requiring high-density sensor arrays. </p>
    <p>  Using a compact, wearable system, our approach achieves performance comparable to high-density EMG for human–computer interaction tasks such as sign language translation and gait force prediction. <a href="https://www.nature.com/articles/s44460-025-00002-2" target="_blank">Nature Sensors, 2026 </a> <a href="https://kyunkyukim.com/assets/pdf/emg_nat.pdf" target="_blank" style="color:#0071e3;">[PDF] </a>
    </p>
  </div>
</div>


---
<h3 class="mb-4">Task/User-Agnostic Wearable Human-Computer Interface</h3>

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
      <a href="https://kyunkyukim.com/assets/pdf/nat_elec.pdf" target="_blank" style="color:#0071e3;">[PDF] </a>
    </p>
  </div>

  <!-- 오른쪽: 이미지 -->
  <div class="col-md-5 text-center">
    {% include figure.liquid 
      loading="eager" 
      path="assets/img/publication_preview/Nat_elec_comp.gif" 
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
      path="assets/img/publication_preview/deep-learned_comp.gif" 
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
      <a href="https://kyunkyukim.com/assets/pdf/deep-learned.pdf" target="_blank" style="color:#0071e3;">[PDF] </a>
    </p>
  </div>
</div>

---
<h3 class="mb-4">Wearable embedded design for mutimodal sensing</h3>
<div class="row align-items-center">
  <!-- 왼쪽: 텍스트 영역 -->
  <div class="col-md-7">
    <p>
      This research demonstrates embedded circuit design for multimodal physiological sensing, integrating EMG, IMU, and temperature sensors on an ultra-thin PCB. 
    </p>
    <p>
      It further integrates a 915 MHz RF rectifier to enable battery-less operation. The system is implemented in a TI-RTOS environment, supporting compact, wearable, and real-time gesture and physiological signal acquisition.
      <a href="https://advanced.onlinelibrary.wiley.com/doi/10.1002/adfm.202106329" target="_blank">Adv.Func.Mat, 2022 </a> 
      <a href="https://kyunkyukim.com/assets/pdf/adv_func.pdf" target="_blank" style="color:#0071e3;">[PDF] </a>
    </p>
  </div>

  <!-- 오른쪽: 이미지 -->
  <div class="col-md-5 text-center">
    {% include figure.liquid 
      loading="eager" 
      path="assets/img/publication_preview/wireless.gif" 
      title="Skin sensor project" 
      class="img-fluid rounded shadow"
    %}
  </div>
</div>