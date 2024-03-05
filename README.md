<div align="center">
<h1 align="center">Hola, soy <a href="https://beltran-puma.com">Beltran Puma</a> 👋</h1>
</div>
<div align="center">
  <h1 id="typed-text" align="center"></h1>
</div>

<script>
  // Texto que deseas mostrar
  
  var text = "Hola, soy Beltran Puma";

  // Tiempo de espera antes de comenzar a escribir
  
  var delay = 1000;

  // Tiempo entre cada letra (en milisegundos)
  
  var speed = 100;

  // Función para animar el texto
  
  function typeWriter(text, i, fnCallback) {
    if (i < text.length) {
      document.getElementById("typed-text").innerHTML += text.charAt(i);
      setTimeout(function () {
        typeWriter(text, i + 1, fnCallback);
      }, speed);
    } else if (typeof fnCallback == "function") {
      setTimeout(fnCallback, delay);
    }
  }

  // Iniciar la animación
  
  function startTextAnimation(i) {
    if (typeof text === "undefined") return;
    if (i < text.length) {
      typeWriter(text, 0, function () {
        startTextAnimation(i);
      });
    }
  }

  // Iniciar la animación cuando la página esté cargada
  
  document.addEventListener("DOMContentLoaded", function () {
    if (text) {
      startTextAnimation(0);
    }
  });
</script>


<h2> / Sobre mí /</h2>

⭐ Desarrollador backend con Java y Spring Boot

💻 Especializado en APIs REST y SQL Server

🌐 Experiencia en desarrollo web con Angular

🎓 Apasionado por el aprendizaje y el crecimiento profesional.

<h2> / Redes Sociales /</h2>

[![Youtube](https://img.shields.io/static/v1?label=&message=youtube&color=FF0000&logo=youtube&logoColor=white&style=for-the-badge)](https://www.youtube.com/@MeSientoProgramador)
[![linkedin](https://img.shields.io/static/v1?label=&message=linkedin&color=0e76a8&logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/coderbeltran/)
[![github](https://img.shields.io/static/v1?label=&message=github&color=171515&logo=github&logoColor=white&style=for-the-badge)](https://github.com/coderbeltran)


<h2> / Habilidades /</h2>

#### Lenguajes de Programación:

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)&nbsp;
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)&nbsp;



#### Base de Datos

![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)&nbsp;
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)&nbsp;

#### Herramientas y Tecnologías

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)&nbsp;
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)&nbsp;
<!-- ![AWS](https://img.shields.io/badge/Amazon_AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)&nbsp;
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)&nbsp; -->

#### IDEs

![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)&nbsp;
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)&nbsp;
![PyCharm](https://img.shields.io/badge/pycharm-143?style=for-the-badge&logo=pycharm&logoColor=black&color=black&labelColor=green)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)&nbsp;
![Vim](https://img.shields.io/badge/VIM-%2311AB00.svg?style=for-the-badge&logo=vim&logoColor=white)&nbsp;

### ⚙️ &nbsp;GitHub Analytics
<p align="center">
<a href="https://github.com/coderbeltran">
  <div style="background-color: #f2f2f2; padding: 20px; border-radius: 5px;">
  <a href="https://github.com/coderbeltran">
    <img src="https://github-readme-stats.vercel.app/api?username=coderbeltran&show_icons=true&theme=radical" alt="GitHub stats">
  </a>
</div>
<div style="background-color: #f2f2f2; padding: 20px; border-radius: 5px;">
  <a href="https://github.com/coderbeltran">
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=coderbeltran&layout=compact" alt="Top Languages">
  </a>
</div>
</a>
</p>









