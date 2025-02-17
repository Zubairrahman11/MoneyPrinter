<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>রহমান জুবায়ের | ডেভেলপার প্রোফাইল</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
  <style>
    :root {
      --primary-color: #2B3137;
      --secondary-color: #0366d6;
      --background-color: #f6f8fa;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--background-color);
      margin: 0;
      padding: 20px;
      color: var(--primary-color);
      line-height: 1.6;
    }

    .container {
      max-width: 1200px;
      margin: 0 auto;
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
      overflow: hidden;
    }

    header {
      background: var(--primary-color);
      color: white;
      padding: 3rem 2rem;
      text-align: center;
    }

    .main-content {
      display: grid;
      grid-template-columns: 250px 1fr;
      gap: 30px;
      padding: 30px;
    }

    .sidebar {
      border-right: 1px solid #e1e4e8;
      padding-right: 30px;
    }

    h1 { margin: 0; font-size: 2.2em; }
    h2 { color: var(--secondary-color); margin-top: 0; }
    h3 { color: var(--primary-color); }

    .contact-list {
      list-style: none;
      padding: 0;
    }

    .contact-list li {
      margin: 15px 0;
      display: flex;
      align-items: center;
    }

    .contact-list i {
      width: 25px;
      margin-right: 10px;
      color: var(--secondary-color);
    }

    .skill-chip {
      display: inline-block;
      background: #f1f8ff;
      color: var(--secondary-color);
      padding: 5px 15px;
      border-radius: 20px;
      margin: 5px;
      font-size: 0.9em;
    }

    .project-card {
      border: 1px solid #e1e4e8;
      border-radius: 6px;
      padding: 20px;
      margin-bottom: 20px;
    }

    .github-stats {
      display: grid;
      grid-template-columns: repeat(2, 1fr);
      gap: 15px;
      margin-top: 20px;
    }

    @media (max-width: 768px) {
      .main-content {
        grid-template-columns: 1fr;
      }
      .sidebar {
        border-right: none;
        padding-right: 0;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <h1>রহমান জুবায়ের</h1>
      <p>আগ্রহী সফটওয়্যার ডেভেলপার</p>
    </header>

    <div class="main-content">
      <aside class="sidebar">
        <h2>যোগাযোগ</h2>
        <ul class="contact-list">
          <li><i class="fas fa-mobile-alt"></i>+6589568391</li>
          <li><i class="fas fa-envelope"></i><a href="mailto:rahmanzubair50@gmail.com">ইমেইল</a></li>
          <li><i class="fab fa-github"></i><a href="#">GitHub</a></li>
          <li><i class="fab fa-facebook"></i><a href="https://www.facebook.com/share/1BT6rnMgUn/">ফেসবুক</a></li>
        </ul>

        <h2>দক্ষতা</h2>
        <div class="skills">
          <span class="skill-chip">HTML</span>
          <span class="skill-chip">CSS</span>
          <span class="skill-chip">JavaScript</span>
          <span class="skill-chip">Python</span>
          <span class="skill-chip">Git</span>
        </div>
      </aside>

      <main>
        <section>
          <h2>আমার সম্পর্কে</h2>
          <p>
            সফটওয়্যার ডেভেলপমেন্টে আগ্রহী একজন উদীয়মান প্রোগ্রামার। প্রতিদিন নতুন প্রযুক্তি শিখতে এবং বাস্তব প্রজেক্টে প্রয়োগ করতে আগ্রহী। ওপেন সোর্স কমিউনিটিতে অবদান রাখা এবং কোলাবোরেটিভ কাজ করতে পছন্দ করি।
          </p>
        </section>

        <section>
          <h2>প্রকল্পসমূহ</h2>
          <div class="project-card">
            <h3>ব্যক্তিগত ওয়েবসাইট</h3>
            <p>HTML, CSS এবং JavaScript ব্যবহার করে তৈরি করা আমার প্রথম ওয়েবসাইট</p>
            <div class="tech-used">
              <span class="skill-chip">HTML</span>
              <span class="skill-chip">CSS</span>
            </div>
          </div>

          <div class="project-card">
            <h3>টাস্ক ম্যানেজার</h3>
            <p>Python ব্যবহার করে তৈরি করা কমান্ড লাইন টাস্ক ম্যানেজমেন্ট সিস্টেম</p>
            <div class="tech-used">
              <span class="skill-chip">Python</span>
              <span class="skill-chip">SQLite</span>
            </div>
          </div>
        </section>

        <div class="github-stats">
          <!-- Add GitHub stats images here -->
          <img src="https://ghchart.rshah.org/rahmanzubair" alt="GitHub Contributions">
        </div>
      </main>
    </div>
  </div>
</body>
</html>