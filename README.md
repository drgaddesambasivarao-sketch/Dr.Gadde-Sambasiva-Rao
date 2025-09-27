<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Dr.Gadde Sambasiva Rao - Personal Website</title>
  <style>
    :root{--accent:#1f6feb;--bg:#f6f8fb;--card:#fff;--muted:#666;}
    *{box-sizing:border-box}
    body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,"Helvetica Neue",Arial;background:var(--bg);color:#222;line-height:1.5}
    .container{max-width:980px;margin:30px auto;padding:20px}
    header{display:flex;gap:20px;align-items:center;padding:20px;background:linear-gradient(90deg,#fff,#f7fbff);border-radius:10px;box-shadow:0 6px 20px rgba(20,30,50,0.06)}
    .avatar{width:120px;height:120px;border-radius:10px;object-fit:cover;background:#ddd}
    h1{margin:0;font-size:1.8rem}
    .sub{color:var(--muted);margin-top:6px}
    nav{display:flex;gap:12px;flex-wrap:wrap;margin:18px 0}
    nav a{color:var(--accent);text-decoration:none;font-weight:600}
    section.card{background:var(--card);padding:18px;border-radius:10px;margin-bottom:16px;box-shadow:0 6px 14px rgba(20,30,50,0.04)}
    .two-col{display:grid;grid-template-columns:1fr 1fr;gap:16px}
    ul{margin:8px 0 0 20px}
    .btn{display:inline-block;padding:10px 14px;border-radius:8px;background:var(--accent);color:white;text-decoration:none;font-weight:600}
    footer{text-align:center;color:var(--muted);font-size:0.9rem;margin:30px 0 10px}
    @media(max-width:700px){.two-col{grid-template-columns:1fr}.avatar{width:96px;height:96px}}
  </style>
</head>
<body>
  <div class="container">

    <!-- Header -->
    <header>
      <!-- Replace profile.jpg with your uploaded image filename -->
      <img src="profile.jpg" alt="Profile" class="avatar" onerror="this.style.display='none'">
      <div>
        <h1>Dr.Gadde Sambasiva Rao</h1>
        <div class="sub">Assistant Professor, Dept. of Mathematics — Sree Dattha Group Of Institution<br>Awarded Ph.D, Engineering Mathematics — KLEF</div>
        <div style="margin-top:8px;color:var(--muted)">
          <strong>Phone:</strong> +91-******* &nbsp; | &nbsp;
          <strong>Email:</strong> <a href="mailto:gaddesambasivarao1@gmail.com">gaddesambasivarao1@gmail.com</a>
        </div>
      </div>
    </header>

    <!-- Navigation -->
    <nav>
      <a href="#about">About</a>
      <a href="#education">Education</a>
      <a href="#research">Research</a>
      <a href="#publications">Publications</a>
      <a href="#teaching">Teaching</a>
      <a href="#contact">Contact</a>
      <!-- Resume link: upload resume.pdf to repo and change href if name different -->
      <a class="btn" href="resume.pdf" target="_blank" rel="noopener">Download CV / Resume</a>
    </nav>

    <!-- About -->
    <section id="about" class="card">
      <h2>About Me</h2>
      <p>
        Hello — I am <strong>Dr.Gadde Sambasiva Rao</strong>. I work as an Assistant Professor in the Department of Mathematics at Sree Dattha Group of Institutions. My research interests include fuzzy soft set theory, neutrosophic soft structures, intuitionistic fuzzy algebraic systems, and Boolean rings.
      </p>
    </section>

    <!-- Education & Awards -->
    <section class="card two-col">
      <div>
        <h3 id="education">Education</h3>
        <ul>
          <li>Ph.D. in Engineering Mathematics — (KLEF) — (2025)</li>
          <li>M.Sc. — Mathematics — Acharya Nagarjuna University — (2018)</li>
          <li>B.Sc — Vignan Degree College — (ANU) — (2015)</li>
        </ul>
      </div>
      <div>
        <h3>Awards & Positions</h3>
        <ul>
          <li>Assistant Professor — Dept. of Mathematics, Sree Dattha Group of Institutions</li>
      
          <li>Preparing for CSIR UGC-NET (if applicable)</li>
        </ul>
      </div>
    </section>

    <!-- Research -->
    <section id="research" class="card">
      <h2>Research Interests</h2>
      <ul>
        <li>Fuzzy Soft Set Theory & Applications</li>
        <li>Neutrosophic Soft Boolean Rings and Ideals</li>
        <li>Intuitionistic / Picture Fuzzy Soft Structures</li>
        <li>Algebraic methods applied to Computer Science</li>
      </ul>
    </section>

    <!-- Publications -->
    <section id="publications" class="card">
      <h2>Publications</h2>
      <p>If you want, replace the items below with your exact papers (title, journal/conference, year).</p>
      <ol>
        <li>"Algebraic Aspects of Bipolar Fuzzy Soft Boolean Rings" — Journal / Year</li>
        <li>"On the Structure of Picture Fuzzy Soft Sets in Boolean Rings" — Journal / Year</li>
        <li>"PFSBR: PFSI and PFSS Over BR" — Conference / Year</li>
      </ol>
    </section>

    <!-- Teaching -->
    <section id="teaching" class="card">
      <h2>Teaching / Courses</h2>
      <p>Discrete Mathematics, Algebra, Calculus, Differential Equations, Numerical Methods, Data Structures (C Programming basics), and more.</p>
    </section>

    <!-- Contact -->
    <section id="contact" class="card">
      <h2>Contact</h2>
      <p><strong>Phone:</strong> +91-8309259564</p>
      <p><strong>Email:</strong> <a href="mailto:your.email@example.com">your.email@example.com</a></p>
      <p><strong>Address:</strong> Guntur, Andhra Pradesh, India</p>
      <p>
        <strong>Social:</strong>
        <a href="#" target="_blank">Google Scholar</a> |
        <a href="#" target="_blank">ResearchGate</a> |
        <a href="#" target="_blank">LinkedIn</a>
      </p>
      <p style="color:var(--muted)">Tip: Replace the # links above with your real profile URLs.</p>
    </section>

    <footer>
      &copy; 2025 Gadde Sambasiva Rao — Built with ❤️
    </footer>

  </div>
</body>
</html>
