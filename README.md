<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=bathiyapunsara.bathiyapunsara" />

<h1 align="center">
    <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+Bathiya+Punsara!;" />
</h1>


<h3 align="center">A passionate frontend developer from Sri Lanka 🇱🇰</h3>

<br/>

<div align="center">
 
 🔭 I’m currently working on **frontend development projects**
 
 🌱 I’m currently learning **Flutter, Dart, and .NET**

💬 Ask me about **React, JavaScript, or anything [here](https://github.com/bathiyapunsara/bathiyapunsara/issues)**

⚡ Fun fact **The first computer virus was created in 1986 and was named "Brain"**

</div>
 
<div align="center"> 
  <a href="mailto:hbpunsara@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-333333?style=for-the-badge&logo=gmail&logoColor=red" />
  </a>
  <a href="https://www.linkedin.com/in/bathiya-punsara-8056b026b" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank" />
  </a>
  <a href="https://bathiyapunsara.github.io" target="_blank">
     <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" target="_blank" />
  </a>
</div>

<hr/>
 
<h2 align="center">⚒️ Languages-Frameworks-Tools ⚒️</h2>
<br/>
<div align="center">
    <img src="https://skillicons.dev/icons?i=react,bootstrap,html,css,vscode,github,figma,tailwind,git,flutter" />
    <img src="https://skillicons.dev/icons?i=javascript,typescript,nodejs,python,mongodb,mysql,dotnet,php,c,cpp,csharp" /><br>
</div>

<br/>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Snake Effect</title>
  <style>
    body {
      margin: 0;
      padding: 0;
      background-color: #0d1117;
    }
    
    .snake {
      position: absolute;
      width: 10px;
      height: 10px;
      background-color: #2ea043;
      border-radius: 50%;
      animation: snake 5s linear infinite;
    }
    
    @keyframes snake {
      0% {
        left: 0;
        top: 0;
      }
      100% {
        left: 100%;
        top: 100%;
      }
    }
  </style>
</head>
<body>
  <div class="snake"></div>
  <script>
    const snake = document.querySelector('.snake');
    
    function createSnake() {
      const newSnake = snake.cloneNode();
      newSnake.style.left = Math.random() * 100 + '%';
      newSnake.style.top = Math.random() * 100 + '%';
      document.body.appendChild(newSnake);
      
      setTimeout(() => {
        newSnake.remove();
      }, 5000);
    }
    
    setInterval(createSnake, 250);
  </script>
</body>
</html>
<br/>
