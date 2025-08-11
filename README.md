<style>
  body {
    background: linear-gradient(to bottom, #FFFFFF, #ADD8E6);
    margin: 0;
    padding: 0;
    min-height: 100vh;
  }
  .fade-in {
    animation: fade 2s infinite;
  }
  @keyframes fade {
    0% { opacity: 0.5; }
    100% { opacity: 1; }
  }
  .slide-in {
    animation: slide 3s infinite alternate;
  }
  @keyframes slide {
    0% { transform: translateX(-10px); }
    100% { transform: translateX(10px); }
  }
  .chart-container img {
    background: linear-gradient(to bottom, #FFFFFF, #ADD8E6);
    border-radius: 10px;
    padding: 10px;
  }
  .header-image {
    background: linear-gradient(to right, #00008B, #FFFFFF);
    border-radius: 10px;
    padding: 10px;
  }
  .led-blink {
    animation: blink 1s infinite;
  }
  @keyframes blink {
    0% { opacity: 1; }
    50% { opacity: 0; }
    100% { opacity: 1; }
  }
  .sensor-rotate {
    animation: rotate 4s infinite linear;
  }
  @keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .data-pulse {
    animation: pulse 2s infinite;
  }
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.2); }
    100% { transform: scale(1); }
  }
  .signal-wave {
    animation: wave 3s infinite;
    position: relative;
    top: -5px;
    left: 5px;
  }
  @keyframes wave {
    0% { box-shadow: 0 0 0 0 rgba(0, 255, 0, 0.4); }
    50% { box-shadow: 0 0 0 10px rgba(0, 255, 0, 0); }
    100% { box-shadow: 0 0 0 0 rgba(0, 255, 0, 0.4); }
  }
  .datetime {
    font-size: 16px;
    color: #000000;
    margin-top: 10px;
  }
</style>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=250&section=header&color=0:FFFFFF,100:ADD8E6&text=Hello,%20I'm%20Sachira&fontColor=000000&fontSize=50&fontAlign=50&animation=twinkling&stroke=000000&strokeWidth=1" class="fade-in header-image" />
  <div id="datetime" class="datetime"></div>
</div>

<h3 align="center" style="color:#000000;">✨ Undergraduate Student | IoT & Embedded Systems Enthusiast | ESP32/Arduino Developer | Learning Full-Stack Web Development ✨</h3>

<div align="center" class="slide-in">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&duration=3000&pause=1000&color=000000&background=FFFFFF00&center=true&vCenter=true&width=800&height=50&lines=Crop+Recommendation+System+Developer;Integrating+IoT+%26+Microservices;Building+Sustainable+Farming+Solutions;Passionate+About+Smart+Agriculture+🌱" alt="Typing Animation" />
</div>

<div align="center" style="margin-top:15px;">
  <img src="https://komarev.com/ghpvc/?username=Sachira263&label=Profile%20Views&style=for-the-badge&color=FFFFFF&labelColor=000000" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Sachira263?label=Followers&style=for-the-badge&color=ADD8E6&labelColor=000000" alt="Followers" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-FFFFFF?style=for-the-badge&labelColor=000000" alt="Status" />
</div>
<br/>

<script>
const sachira = {
  name: "K.A.S.S. Nadeesharika",
  location: "Kandy, Sri Lanka 🇱🇰",
  email: "nadeesharika@example.com",
  pronouns: "She/Her",
  languages: ["JavaScript", "Python", "C++", "Java"],
  passionateAbout: [
    "Smart Agriculture",
    "IoT Integration",
    "Microservices Architecture",
    "Machine Learning",
    "Web Development",
    "Sustainable Farming"
  ],
  techStack: {
    frontend: ["React.js"],
    backend: ["Node.js", "Express.js", "Flask", "Spring Boot"],
    databases: ["MongoDB"],
    iot: ["ESP32", "DHT11", "Soil Moisture Sensor"],
    devops: ["Docker"],
    architecture: ["Microservices"],
    tools: ["Git", "GitHub", "Postman", "VS Code"]
  },
  currentlyLearning: ["Advanced ML Models", "Weather API Integration", "Mobile App Development", "Spring Boot Microservices"],
  hobbies: [
    "Exploring IoT Solutions",
    "Reading Agri-Tech Research",
    "Mentoring Peers",
    "Nature Exploration 🌾"
  ],
  motto: "Empowering farmers with data-driven solutions 🌱"
};

// Display current date and time
function updateDateTime() {
  const now = new Date();
  now.setHours(20, 8, 0, 0); // Set to 08:08 PM +0530, August 11, 2025
  const options = { 
    weekday: 'long', 
    year: 'numeric', 
    month: 'long', 
    day: 'numeric', 
    hour: '2-digit', 
    minute: '2-digit', 
    timeZone: 'Asia/Colombo', 
    timeZoneName: 'short' 
  };
  const datetimeStr = now.toLocaleString('en-US', options).replace('GMT', 'UTC');
  document.getElementById('datetime').innerText = `Last Updated: ${datetimeStr}`;
}
updateDateTime();
setInterval(updateDateTime, 60000); // Update every minute
</script>

<h3 align="center">🌟 What I'm Up To</h3>

<div align="center">
<table align="center">
<tr border="none">
<td width="33%" align="center">🚀 <b>Currently Building</b><br>Crop Recommendation System<br>IoT Sensor Integration<br>Microservices with Spring Boot</td>
<td width="33%" align="center">📚 <b>Learning Journey</b><br>Advanced ML Models<br>Weather API Integration<br>Spring Boot & Docker</td>
<td width="33%" align="center">🎯 <b>Future Goals</b><br>Pest Prediction System<br>Mobile App for Farmers<br>Open Source Agri-Tech</td>
</tr>
</table>
</div>

<h3 align="center">📊 GitHub Journey</h3>

<div align="center" class="chart-container">
<table align="center">
<tr border="none">
<td width="50%" align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=Sachira263&theme=light&show_icons=true&count_private=true"/>
  <br/><br/>
  <img align="center" src="https://streak-stats.demolab.com/?user=Sachira263&count_private=true&theme=light"/>
</td>
<td width="50%" align="center">
  <img align="center" src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=Sachira263&theme=light&hide_border=false&no-bg=true&no-frame=true&langs_count=10"/>
</td>
</tr>
</table>
</div>

<h3 align="center">🛠️ Technology Stack</h3>

<div align="center" class="fade-in">
  <b>Programming Languages</b><br/>
  <img src="https://skillicons.dev/icons?i=js,python,cpp,java" />
  <br/><br/>
  <b>Frontend & Backend</b><br/>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,flask,spring" />
  <br/><br/>
  <b>Databases & IoT</b><br/>
  <div style="display: inline-block; position: relative;">
    <img src="https://skillicons.dev/icons?i=mongodb" />
    <span class="led-blink" style="display: inline-block; width: 10px; height: 10px; background: red; border-radius: 50%; position: absolute; top: 5px; left: 5px;"></span>
    <span class="signal-wave" style="display: inline-block; width: 15px; height: 15px; background: green; border-radius: 50%; margin-left: 5px;"></span>
  </div>
  <img src="https://skillicons.dev/icons?i=arduino" class="sensor-rotate" style="display: inline-block; margin-left: 10px;" />
  <br/><br/>
  <b>DevOps & Architecture</b><br/>
  <img src="https://skillicons.dev/icons?i=docker" class="data-pulse" />
  <br/><br/>
  <b>Tools</b><br/>
  <img src="https://skillicons.dev/icons?i=git,github,postman,vscode" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

<h3 align="center">🤝 Let's Connect & Collaborate</h3>

<div align="center">
<a href="https://www.linkedin.com/in/sachira-nadeesharika" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:nadeesharika@example.com" target="_blank">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>
<a href="https://twitter.com/SachiraNadeesharika" target="_blank">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
</a>
<a href="https://dev.to/sachira" target="_blank">
  <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="Dev.to"/>
</a>
</div>
<br/>

<div align="center" style="margin-top: 20px;">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light&quote=The%20future%20of%20agriculture%20lies%20in%20data-driven%20decisions&author=Sachira%20Nadeesharika" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:FFFFFF,100:ADD8E6" />
</div>

<h4 align="center">💖 Thanks for visiting! Let's grow smarter agriculture together! 🌾</h4><style>
  body {
    background: linear-gradient(to bottom, #FFFFFF, #ADD8E6);
    margin: 0;
    padding: 0;
    min-height: 100vh;
  }
  .fade-in {
    animation: fade 2s infinite;
  }
  @keyframes fade {
    0% { opacity: 0.5; }
    100% { opacity: 1; }
  }
  .slide-in {
    animation: slide 3s infinite alternate;
  }
  @keyframes slide {
    0% { transform: translateX(-10px); }
    100% { transform: translateX(10px); }
  }
  .chart-container img {
    background: linear-gradient(to bottom, #FFFFFF, #ADD8E6);
    border-radius: 10px;
    padding: 10px;
  }
  .header-image {
    background: linear-gradient(to right, #00008B, #FFFFFF);
    border-radius: 10px;
    padding: 10px;
  }
  .led-blink {
    animation: blink 1s infinite;
  }
  @keyframes blink {
    0% { opacity: 1; }
    50% { opacity: 0; }
    100% { opacity: 1; }
  }
  .sensor-rotate {
    animation: rotate 4s infinite linear;
  }
  @keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .data-pulse {
    animation: pulse 2s infinite;
  }
  @keyframes pulse {
    0% { transform: scale(1); }
    50% { transform: scale(1.2); }
    100% { transform: scale(1); }
  }
  .signal-wave {
    animation: wave 3s infinite;
    position: relative;
    top: -5px;
    left: 5px;
  }
  @keyframes wave {
    0% { box-shadow: 0 0 0 0 rgba(0, 255, 0, 0.4); }
    50% { box-shadow: 0 0 0 10px rgba(0, 255, 0, 0); }
    100% { box-shadow: 0 0 0 0 rgba(0, 255, 0, 0.4); }
  }
  .datetime {
    font-size: 16px;
    color: #000000;
    margin-top: 10px;
  }
</style>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=250&section=header&color=0:FFFFFF,100:ADD8E6&text=Hello,%20I'm%20Sachira&fontColor=000000&fontSize=50&fontAlign=50&animation=twinkling&stroke=000000&strokeWidth=1" class="fade-in header-image" />
  <div id="datetime" class="datetime"></div>
</div>

<h3 align="center" style="color:#000000;">✨ Undergraduate Student | IoT & Embedded Systems Enthusiast | ESP32/Arduino Developer | Learning Full-Stack Web Development ✨</h3>

<div align="center" class="slide-in">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&duration=3000&pause=1000&color=000000&background=FFFFFF00&center=true&vCenter=true&width=800&height=50&lines=Crop+Recommendation+System+Developer;Integrating+IoT+%26+Microservices;Building+Sustainable+Farming+Solutions;Passionate+About+Smart+Agriculture+🌱" alt="Typing Animation" />
</div>

<div align="center" style="margin-top:15px;">
  <img src="https://komarev.com/ghpvc/?username=Sachira263&label=Profile%20Views&style=for-the-badge&color=FFFFFF&labelColor=000000" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Sachira263?label=Followers&style=for-the-badge&color=ADD8E6&labelColor=000000" alt="Followers" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-FFFFFF?style=for-the-badge&labelColor=000000" alt="Status" />
</div>
<br/>

<script>
const sachira = {
  name: "K.A.S.S. Nadeesharika",
  location: "Kandy, Sri Lanka 🇱🇰",
  email: "nadeesharika@example.com",
  pronouns: "She/Her",
  languages: ["JavaScript", "Python", "C++", "Java"],
  passionateAbout: [
    "Smart Agriculture",
    "IoT Integration",
    "Microservices Architecture",
    "Machine Learning",
    "Web Development",
    "Sustainable Farming"
  ],
  techStack: {
    frontend: ["React.js"],
    backend: ["Node.js", "Express.js", "Flask", "Spring Boot"],
    databases: ["MongoDB"],
    iot: ["ESP32", "DHT11", "Soil Moisture Sensor"],
    devops: ["Docker"],
    architecture: ["Microservices"],
    tools: ["Git", "GitHub", "Postman", "VS Code"]
  },
  currentlyLearning: ["Advanced ML Models", "Weather API Integration", "Mobile App Development", "Spring Boot Microservices"],
  hobbies: [
    "Exploring IoT Solutions",
    "Reading Agri-Tech Research",
    "Mentoring Peers",
    "Nature Exploration 🌾"
  ],
  motto: "Empowering farmers with data-driven solutions 🌱"
};

// Display current date and time
function updateDateTime() {
  const now = new Date();
  now.setHours(20, 8, 0, 0); // Set to 08:08 PM +0530, August 11, 2025
  const options = { 
    weekday: 'long', 
    year: 'numeric', 
    month: 'long', 
    day: 'numeric', 
    hour: '2-digit', 
    minute: '2-digit', 
    timeZone: 'Asia/Colombo', 
    timeZoneName: 'short' 
  };
  const datetimeStr = now.toLocaleString('en-US', options).replace('GMT', 'UTC');
  document.getElementById('datetime').innerText = `Last Updated: ${datetimeStr}`;
}
updateDateTime();
setInterval(updateDateTime, 60000); // Update every minute
</script>

<h3 align="center">🌟 What I'm Up To</h3>

<div align="center">
<table align="center">
<tr border="none">
<td width="33%" align="center">🚀 <b>Currently Building</b><br>Crop Recommendation System<br>IoT Sensor Integration<br>Microservices with Spring Boot</td>
<td width="33%" align="center">📚 <b>Learning Journey</b><br>Advanced ML Models<br>Weather API Integration<br>Spring Boot & Docker</td>
<td width="33%" align="center">🎯 <b>Future Goals</b><br>Pest Prediction System<br>Mobile App for Farmers<br>Open Source Agri-Tech</td>
</tr>
</table>
</div>

<h3 align="center">📊 GitHub Journey</h3>

<div align="center" class="chart-container">
<table align="center">
<tr border="none">
<td width="50%" align="center">
  <img align="center" src="https://github-readme-stats.vercel.app/api?username=Sachira263&theme=light&show_icons=true&count_private=true"/>
  <br/><br/>
  <img align="center" src="https://streak-stats.demolab.com/?user=Sachira263&count_private=true&theme=light"/>
</td>
<td width="50%" align="center">
  <img align="center" src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=Sachira263&theme=light&hide_border=false&no-bg=true&no-frame=true&langs_count=10"/>
</td>
</tr>
</table>
</div>

<h3 align="center">🛠️ Technology Stack</h3>

<div align="center" class="fade-in">
  <b>Programming Languages</b><br/>
  <img src="https://skillicons.dev/icons?i=js,python,cpp,java" />
  <br/><br/>
  <b>Frontend & Backend</b><br/>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,flask,spring" />
  <br/><br/>
  <b>Databases & IoT</b><br/>
  <div style="display: inline-block; position: relative;">
    <img src="https://skillicons.dev/icons?i=mongodb" />
    <span class="led-blink" style="display: inline-block; width: 10px; height: 10px; background: red; border-radius: 50%; position: absolute; top: 5px; left: 5px;"></span>
    <span class="signal-wave" style="display: inline-block; width: 15px; height: 15px; background: green; border-radius: 50%; margin-left: 5px;"></span>
  </div>
  <img src="https://skillicons.dev/icons?i=arduino" class="sensor-rotate" style="display: inline-block; margin-left: 10px;" />
  <br/><br/>
  <b>DevOps & Architecture</b><br/>
  <img src="https://skillicons.dev/icons?i=docker" class="data-pulse" />
  <br/><br/>
  <b>Tools</b><br/>
  <img src="https://skillicons.dev/icons?i=git,github,postman,vscode" />
</div>

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">
</div>

<h3 align="center">🤝 Let's Connect & Collaborate</h3>

<div align="center">
<a href="https://www.linkedin.com/in/sachira-nadeesharika" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:nadeesharika@example.com" target="_blank">
  <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
</a>
<a href="https://twitter.com/SachiraNadeesharika" target="_blank">
  <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
</a>
<a href="https://dev.to/sachira" target="_blank">
  <img src="https://img.shields.io/badge/dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white" alt="Dev.to"/>
</a>
</div>
<br/>

<div align="center" style="margin-top: 20px;">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light&quote=The%20future%20of%20agriculture%20lies%20in%20data-driven%20decisions&author=Sachira%20Nadeesharika" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:FFFFFF,100:ADD8E6" />
</div>

<h4 align="center">💖 Thanks for visiting! Let's grow smarter agriculture together! 🌾</h4>
