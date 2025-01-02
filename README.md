<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Shahinur Rahman - Developer Profile</title>
  <style>
    /* Global styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Arial', sans-serif;
      background: #f4f7f6;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      text-align: center;
      padding: 20px;
    }

    h1, h2 {
      color: #4b8df8;
      margin-bottom: 20px;
    }

    p {
      line-height: 1.6;
      font-size: 16px;
      max-width: 600px;
      margin: 10px auto;
    }

    /* Profile section */
    .profile-container {
      max-width: 1000px;
      width: 100%;
      background: white;
      border-radius: 20px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
      padding: 40px 30px;
      margin-bottom: 30px;
      transform: scale(0.98);
      transition: transform 0.3s ease-in-out;
    }
    .profile-container:hover {
      transform: scale(1);
    }

    .profile-header {
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    .profile-header img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .profile-links {
      margin-top: 20px;
    }

    .profile-links a {
      margin: 15px;
      text-decoration: none;
      color: #333;
      transition: transform 0.3s ease;
    }

    .profile-links img {
      width: 40px;
      height: 40px;
      transition: transform 0.3s ease;
    }

    .profile-links a:hover img {
      transform: scale(1.2);
    }

    /* Skills section */
    .skills-section {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(50px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }

    .skills-section img {
      width: 50px;
      height: 50px;
      transition: transform 0.3s ease;
      cursor: pointer;
    }

    .skills-section img:hover {
      transform: scale(1.1);
    }

    /* Cards for Education and Contact */
    .card-container {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 50px;
      flex-wrap: wrap;
    }

    .card {
      background-color: #ffffff;
      border-radius: 15px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
      padding: 30px;
      width: 300px;
      text-align: left;
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-10px);
    }

    .card h3 {
      color: #4b8df8;
      font-size: 20px;
      margin-bottom: 15px;
    }

    .card p {
      color: #555;
      font-size: 16px;
    }

    .card a {
      color: #4b8df8;
      text-decoration: none;
    }

    /* Animation */
    .typing-animation {
      font-size: 30px;
      font-weight: bold;
      color: #4b8df8;
      animation: typing 2s steps(30) 1s 1 normal both, blink 0.75s step-end infinite;
    }

    @keyframes typing {
      from { width: 0; }
      to { width: 100%; }
    }

    @keyframes blink {
      50% { border-color: transparent; }
    }

    /* Scroll to top */
    .scroll-to-top {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background: #4b8df8;
      color: white;
      border-radius: 50%;
      width: 50px;
      height: 50px;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
      font-size: 20px;
      transition: transform 0.3s ease;
    }

    .scroll-to-top:hover {
      transform: scale(1.1);
    }

  </style>
</head>
<body>

  <div class="profile-container">
    <div class="profile-header">
      <h1 class="typing-animation">Hello, There! 👋</h1>
      <p>This is Shahinur Rahman. Nice to meet you!</p>
      <p>Software Engineer | Programmer | Bug Hunter | Ethical Hacker from Bangladesh</p>
    </div>

    <p>
      - 🔬 I'm currently pursuing a Master's degree in Computer Engineering at Harvard University.
      <br>
      - 🎓 I graduated from the Hong Kong University of Science and Technology (HKUST) in Computer Engineering.
      <br>
      - 💻 Passionate about writing code and learning new technologies.
      <br>
      - 📚 I’m currently learning Ethical Hacking.
    </p>

    <div class="profile-links">
      <a href="https://github.com/shahin0075"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg" alt="GitHub"></a>
      <a href="https://www.linkedin.com/in/mohammad-sheikh-shahinur-rahman/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg" alt="LinkedIn"></a>
      <a href="https://www.facebook.com/Shahinurrahman.0.Official"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/facebook.svg" alt="Facebook"></a>
      <a href="https://www.instagram.com/Shahinur3546/"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/instagram.svg" alt="Instagram"></a>
      <a href="https://twitter.com/Shahinalam3546"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/twitter.svg" alt="Twitter"></a>
      <a href="https://shahinur.amadersomaj.com"><img src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/icloud.svg" alt="Website"></a>
    </div>
  </div>

  <h2>🔥 Skills & Expertise 🔥</h2>
  <div class="skills-section">
    <img src="c.svg" alt="C">
    <img src="cpp.svg" alt="C++">
    <img src="cSharp.svg" alt="C#">
    <img src="python-original.svg" alt="Python">
    <img src="django.png" alt="Django">
    <img src="javascript.svg" alt="JavaScript">
    <img src="html5.svg" alt="HTML5">
    <img src="css.svg" alt="CSS">
    <img src="react-original.svg" alt="React">
    <img src="git-original.svg" alt="Git">
    <img src="mysql.svg" alt="MySQL">
    <img src="flask.png" alt="Flask">
  </div>

  <div class="card-container">
    <div class="card">
      <h3>Education</h3>
      <p>Master's in Computer Engineering (Harvard University). Bachelor's in Computer Engineering (HKUST).</p>
    </div>

    <div class="card">
      <h3>Contact</h3>
      <p>You can reach me via email: <a href="mailto:shahinalam3546@gmail.com">shahinalam3546@gmail.com</a></p>
    </div>
  </div>

  <div class="scroll-to-top" onclick="window.scrollTo({top: 0, behavior: 'smooth'});">
    ↑
  </div>

</body>
</html>
