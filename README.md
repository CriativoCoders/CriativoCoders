<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Perfil Talita</title>
<style>
  /* Reset básico */
  * {
    box-sizing: border-box;
  }

  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #121212;
    color: #eee;
    margin: 0;
    padding: 30px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
  }

  h1, h2, h3 {
    margin-bottom: 15px;
    font-weight: 700;
    text-align: center;
  }

  /* Container principal */
  .container {
    max-width: 1000px;
    width: 100%;
  }

  /* Cards de stats do GitHub */
  .stats-cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 30px;
    margin-bottom: 40px;
  }

  .card {
    background: #1e1e1e;
    border-radius: 16px;
    box-shadow: 0 8px 24px rgba(0, 255, 200, 0.25);
    overflow: hidden;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
    cursor: pointer;
    width: 350px;
  }

  .card:hover {
    transform: translateY(-10px) scale(1.05);
    box-shadow: 0 16px 40px rgba(0, 255, 200, 0.5);
  }

  .card img {
    width: 100%;
    display: block;
  }

  /* Skills section */
  .skills-section {
    margin-top: 10px;
  }

  .skills-category {
    margin-bottom: 30px;
  }

  .skills-category h3 {
    display: flex;
    align-items: center;
    gap: 10px;
    color: #00ffc8;
    font-size: 1.4rem;
    user-select: none;
  }

  /* Ícones de skills */
  .skills-icons {
    display: flex;
    flex-wrap: wrap;
    gap: 14px;
    margin-top: 10px;
    justify-content: center;
  }

  .skills-icons img {
    width: 48px;
    height: 48px;
    filter: drop-shadow(0 0 2px #00ffc8);
    transition: transform 0.25s ease, filter 0.25s ease;
    cursor: default;
  }

  .skills-icons img:hover {
    transform: scale(1.3) rotate(5deg);
    filter: drop-shadow(0 0 6px #00ffc8);
  }

  /* About Me */
  .about-me {
    background: #1e1e1e;
    border-radius: 14px;
    padding: 25px;
    margin-top: 40px;
    box-shadow: 0 8px 24px rgba(0, 255, 200, 0.3);
    font-size: 1.1rem;
    line-height: 1.5;
    max-width: 900px;
  }

  /* Emoji icon in title */
  .category-icon {
    width: 30px;
    height: 30px;
  }

  /* Responsive */
  @media (max-width: 400px) {
    .card {
      width: 90vw;
    }

    .skills-icons img {
      width: 40px;
      height: 40px;
    }
  }
</style>
</head>
<body>

<div class="container">

  <h1>Olá, eu sou a Talita 👋</h1>

  <section class="stats-cards">
    <div class="card" title="GitHub Stats">
      <img src="https://github-readme-stats.vercel.app/api?username=CriativoCoders&show_icons=False&theme=radical" alt="Your GitHub Stats" />
    </div>
    <div class="card" title="Top Languages">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CriativoCoders&layout=compact&theme=radical" alt="Top Languages" />
    </div>
  </section>

  <section class="skills-section">

    <div class="skills-category">
      <h3>
        <img class="category-icon" src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" alt="Hammer and Wrench" />
        Languages and Tools
      </h3>
    </div>

    <div class="skills-category">
      <h3>🔹 Frontend</h3>
      <div class="skills-icons">
        <img src="https://skillicons.dev/icons?i=html" alt="HTML" />
        <img src="https://skillicons.dev/icons?i=css" alt="CSS" />
        <img src="https://skillicons.dev/icons?i=js" alt="JavaScript" />
        <img src="https://skillicons.dev/icons?i=vite" alt="Vite" />
        <img src="https://skillicons.dev/icons?i=react" alt="React" />
        <img src="https://skillicons.dev/icons?i=ts" alt="TypeScript" />
        <img src="https://skillicons.dev/icons?i=sass" alt="Sass" />
        <img src="https://skillicons.dev/icons?i=angular" alt="Angular" />
        <img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" />
      </div>
    </div>

    <div class="skills-category">
      <h3>🔹 Design</h3>
      <div class="skills-icons">
        <img src="https://skillicons.dev/icons?i=figma" alt="Figma" />
      </div>
    </div>

    <div class="skills-category">
      <h3>🔹 Backend</h3>
      <div class="skills-icons">
        <img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" />
        <img src="https://skillicons.dev/icons?i=nestjs" alt="Nest.js" />
        <img src="https://skillicons.dev/icons?i=java" alt="Java" />
        <img src="https://skillicons.dev/icons?i=php" alt="PHP" />
        <img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" />
        <img src="https://skillicons.dev/icons?i=django" alt="Django" />
        <img src="https://skillicons.dev/icons?i=sqlite" alt="SQLite" />
        <img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" />
      </div>
    </div>

    <div class="skills-category">
      <h3>🔹 Tools and Others</h3>
      <div class="skills-icons">
        <img src="https://skillicons.dev/icons?i=git" alt="Git" />
        <img src="https://skillicons.dev/icons?i=github" alt="GitHub" />
        <img src="https://skillicons.dev/icons?i=vscode" alt="VS Code" />
        <img src="https://skillicons.dev/icons?i=postman" alt="Postman" />
        <img src="https://skillicons.dev/icons?i=arduino" alt="Arduino" />
        <img src="https://skillicons.dev/icons?i=pycharm" alt="PyCharm" />
      </div>
    </div>

    <div class="skills-category">
      <h3>🔹 Mobile</h3>
      <div class="skills-icons">
        <img src="https://skillicons.dev/icons?i=flutter" alt="Flutter" />
        <img src="https://skillicons.dev/icons?i=dart" alt="Dart" />
      </div>
    </div>

    <div class="skills-category">
      <h3>🔹 DevOps</h3>
      <div class="skills-icons">
        <img src="https://skillicons.dev/icons?i=heroku" alt="Heroku" />
      </div>
    </div>

  </section>

  <section class="about-me">
    <h2>About Me</h2>
    <p>Olá! Meu nome é Talita! e sou uma pessoa comunicativa, sempre em busca de aprender e crescer. Acredito que a comunicação é uma ferramenta poderosa, e adoro interagir com diferentes pessoas, trocar ideias e compartilhar experiências. Essa habilidade me ajuda a construir relacionamentos significativos e a entender melhor o mundo ao meu redor.</p>
  </section>

</div>

</body>
</html>


<div align="center">
  <h1>Meus Certificados</h1>
</div>

<div align="center" style="display: flex; flex-wrap: wrap; justify-content: center;">
  <img src="img/B7Web_MYSQL.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura1.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura2.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura3.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura4.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura5.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura6.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura7.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura9.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura10.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura11.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura12.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura13.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura14.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura15.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura16.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura17.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura18.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura19.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura20.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura21.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura22.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Alura23.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Cursa1.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Cursa2.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/Cursa3.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/SENAI_excel.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/SENAI_segurançaTrabalho.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/SENAI_ÉticaInteligenciaArtificial.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/HTML5.jpeg" width="300" height="200" style="margin: 10px;">
  <img src="img/HACKATHON.jpeg" width="300" height="200" style="margin: 10px;">
  <!-- Adicione mais imagens aqui -->
  <!-- Repita o padrão acima para as 29 imagens restantes -->
</div>
