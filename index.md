---
title: "HOME"
author: "MEI"
date: "2025-03-14"
layout: post
---

<!-- 只引入 Bootstrap 样式，不影响 `minima` -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css">

<style>
  /* 避免影响 `minima` 主题，所有样式仅限 `.custom-container` */
  .custom-container {
    max-width: 900px;
    margin: auto;
    padding: 20px;
  }
  
  .card {
    border: 1px solid #ddd;
    border-radius: 12px;
    padding: 15px;
    margin-bottom: 20px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
    background: #fff;
  }
  
  .card-img {
    width: 100%;
    border-radius: 12px;
    object-fit: cover;
  }
  
  .card-body {
    display: flex;
    align-items: center;
  }
  
  .card-content {
    flex: 1;
    padding-right: 15px;
  }
  
  .card-title {
    font-size: 1.5rem;
    font-weight: bold;
    color: #333;
  }
  
  .card-text {
    font-size: 1rem;
    color: #555;
  }
  
  .tag {
    background-color: #007bff;
    color: white;
    padding: 3px 8px;
    border-radius: 5px;
    font-size: 0.9rem;
  }
  
  .card a {
    color: #007bff;
    text-decoration: none;
  }
  
  .card a:hover {
    text-decoration: underline;
  }
</style>

<div class="custom-container">
  
  <!-- 卡片 1 -->
  <div class="card">
    <div class="row g-0">
      <div class="col-md-8 card-body">
        <div class="card-content">
          <div class="card-title">实验 1：牛顿第二定律</div>
          <div class="card-text">📅 时间：2025-03-14</div>
          <div class="card-text">🏷️ <span class="tag">物理</span> <span class="tag">力学</span></div>
          <div class="card-text">🔗 <a href="#">查看详情</a></div>
        </div>
      </div>
      <div class="col-md-4">
        <img src="https://source.unsplash.com/200x200/?science" class="card-img" alt="实验配图">
      </div>
    </div>
  </div>

  <!-- 卡片 2 -->
  <div class="card">
    <div class="row g-0">
      <div class="col-md-8 card-body">
        <div class="card-content">
          <div class="card-title">实验 2：自由落体</div>
          <div class="card-text">📅 时间：2025-03-14</div>
          <div class="card-text">🏷️ <span class="tag">物理</span> <span class="tag">运动学</span></div>
          <div class="card-text">🔗 <a href="#">查看详情</a></div>
        </div>
      </div>
      <div class="col-md-4">
        <img src="https://source.unsplash.com/200x200/?gravity" class="card-img" alt="实验配图">
      </div>
    </div>
  </div>

</div>

