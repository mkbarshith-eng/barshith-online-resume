<!doctype html>
<html lang="ta">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mohamed Barshith .M — Resume</title>
  <style>
    :root{
      --accent:#0f4c81;
      --muted:#6b6b6b;
      --card-bg:#ffffff;
      --page-bg:#f1f3f5;
      --max-width:1000px;
      font-family: system-ui, -apple-system, "Segoe UI", Roboto, "Noto Sans", "Helvetica Neue", Arial;
    }
    html,body{height:100%;margin:0;background:var(--page-bg);color:#111;}
    .wrap{
      max-width:var(--max-width);
      margin:28px auto;
      padding:22px;
    }

    /* Card */
    .resume{
      background:linear-gradient(180deg, rgba(255,255,255,0.98), rgba(255,255,255,0.98));
      box-shadow:0 6px 18px rgba(16,24,40,0.08);
      border-radius:14px;
      overflow:hidden;
      display:grid;
      grid-template-columns: 1fr 320px; /* desktop two-column */
      gap:0;
    }

    /* Left main column */
    .main{
      padding:28px 30px;
    }
    .heading{
      display:flex;
      gap:18px;
      align-items:center;
      margin-bottom:6px;
    }
    .avatar{
      width:64px;height:64px;border-radius:10px;
      background:linear-gradient(135deg,var(--accent),#2b9dd4);
      display:flex;align-items:center;justify-content:center;color:#fff;font-weight:700;
      font-size:20px;flex:0 0 64px;
    }
    .name{
      font-size:20px;font-weight:700;color:#0b3b61;
    }
    .sub{
      font-size:12px;color:var(--muted);margin-top:4px;
    }

    h3{margin:18px 0 8px;font-size:14px;color:#0b3b61;}
    p.small{font-size:13px;color:var(--muted);margin:0 0 10px;line-height:1.45;}

    .section{
      margin-top:12px;
      border-top:1px solid rgba(15,20,30,0.04);
      padding-top:12px;
    }

    /* Right sidebar */
    .side{
      background:#fafcff;
      padding:22px;
      border-left:1px solid rgba(15,20,30,0.03);
      min-width:240px;
    }
    .contact-row{display:flex;gap:8px;align-items:center;margin-bottom:8px;font-size:13px;color:var(--muted);}
    .label{font-weight:600;color:#0b3b61;font-size:13px;margin-bottom:6px;}

    ul.clean{list-style:none;padding:0;margin:0;}
    ul.clean li{margin:6px 0;font-size:13px;color:var(--muted);line-height:1.35;}

    /* Skills grid */
    .skills{display:flex;flex-wrap:wrap;gap:8px;}
    .skill{background:rgba(11,59,97,0.06);padding:6px 10px;border-radius:999px;font-size:12px;color:#0b3b61;}

    /* Responsive rules */
    @media (max-width:880px){
      .resume{grid-template-columns:1fr;box-shadow:none;border-radius:10px;}
      .side{order:2;border-left:0;border-top:1px solid rgba(15,20,30,0.03);}
      .main{order:1;padding:20px;}
      .wrap{padding:14px;}
      .avatar{width:56px;height:56px;font-size:18px}
    }

    /* Small tweaks for very small screens */
    @media (max-width:420px){
      .name{font-size:18px}
      .side{padding:16px}
      .main{padding:16px}
    }
  </style>
</head>
<body>
  <div class="wrap">
    <div class="resume" role="article" aria-label="Resume of Mohamed Barshith .M">
      <!-- LEFT -->
      <div class="main">
        <div class="heading">
          <div class="avatar">MB</div>
          <div>
            <div class="name">Mohamed Barshith .M</div>
            <div class="sub">MBA (HR) Student • Data Analyst (entry) • Programming & HR interest</div>
          </div>
        </div>

        <div class="section">
          <h3>Objective</h3>
          <p class="small">
            Motivated and adaptable professional currently pursuing MBA in Human Resource Management with a Bachelor's degree in History. Skilled in HR concepts, office administration, programming basics, and data handling. Seeking opportunities in HR, recruitment, employee engagement, and back-office operations to contribute to organizational success.
          </p>
        </div>

        <div class="section">
          <h3>Education</h3>
          <ul class="clean">
            <li><strong>Muslim Higher Secondary School</strong><br/><small class="small">Computer Application & Accounting Group — Completed 12th (2020–2022)</small></li>
            <li style="margin-top:8px;"><strong>Bachelor of Arts in History</strong><br/><small class="small">Sadakadhul Aupa College (Manonmaniam Sundaranar University) — 2022–2025 • Percentage: 63%</small></li>
            <li style="margin-top:8px;"><strong>MBA (HR)</strong><br/><small class="small">Alagappa University — 2025–2027 (Present)</small></li>
          </ul>
        </div>

        <div class="section">
          <h3>Experience & Training</h3>
          <ul class="clean">
            <li><strong>ISF Coding Hub — Internship</strong><br/><small class="small">Programming & Skills Trainer (Intern). Exposure to teaching Python/C basics and data concepts.</small></li>
            <li style="margin-top:8px;"><strong>Data Analyst Course</strong><br/><small class="small">ISF coaching center — Training in data handling & visualization.</small></li>
          </ul>
        </div>

        <div class="section">
          <h3>Technical Skills</h3>
          <div class="skills" aria-hidden="true">
            <div class="skill">Microsoft Excel (SUM, SORT, FILTER, Charts)</div>
            <div class="skill">Python (Pandas, NumPy, Matplotlib)</div>
            <div class="skill">SQL — Basics</div>
            <div class="skill">Power BI</div>
            <div class="skill">C, C++</div>
            <div class="skill">Data Entry</div>
          </div>
        </div>

        <div class="section">
          <h3>Additional Skills</h3>
          <p class="small">Good communication skill · Leadership skill · Management skill · Critical Thinking</p>
        </div>
      </div>

      <!-- RIGHT SIDEBAR -->
      <aside class="side">
        <div class="label">Contact</div>
        <div class="contact-row">📞 +91 6383697844</div>
        <div class="contact-row">✉ <a href="mailto:mk.barshith@gmail.com">mk.barshith@gmail.com</a></div>
        <div class="contact-row" style="font-size:13px;color:var(--muted);margin-bottom:12px;">🏠 118, Periya Kothba Palli, Vasal South East Street, Melapalayam, Tirunelveli</div>

        <div class="label">Languages</div>
        <ul class="clean"><li>Tamil · English</li></ul>

        <div style="height:10px;"></div>
        <div class="label">Certifications</div>
        <ul class="clean">
          <li>Certification in Python Programming (CSC coaching center)</li>
          <li>Certification in C, C++ Programming (CSC coaching center)</li>
          <li>Government Certification in Typing — 30+ WPM</li>
          <li>Data Analyst Course (ISF coaching center)</li>
        </ul>

        <div style="height:10px;"></div>
        <div class="label">Quick Facts</div>
        <p class="small">Currently pursuing MBA (HR). Comfortable with data tools & basic programming. Seeking HR / back-office / data-support roles.</p>
      </aside>
    </div>
  </div>
</body>
</html>
