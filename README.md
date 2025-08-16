<h1 align="center" style="font-size:28px; font-weight:bold; color:#00cc44;">
  Hello, I'm Teja, <span id="animated-text" style="color:#32CD32"></span>
</h1>

<script>
const texts = ["Data Analyst", "Fullstack Dev", "AI Enthusiast"];
let index = 0;
const element = document.getElementById("animated-text");

function typeText(text, callback) {
  let i = 0;
  element.textContent = "";
  const interval = setInterval(() => {
    element.textContent += text[i];
    i++;
    if (i === text.length) {
      clearInterval(interval);
      setTimeout(callback, 1000); // wait 1s then callback
    }
  }, 150);
}

function deleteText(callback) {
  let text = element.textContent;
  let i = text.length;
  const interval = setInterval(() => {
    element.textContent = text.substring(0, i-1);
    i--;
    if (i === 0) {
      clearInterval(interval);
      setTimeout(callback, 500);
    }
  }, 100);
}

function loopAnimation() {
  typeText(texts[index], () => {
    deleteText(() => {
      index = (index + 1) % texts.length;
      loopAnimation();
    });
  });
}

loopAnimation();
</script>

<!-- About Me -->
## 🚀 About Me  
I enjoy learning by doing and I am passionate about transforming data into actionable insights.  
Proficient in **Java, Python, and SQL**, I actively use tools like **Power BI, Tableau, and Figma** to solve problems and visualize data effectively.  

Beyond coding, I focus on **AI-driven automation, prompt engineering, and hackathons** to stay ahead in this AI-driven era.  
I also participate in workshops, conferences, and competitions to expand my network and sharpen my technical edge.  

---

<!-- Skills -->
## 🛠️ Skills  

<p align="center">
  <!-- Row 1 -->
  <img src="https://cdn-icons-png.flaticon.com/512/226/226777.png" width="70"/>&nbsp;&nbsp; <!-- Java -->
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="55"/>&nbsp;&nbsp;
  <img src="https://cdn-icons-png.flaticon.com/512/4248/4248443.png" width="55"/>&nbsp;&nbsp; <!-- HTML -->
  <img src="https://upload.wikimedia.org/wikipedia/en/d/dd/MySQL_logo.svg" width="70"/>&nbsp;&nbsp; <!-- MySQL -->
  <img src="https://cdn.worldvectorlogo.com/logos/mongodb-icon-1.svg" width="55"/>&nbsp;&nbsp; <!-- MongoDB -->
  <img src="https://cdn-icons-png.flaticon.com/512/919/919825.png" width="55"/>&nbsp;&nbsp; <!-- NodeJS -->
  <img src="https://cdn.worldvectorlogo.com/logos/react-2.svg" width="55"/> <!-- ReactJS -->
</p>

<p align="center">
  <!-- Row 2 -->
  <img src="https://cdn-icons-png.flaticon.com/512/732/732212.png" width="55"/>&nbsp;&nbsp; <!-- CSS -->
  <img src="https://cdn-icons-png.flaticon.com/512/732/732190.png" width="55"/>&nbsp;&nbsp; <!-- JS -->
  <img src="https://cdn-icons-png.flaticon.com/512/5968/5968292.png" width="55"/>&nbsp;&nbsp; <!-- Figma -->
  <img src="https://cdn.worldvectorlogo.com/logos/tailwindcss.svg" width="55"/>&nbsp;&nbsp;
  <img src="https://cdn.worldvectorlogo.com/logos/git-icon.svg" width="55"/>&nbsp;&nbsp;
  <img src="https://cdn-icons-png.flaticon.com/512/919/919853.png" width="65"/>&nbsp;&nbsp; <!-- Docker -->
  <img src="https://cdn-icons-png.flaticon.com/512/733/733553.png" width="55"/> <!-- Linux -->
</p>

<p align="center">
  <!-- Row 3 (ML/DS Tools) -->
  <img src="https://upload.wikimedia.org/wikipedia/commons/3/31/NumPy_logo_2020.svg" width="90"/>&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Pandas_logo.svg" width="90"/>&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width="55"/>&nbsp;&nbsp;
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="55"/>&nbsp;&nbsp;
  <img src="https://pytorch.org/assets/images/pytorch-logo.png" width="85"/>&nbsp;&nbsp;
  <img src="https://cdn.worldvectorlogo.com/logos/tensorflow-2.svg" width="55"/>&nbsp;&nbsp;
  <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" width="55"/>&nbsp;&nbsp;
  <img src="https://cdn.worldvectorlogo.com/logos/tableau-software.svg" width="55"/>
</p>

---

<!-- GitHub Stats -->
## 📊 GitHub Stats  

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MallamTeja&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&title_color=006400&icon_color=006400&text_color=006400&bg_color=0D1117" height="160"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=MallamTeja&theme=dark&background=0D1117&ring=006400&fire=006400&currStreakLabel=006400&sideLabels=006400&dates=006400" height="160"/>
</p>

---

<!-- Coding Profiles -->
## 💻 Coding Profiles  

<p align="center">
  <a href="https://leetcode.com/tejamallam026" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/1/19/LeetCode_logo_black.png" width="55"/></a>&nbsp;&nbsp;
  <a href="https://www.codechef.com/users/tejamallam" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/4d/CodeChef_logo.png" width="55"/></a>&nbsp;&nbsp;
  <a href="https://www.hackerrank.com/mallamteja" target="_blank"><img src="https://cdn.worldvectorlogo.com/logos/hackerrank.svg" width="55"/></a>&nbsp;&nbsp;
  <a href="https://codeforces.com/profile/tejamallam" target="_blank"><img src="https://cdn.iconscout.com/icon/free/png-256/free-code-forces-3521352-2944796.png" width="55"/></a>&nbsp;&nbsp;
  <a href="https://auth.geeksforgeeks.org/user/mallamsi8z/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/43/GeeksforGeeks.svg" width="55"/></a>
</p>

---

<!-- Connect With Me -->
## 🌐 Connect With Me  

<p align="center">
  <a href="https://www.linkedin.com/in/mallam-teja/" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/174/174857.png" width="55"/></a>&nbsp;&nbsp;
  <a href="https://x.com/Mallam_Teja?s=09" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/5969/5969020.png" width="55"/></a>&nbsp;&nbsp;
  <a href="https://www.reddit.com/user/Salt_Owl5906/" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/3670/3670226.png" width="55"/></a>&nbsp;&nbsp;
  <a href="https://unstop.com/u/tejakqba8271" target="_blank"><img src="https://d8it4huxumps7.cloudfront.net/uploads/images/unstop/unstop-logo.svg" width="55"/></a>&nbsp;&nbsp;
  <a href="https://www.figma.com/@tejamallam" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/5968/5968705.png" width="55"/></a>&nbsp;&nbsp;
  <a href="https://github.com/MallamTeja" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/733/733609.png" width="55"/></a>
</p>
