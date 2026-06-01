---
layout: default
title: 团队成员
subtitle: 朱红林课题组团队成员
permalink: /cn/people/
lang: cn
---

<style>
  .people-page {
    margin-top: 20px;
  }

  .people-section {
    margin-bottom: 36px;
  }

  .people-section h2 {
    margin-bottom: 18px;
  }

  .people-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    grid-auto-rows: 1fr;
    gap: 16px;
    align-items: stretch;
  }

  .person-card {
    border: 1px solid #e5e5e5;
    border-radius: 6px;
    padding: 18px;
    min-height: 150px;
    background: #fff;
  }

  .person-card-featured {
    display: grid;
    grid-template-columns: 130px 1fr;
    gap: 20px;
    align-items: start;
  }

  .person-card-with-photo {
    display: grid;
    grid-template-columns: 110px 1fr;
    gap: 16px;
    align-items: start;
  }

  .person-card:not(.person-card-featured):not(.person-card-with-photo) {
    display: flex;
    flex-direction: column;
  }

  .person-photo {
    width: 130px;
    height: 130px;
    object-fit: contain;
    object-position: center;
  }

  .person-photo-small {
    width: 110px;
    height: 110px;
    object-fit: contain;
    object-position: center;
    border-radius: 4px;
  }

  .person-name {
    margin-top: 0;
    margin-bottom: 8px;
    font-size: 20px;
  }

  .person-role {
    margin-bottom: 8px;
    min-height: 44px;
    font-weight: 600;
  }

  .person-affiliation {
    margin-top: auto;
    margin-bottom: 0;
    color: #555;
  }

  @media (max-width: 640px) {
    .person-card-featured,
    .person-card-with-photo {
      grid-template-columns: 1fr;
      text-align: center;
    }

    .person-role {
      min-height: 0;
    }

    .person-affiliation {
      margin-top: 0;
    }

    .person-photo,
    .person-photo-small {
      margin: 0 auto;
    }
  }
</style>

<div class="people-page">
  <h1>团队成员</h1>

  <section class="people-section">
    <h2>课题组负责人</h2>
    <div class="person-card person-card-featured">
      <img class="person-photo" src="/img/people/honglin_zhu.png" alt="朱红林">
      <div>
        <h3 class="person-name">朱红林，博士</h3>
        <p class="person-role">副教授；博士后、博士生和硕士生导师</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
    </div>
  </section>

  <section class="people-section">
    <h2>共同课题组负责人</h2>
    <div class="people-grid">
      <div class="person-card person-card-with-photo">
        <img class="person-photo-small" src="/img/people/hui_luo.jpg" alt="罗卉">
        <div>
          <h3 class="person-name">罗卉，博士</h3>
          <p class="person-role">教授；博士后、博士生和硕士生导师</p>
          <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
        </div>
      </div>
      <div class="person-card person-card-with-photo">
        <img class="person-photo-small" src="/img/people/sijia_liu.jpg" alt="刘思佳">
        <div>
          <h3 class="person-name">刘思佳，博士</h3>
          <p class="person-role">副教授；硕士生导师</p>
          <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
        </div>
      </div>
    </div>
  </section>

  <section class="people-section">
    <h2>合作课题组负责人</h2>
    <div class="people-grid">
      <div class="person-card">
        <h3 class="person-name">王建新，博士</h3>
        <p class="person-role">教授；博士后、博士生和硕士生导师</p>
        <p class="person-affiliation">中南大学计算机学院</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">李洪东，博士</h3>
        <p class="person-role">教授；博士后、博士生和硕士生导师</p>
        <p class="person-affiliation">中南大学计算机学院</p>
      </div>
    </div>
  </section>

  <section class="people-section">
    <h2>团队成员</h2>
    <div class="people-grid">
      <div class="person-card">
        <h3 class="person-name">肖亦之，博士</h3>
        <p class="person-role">主治医师；副教授</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">郭慕瑶，博士</h3>
        <p class="person-role">主治医师；副教授</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">黄靖，博士</h3>
        <p class="person-role">主治医师</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">谢莎莎，M.D., Ph.D.</h3>
        <p class="person-role">博士后；助理研究员</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">孟琦铭</h3>
        <p class="person-role">博士生</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">何瑞敏</h3>
        <p class="person-role">博士生</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">杨婧琪</h3>
        <p class="person-role">硕士生</p>
        <p class="person-affiliation">中南大学湘雅医院风湿免疫科</p>
      </div>
    </div>
  </section>
</div>
