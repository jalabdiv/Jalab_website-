!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ahmed Jalab - Personal Website</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <link rel="stylesheet" href="https://unpkg.com/aos@2.3.1/dist/aos.css"/>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f2f2f2;
      color: #333;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .container {
      max-width: 750px;
      margin: 40px auto;
      padding: 25px;
      background: #ffffff;
      border-radius: 20px;
      box-shadow: 0 8px 20px rgba(0, 0, 0, 0.05);
      text-align: center;
    }

    .profile-img {
      width: 130px;
      height: 130px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid #b3e5fc;
      margin-bottom: 20px;
    }

    h1 {
      margin: 10px 0 5px;
      font-size: 30px;
      color: #4a90e2;
    }

    p {
      font-size: 16px;
      font-weight: 500;
    }

    .social-icons a {
      display: inline-block;
      margin: 6px;
      padding: 10px 16px;
      border-radius: 25px;
      color: white;
      text-decoration: none;
      font-weight: bold;
      font-size: 14px;
      transition: all 0.3s ease;
    }

    .facebook { background-color: #a0c4ff; }
    .gmail { background-color: #ffc6c6; }
    .whatsapp { background-color: #caffbf; }

    .social-icons a:hover {
      opacity: 0.9;
      transform: scale(1.05);
    }

    .section {
      margin-top: 35px;
      padding: 20px;
      border-radius: 15px;
    }

    .section:nth-of-type(1) { background-color: #e3f2fd; }
    .section:nth-of-type(2) { background-color: #f3e5f5; }

    .skills {
      display: flex;
      justify-content: center;
      gap: 12px;
      margin-top: 15px;
      flex-wrap: wrap;
    }

    .skill {
      background: #ffffff;
      color: #555;
      padding: 8px 18px;
      border-radius: 20px;
      font-weight: bold;
      font-size: 14px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    footer {
      margin-top: 40px;
      font-size: 14px;
      color: #999;
    }
  </style>
</head>
<body>

  <div class="container" data-aos="zoom-in">
    <img src="jalab.jpg" alt="Ahmed Jalab - Profile Photo" class="profile-img" data-aos="fade-down"/>
    <h1 data-aos="fade-up">Ahmed Jalab</h1>
    <p data-aos="fade-up">Web Designer & Developer</p>

    <div class="social-icons" data-aos="fade-up">
      <a href="https://www.facebook.com/share/168taPv9yU/" class="facebook" target="_blank"><i class="fab fa-facebook-f"></i> Facebook</a>
      <a href="mailto:Jalaabahmed@gmail.com" class="gmail"><i class="fas fa-envelope"></i> Gmail</a>
      <a href="https://wa.me/256705761060" class="whatsapp" target="_blank"><i class="fab fa-whatsapp"></i> WhatsApp</a>
    </div>

    <div class="section" data-aos="fade-up">
      <h2>About Me</h2>
      <p>Hello! I'm a creative web designer and front-end developer from Uganda. I create fast and beautiful websites with a focus on user experience. I love designing elegant and responsive pages.</p>
    </div>

    <div class="section" data-aos="fade-up">
      <h2>Skills</h2>
      <div class="skills">
        <div class="skill" data-aos="flip-left">HTML</div>
        <div class="skill" data-aos="flip-left">CSS</div>
        <div class="skill" data-aos="flip-left">JavaScript</div>
      </div>
    </div>

    <footer data-aos="fade-up">
      <p>&copy; 2025 Ahmed Jalab. All rights reserved.</p>
    </footer>
  </div>

  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init({
      duration: 1000,
      once: true
    });
  </script>

</body>
</html>
