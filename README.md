# Luan Tran Portfolio

Hi 👋! My name is Luan Tran

---

<img align="right" src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMmh4czBpcjVkcW43MjM4NWh2eWlkYWZmbWFnamU5dmtraDdkMXlzMyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/VbnUQpnihPSIgIXuZv/giphy.gif" alt="Luan Tran GIF" style="border-radius: 15px; margin: 1rem; width:370px; max-width:100%;" />

## Social Links

<div align="left">
  <a href="https://www.instagram.com/louis.tran1202/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&style=for-the-badge" alt="Instagram" height="45"/>
  </a>
  <a href="mailto:tdtruongluan1202@gmail.com">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&style=for-the-badge" alt="Gmail" height="45"/>
  </a>
  <a href="https://www.linkedin.com/in/louistran1202/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&style=for-the-badge" alt="LinkedIn" height="45"/>
  </a>
  <a href="https://www.hackerrank.com/profile/tdtruongluan" target="_blank">
    <img src="https://img.shields.io/static/v1?message=HackerRank&logo=hackerrank&label=&color=2EC866&logoColor=white&style=for-the-badge" alt="HackerRank" height="45"/>
  </a>
</div>

---

## Technology Icons

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-line-wordmark.svg" alt="AWS" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" height="40"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" height="40"/>
</div>

---

## Stats

<div align="center">
  <img src="https://streak-stats.demolab.com?user=truongluan1202&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5" alt="Streak Graph" style="max-width:100%; border-radius:5px;"/>
  <br><br>
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=truongluan1202&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" alt="Languages Graph" style="max-width:100%; border-radius:5px;"/>
</div>

---

## Snake Animation

<div align="center">
  <img src="https://raw.githubusercontent.com/truongluan1202/truongluan1202/output/snake.svg" alt="Snake Animation" style="max-width:100%; border-radius:5px;"/>
</div>

---

## HTML Source Code

Below is the full HTML code used to build the above portfolio:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Luan Tran | Portfolio</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      font-family: sans-serif;
      background: #f4f4f4;
    }
    .container {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 2rem;
      gap: 2rem;
    }
    .header {
      display: flex;
      flex-wrap: wrap;
      justify-content: space-around;
      align-items: center;
      width: 100%;
      background: #fff;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .intro {
      flex: 1;
      min-width: 250px;
      text-align: left;
      padding: 1rem;
    }
    .intro h2 {
      margin: 0;
    }
    .header img {
      border-radius: 15px; /* rounded corners for GIF */
      margin: 1rem;
      width: 370px;
      max-width: 100%;
    }
    .social, .tech-icons {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
    }
    .social img {
      height: 45px; /* bigger icon */
    }
    .tech-icons img {
      height: 40px;
    }
    .stats, .snake {
      display: flex;
      justify-content: center;
      width: 100%;
    }
    .stats img, .snake img {
      max-width: 100%;
      border-radius: 5px;
    }
    @media (min-width: 768px) {
      .header {
        flex-wrap: nowrap;
      }
      .intro {
        text-align: left;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- Header Section -->
    <div class="header">
      <div class="intro">
        <h2>Hi 👋! My name is Luan Tran</h2>
      </div>
      <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExMmh4czBpcjVkcW43MjM4NWh2eWlkYWZmbWFnamU5dmtraDdkMXlzMyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/VbnUQpnihPSIgIXuZv/giphy.gif" alt="Luan Tran GIF" />
    </div>

    <!-- Social Links -->
    <div class="social">
      <a href="https://www.instagram.com/louis.tran1202/" target="_blank">
        <img src="https://img.shields.io/static/v1?message=Instagram&logo=instagram&label=&color=E4405F&logoColor=white&style=for-the-badge" alt="Instagram" />
      </a>
      <a href="mailto:tdtruongluan1202@gmail.com">
        <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&style=for-the-badge" alt="Gmail" />
      </a>
      <a href="https://www.linkedin.com/in/louistran1202/" target="_blank">
        <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&style=for-the-badge" alt="LinkedIn" />
      </a>
      <a href="https://www.hackerrank.com/profile/tdtruongluan" target="_blank">
        <img src="https://img.shields.io/static/v1?message=HackerRank&logo=hackerrank&label=&color=2EC866&logoColor=white&style=for-the-badge" alt="HackerRank" />
      </a>
    </div>

    <!-- Technology Icons -->
    <div class="tech-icons">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-line-wordmark.svg" alt="AWS" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" alt="Jupyter" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" />
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" alt="MongoDB" />
    </div>

    <!-- Streak Stats -->
    <div class="stats">
      <img src="https://streak-stats.demolab.com?user=truongluan1202&locale=en&mode=daily&theme=dracula&hide_border=false&border_radius=5" alt="Streak Graph" />
    </div>

    <!-- Languages Stats -->
    <div class="stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs?username=truongluan1202&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" alt="Languages Graph" />
    </div>

    <!-- Snake Animation -->
    <div class="snake">
      <img src="https://raw.githubusercontent.com/truongluan1202/truongluan1202/output/snake.svg" alt="Snake Animation" />
    </div>
  </div>
</body>
</html>
