<p align="center" width="300">
   <h3 align="center"> Framqueli 👨🏻‍💻</h3>
</p>


<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=FraMqueli&hide_title=false&hide_rank=false&show_icons=true&include_all_commits=true&count_private=true&disable_animations=false&theme=dracula&locale=en&hide_border=false" height="120" alt="stats graph"  />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=FraMqueli&locale=en&hide_title=false&layout=compact&card_width=320&langs_count=5&theme=dracula&hide_border=false" height="120" alt="languages graph"  />
</div>

<div align="center">
    <img src="https://th.bing.com/th/id/R.7b83b010c1b941aad40ecacd7bad6520?rik=kXuhpdMQN73vYQ&riu=http%3a%2f%2fi0.kym-cdn.com%2fphotos%2fimages%2foriginal%2f001%2f055%2f436%2f1e4.gif&ehk=2ZLoHo%2fm%2flU7m%2bULWQoQNJBiACunC05s1uoVHiIkPzI%3d&risl=&pid=ImgRaw&r=0"/>
</div>

<p align="center">

  <span style="width: 8px;"> </span>
   <a href="https://www.youtube.com/channel/UCkFV8dmKlR0swj3y7oRTXCA" target="blank">
    <img align="center" src="https://upload.wikimedia.org/wikipedia/commons/0/09/YouTube_full-color_icon_%282017%29.svg" alt="Canal de YouTube de Framqueli" height="23px" width="33px" />
  </a>
  <span style="width: 8px;"> </span>
  <a href="https://instagram.com/tu_canal" target="blank">
    <img align="center" src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Instagram_logo_2016.svg" alt="Canal de Instagram de Framqueli" height="23px" width="23px" />
</p>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Snake Animation</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #333;
        }

        .snake {
            display: flex;
            position: relative;
        }

        .snake div {
            width: 20px;
            height: 20px;
            background-color: lime;
            margin: 2px;
            border-radius: 50%;
            animation: move 2s linear infinite;
        }

        @keyframes move {
            0% {
                transform: translate(0, 0);
            }
            25% {
                transform: translate(100px, 0);
            }
            50% {
                transform: translate(100px, 100px);
            }
            75% {
                transform: translate(0, 100px);
            }
            100% {
                transform: translate(0, 0);
            }
        }

        .snake div:nth-child(2) {
            animation-delay: 0.2s;
        }

        .snake div:nth-child(3) {
            animation-delay: 0.4s;
        }

        .snake div:nth-child(4) {
            animation-delay: 0.6s;
        }

        .snake div:nth-child(5) {
            animation-delay: 0.8s;
        }
    </style>
</head>
<body>
    <div class="snake">
        <div></div>
        <div></div>
        <div></div>
        <div></div>
        <div></div>
    </div>
</body>