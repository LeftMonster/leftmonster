### lately, I'm join the community formally.(2023.9)
<img align="left" src="https://github-readme-stats.vercel.app/api?username=leftmonster&include_all_commits=true&count_private-true&custom_title=leftmonster'%20GitHub%20Stats&line_height=30&show_icons=true&hide_border=true&bg_color=192133&title_color=efb752&icon_color=efb752&text_color=70bed9">

被网络抢劫了☘☘☘☘

- 🔭 I’m currently working on とうきょうだいがく
- 🌱 I’m currently learning all kinds of CS（コンピュータサイエンス）.
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 📫 How to reach me: Data Science & CyberSecurity【赛博保安】
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

![](https://github.com/LeftMonster/leftmonster/blob/main/github-contribution-grid-snake.svg)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My GitHub Music Page</title>
  <style>
    body {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background: #111;
      color: #fff;
      font-family: sans-serif;
      text-align: center;
    }
    button {
      margin: 10px;
      padding: 10px 20px;
      font-size: 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      background: #4CAF50;
      color: white;
    }
    #langBtn {
      background: #2196F3;
    }
  </style>
</head>
<body>
  <!-- Intro text (default English) -->
  <div id="intro">
    <h1>🎶 Welcome to my page 🎶</h1>
    <p>This page comes with background music. Click the button below to enable sound.</p>
  </div>

  <!-- Background music -->
  <audio id="bgm" autoplay loop muted>
    <source src="music/Sultan.mp3" type="audio/mpeg">
    Your browser does not support the audio element.
  </audio>

  <!-- Buttons -->
  <button onclick="unmute()">Enable Sound</button>
  <button id="langBtn" onclick="toggleLang()">中文 / English</button>

  <script>
    const intro = document.getElementById("intro");
    let isEnglish = true;

    function unmute() {
      const bgm = document.getElementById("bgm");
      bgm.muted = false;
      bgm.play();
    }

    function toggleLang() {
      if (isEnglish) {
        intro.innerHTML = `
          <h1>🎶 欢迎来到我的主页 🎶</h1>
          <p>本页面带有背景音乐，请点击下方按钮开启声音。</p>
        `;
        document.getElementById("langBtn").innerText = "English / 中文";
      } else {
        intro.innerHTML = `
          <h1>🎶 Welcome to my page 🎶</h1>
          <p>This page comes with background music. Click the button below to enable sound.</p>
        `;
        document.getElementById("langBtn").innerText = "中文 / English";
      }
      isEnglish = !isEnglish;
    }
  </script>
</body>
</html>
