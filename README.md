<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 200">
  <style>
    @keyframes fadeIn {
      0% { opacity: 0; }
      100% { opacity: 1; }
    }
    
    @keyframes wave {
      0% { transform: rotate(0deg); }
      25% { transform: rotate(15deg); }
      50% { transform: rotate(0deg); }
      75% { transform: rotate(-15deg); }
      100% { transform: rotate(0deg); }
    }
    
    .bg {
      fill: #f6f8fa;
    }
    
    .letter {
      font-family: 'Arial', sans-serif;
      font-weight: bold;
      opacity: 0;
    }
    
    .hi-letter {
      font-size: 42px;
      fill: #0366d6;
    }
    
    .name-letter {
      font-size: 38px;
      fill: #2d333b;
    }
    
    .cursor {
      fill: #0366d6;
      animation: blink 1s step-end infinite;
    }
    
    .wave-emoji {
      font-size: 42px;
      opacity: 0;
      transform-origin: 70% 70%;
    }
    
    @keyframes blink {
      from, to { opacity: 1; }
      50% { opacity: 0; }
    }
  </style>
  
  <!-- Background -->
  <rect class="bg" width="800" height="200" rx="10" ry="10"/>
  
  <!-- First text: "Hi there" with waving hand emoji -->
  <text x="220" y="80" class="wave-emoji" style="animation: fadeIn 0.3s ease-out forwards, wave 1.5s 3s infinite; animation-delay: 0.1s;">👋</text>
  <text x="270" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 0.3s;">H</text>
  <text x="295" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 0.6s;">i</text>
  <text x="310" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 0.9s;"> </text>
  <text x="325" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 1.2s;">t</text>
  <text x="340" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 1.5s;">h</text>
  <text x="360" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 1.8s;">e</text>
  <text x="380" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 2.1s;">r</text>
  <text x="395" y="80" class="letter hi-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 2.4s;">e</text>
  
  <!-- Second text: "I'm Anton Luckshman" -->
  <text x="200" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 3.0s;">I</text>
  <text x="210" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 3.2s;">'</text>
  <text x="220" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 3.4s;">m</text>
  <text x="250" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 3.6s;"> </text>
  <text x="265" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 3.8s;">A</text>
  <text x="290" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 4.0s;">n</text>
  <text x="310" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 4.2s;">t</text>
  <text x="325" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 4.4s;">o</text>
  <text x="345" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 4.6s;">n</text>
  <text x="365" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 4.8s;"> </text>
  <text x="380" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 5.0s;">L</text>
  <text x="400" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 5.2s;">u</text>
  <text x="420" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 5.4s;">c</text>
  <text x="440" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 5.6s;">k</text>
  <text x="460" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 5.8s;">s</text>
  <text x="475" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 6.0s;">h</text>
  <text x="495" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 6.2s;">m</text>
  <text x="525" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 6.4s;">a</text>
  <text x="545" y="130" class="letter name-letter" style="animation: fadeIn 0.3s ease-out forwards; animation-delay: 6.6s;">n</text>
  
  <!-- Typing cursor -->
  <rect x="565" y="115" width="3" height="25" class="cursor">
    <animate attributeName="x" values="395,565" dur="3s" begin="2.4s" fill="freeze" />
  </rect>
  
  <!-- Decorative elements -->
  <circle cx="150" cy="50" r="8" fill="#0366d6" opacity="0">
    <animate attributeName="opacity" from="0" to="0.7" dur="0.5s" begin="1s" fill="freeze" />
    <animate attributeName="r" values="8;12;8" dur="3s" repeatCount="indefinite" begin="1s" />
  </circle>
  <circle cx="650" cy="150" r="10" fill="#6f42c1" opacity="0">
    <animate attributeName="opacity" from="0" to="0.7" dur="0.5s" begin="2s" fill="freeze" />
    <animate attributeName="r" values="10;15;10" dur="3s" repeatCount="indefinite" begin="2s" />
  </circle>
  <circle cx="700" cy="70" r="6" fill="#ea4aaa" opacity="0">
    <animate attributeName="opacity" from="0" to="0.7" dur="0.5s" begin="3s" fill="freeze" />
    <animate attributeName="r" values="6;9;6" dur="2.5s" repeatCount="indefinite" begin="3s" />
  </circle>
  <circle cx="100" cy="130" r="7" fill="#2188ff" opacity="0">
    <animate attributeName="opacity" from="0" to="0.7" dur="0.5s" begin="4s" fill="freeze" />
    <animate attributeName="r" values="7;11;7" dur="2.2s" repeatCount="indefinite" begin="4s" />
  </circle>
</svg>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=antonluckshman&label=Profile%20views&color=0e75b6&style=flat" alt="antonluckshman" /> </p>
# 💫 About Me:
🔭 I’m currently working on<br>👯 I’m looking to collaborate on<br>🤝 I’m looking for help with<br>🌱 I’m currently learning<br>💬 Ask me about<br>⚡ Fun fact


## 🌐 Socials:
[![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?logo=Facebook&logoColor=white)](https://facebook.com/profile.php?id=100090531630192) [![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=Instagram&logoColor=white)](https://instagram.com/antonluckshman) [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/anton-luckshman-53121a265) [![email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:antonluckshman2@gmail.com) 

# 💻 Tech Stack:
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=for-the-badge&logo=powershell&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white) ![Azure](https://img.shields.io/badge/azure-%230072C6.svg?style=for-the-badge&logo=microsoftazure&logoColor=white) ![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white) ![Vercel](https://img.shields.io/badge/vercel-%23000000.svg?style=for-the-badge&logo=vercel&logoColor=white) ![Netlify](https://img.shields.io/badge/netlify-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=#00C7B7) ![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase) ![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white) ![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB) ![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white) ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white) ![Apache Tomcat](https://img.shields.io/badge/apache%20tomcat-%23F8DC75.svg?style=for-the-badge&logo=apache-tomcat&logoColor=black) ![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white) ![Jenkins](https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white) ![Apache](https://img.shields.io/badge/apache-%23D42029.svg?style=for-the-badge&logo=apache&logoColor=white) ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) ![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Firebase](https://img.shields.io/badge/firebase-a08021?style=for-the-badge&logo=firebase&logoColor=ffcd34) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=for-the-badge&logo=Canva&logoColor=white) ![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=antonLukshman&theme=radical&hide_border=false&include_all_commits=true&count_private=true)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=antonLukshman&theme=radical&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=antonLukshman&theme=radical&hide_border=false&include_all_commits=true&count_private=true&layout=compact)

## 🏆 GitHub Trophies
![](https://github-profile-trophy.vercel.app/?username=antonLukshman&theme=radical&no-frame=false&no-bg=true&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=antonLukshman&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=antonLukshman&icon=0&color=0)](https://visitcount.itsvg.in)

  ## 💰 You can help me by Donating
  [![BuyMeACoffee](https://img.shields.io/badge/Buy%20Me%20a%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/buymeacoffee.com/antonluckshman) 

  
<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
