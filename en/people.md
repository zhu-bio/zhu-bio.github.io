---
layout: default
title: People
subtitle: People in Zhu Lab
permalink: /en/people/
lang: en
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
  <h1>People</h1>

  <section class="people-section">
    <h2>Principal Investigator</h2>
    <div class="person-card person-card-featured">
      <img class="person-photo" src="/img/people/honglin_zhu.png" alt="Honglin Zhu">
      <div>
        <h3 class="person-name">Honglin Zhu, Ph.D.</h3>
        <p class="person-role">Associate Professor; Supervisor of Postdoctoral Fellows, Doctoral Students, and Master’s Students</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
    </div>
  </section>

  <section class="people-section">
    <h2>Co-Principal Investigators</h2>
    <div class="people-grid">
      <div class="person-card person-card-with-photo">
        <img class="person-photo-small" src="/img/people/hui_luo.jpg" alt="Hui Luo">
        <div>
          <h3 class="person-name">Hui Luo, M.D., Ph.D.</h3>
        <p class="person-role">Professor; Supervisor of Postdoctoral Fellows, Doctoral Students, and Master’s Students</p>
          <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
        </div>
      </div>
      <div class="person-card person-card-with-photo">
        <img class="person-photo-small" src="/img/people/sijia_liu.jpg" alt="Sijia Liu">
        <div>
          <h3 class="person-name">Sijia Liu</h3>
        <p class="person-role">Associate Professor; Supervisor of Master’s Students</p>
          <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
        </div>
      </div>
    </div>
  </section>

  <section class="people-section">
    <h2>Collaborating Principal Investigators</h2>
    <div class="people-grid">
      <div class="person-card">
        <h3 class="person-name">Jianxin Wang, Ph.D.</h3>
        <p class="person-role">Professor; Supervisor of Postdoctoral Fellows, Doctoral Students, and Master’s Students</p>
        <p class="person-affiliation">School of Computer Science, Central South University</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">Hongdong Li, Ph.D.</h3>
        <p class="person-role">Professor; Supervisor of Postdoctoral Fellows, Doctoral Students, and Master’s Students</p>
        <p class="person-affiliation">School of Computer Science, Central South University</p>
      </div>
    </div>
  </section>

  <section class="people-section">
    <h2>Team Members</h2>
    <div class="people-grid">
      <div class="person-card">
        <h3 class="person-name">Yizhi Xiao, M.D., Ph.D.</h3>
        <p class="person-role">Attending Physician; Associate Professor</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">Muyao Guo, M.D., Ph.D.</h3>
        <p class="person-role">Attending Physician; Associate Professor</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">Jing Huang, M.D., Ph.D.</h3>
        <p class="person-role">Attending Physician</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">Shasha Xie, M.D., Ph.D.</h3>
        <p class="person-role">Postdoctoral Fellow; Assistant Research Fellow</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">Qiming Meng, M.D.</h3>
        <p class="person-role">Resident Physician; M.D. Candidate</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">Ruimin He</h3>
        <p class="person-role">M.D. Candidate</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
      <div class="person-card">
        <h3 class="person-name">Jingqi Yang</h3>
        <p class="person-role">Master’s Student</p>
        <p class="person-affiliation">Department of Rheumatology and Immunology, Xiangya Hospital, Central South University</p>
      </div>
    </div>
  </section>
</div>
