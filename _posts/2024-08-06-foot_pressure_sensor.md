---
layout: post
title: Foot Pressure Sensor And It's Usage In Barefoot Shoes: Fullsoul Runningpad

subtitle: a fullsoul which is able to measure the foot pressure distribution in real time.
thumbnail-img: /assets/img/run_on_the_grass.jpg
tags: [python, data analyse]
---

We integrate the [sensor]:https://www.moxiantech.com/ on the [fullsole designed by our Prof. Dr. Martin Daumer] :[https://fullsoul.de/ ] and measure the foot pressure distribution in time. The code are uploaded on the github:[https://github.com/weichkai/footPressureSensor]. 

For example,  the following four videos are in four situations: sensor in the fullsole, sensor in the normal shoes, walking on the grass, walking on the stone.

<!-- 视频网格样式 -->
<style>
.video-grid {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
  margin-bottom: 40px;
}

.video-item {
  flex: 1 1 45%;
  max-width: 45%;
}

video {
  width: 100%;
  height: auto;
  border-radius: 10px;
}
</style>

<!-- 视频展示区域 -->
<div class="video-grid">
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/fullsoul_wiese1-lessthan25MB.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">Sensor in fullsole</p>
  </div>
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/nrshoes_wiese2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">Sensor in normal shoes</p>
  </div>
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/fullsoul_stone1.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">Walking on grass</p>
  </div>
  <div class="video-item">
    <video controls>
      <source src="/assets/vid/nrshoes_stone2.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <p style="text-align: center;">Walking on stone</p>
  </div>
</div>

<iframe src="/assets/pdf/foot_pressure_sensor_presentation_06082024_v15.pdf" width="100%" height="1000px" style="border-radius: 15px;"></iframe>
