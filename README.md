<style>
  body {
    background: linear-gradient(to bottom, #FFFFFF, #ADD8E6);
    margin: 0;
    padding: 0;
    min-height: 100vh;
  }

  /* Smooth fade-in for header */
  .fade-in {
    animation: fade 2s ease-in-out infinite alternate;
  }
  @keyframes fade {
    0% { opacity: 0.6; }
    100% { opacity: 1; }
  }

  /* Slide effect for tagline */
  .slide-in {
    animation: slide 3s infinite alternate;
  }
  @keyframes slide {
    0% { transform: translateX(-10px); }
    100% { transform: translateX(10px); }
  }

  /* IoT LED blink */
  .led-blink {
    animation: blink 1s infinite;
  }
  @keyframes blink {
    0% { background: #00ff00; box-shadow: 0 0 10px #00ff00; }
    50% { background: #006400; box-shadow: none; }
    100% { background: #00ff00; box-shadow: 0 0 10px #00ff00; }
  }

  /* Sensor rotation animation */
  .sensor-rotate {
    animation: rotate 4s infinite linear;
  }
  @keyframes rotate {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }

  /* Data pulse effect */
  .data-pulse {
    animation: pulse 1.5s infinite;
  }
  @keyframes pulse {
    0% { transform: scale(1); box-shadow: 0 0 5px #00f; }
    50% { transform: scale(1.2); box-shadow: 0 0 20px #0ff; }
    100% { transform: scale(1); box-shadow: 0 0 5px #00f; }
  }

  /* Wireless signal wave */
  .signal-wave {
    animation: wave 2s infinite;
  }
  @keyframes wave {
    0% { box-shadow: 0 0 0 0 rgba(0, 255, 0, 0.5); }
    70% { box-shadow: 0 0 0 15px rgba(0, 255, 0, 0); }
    100% { box-shadow: 0 0 0 0 rgba(0, 255, 0, 0.5); }
  }

  .datetime {
    font-size: 16px;
    color: #000000;
    margin-top: 10px;
  }
</style>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=250&section=header&color=0:FFFFFF,100:ADD8E6&text=Hello,%20I'm%20Sachira&fontColor=000000&fontSize=50&animation=twinkling&stroke=000000&strokeWidth=1" class="fade-in" />
  <div id="datetime" class="datetime"></div>
</div>

<h3 align="center" style="color:#000000;">💡 Undergraduate Student | IoT & Embedded Systems Enthusiast | ESP32/Arduino Developer | Learning Full-Stack Web Development</h3>

<!-- IoT Animation Icons -->
<div align="center" style="margin: 20px;">
  <span class="led-blink" style="display:inline-block;width:15px;height:15px;border-radius:50%;"></span>
  <img src="https://skillicons.dev/icons?i=arduino" class="sensor-rotate" width="40"/>
  <span class="data-pulse" style="display:inline-block;width:15px;height:15px;border-radius:50%;background:#00f;margin-left:10px;"></span>
  <span class="signal-wave" style="display:inline-block;width:15px;height:15px;border-radius:50%;background:#0f0;margin-left:10px;"></span>
</div>

<!-- Typing Animation -->
<div align="center" class="slide-in">
  <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&duration=3000&pause=1000&color=000000&background=FFFFFF00&center=true&vCenter=true&width=800&height=50&lines=Crop+Recommendation+System+Developer;Real-time+IoT+Sensor+Integration;Building+Sustainable+Farming+Solutions;Passionate+About+Smart+Agriculture+🌱" />
</div>

<!-- Profile Badges -->
<div align="center" style="margin-top:15px;">
  <img src="https://komarev.com/ghpvc/?username=Sachira263&label=Profile%20Views&style=for-the-badge&color=FFFFFF&labelColor=000000" />
  <img src="https://img.shields.io/github/followers/Sachira263?label=Followers&style=for-the-badge&color=ADD8E6&labelColor=000000" />
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-FFFFFF?style=for-the-badge&labelColor=000000" />
</div>

<script>
function updateDateTime() {
  const now = new Date();
  now.setHours(20, 8, 0, 0);
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
  document.getElementById('datetime').innerText = `Last Updated: ${now.toLocaleString('en-US', options)}`;
}
updateDateTime();
setInterval(updateDateTime, 60000);
</script>

<h3 align="center">🌟 What I'm Up To</h3>

<div align="center">
<table>
<tr>
<td width="33%" align="center">🚀 <b>Currently Building</b><br>Crop Recommendation System<br>IoT Sensor Integration<br>Microservices with Spring Boot</td>
<td width="33%" align="center">📚 <b>Learning Journey</b><br>Advanced ML Models<br>Weather API Integration<br>Spring Boot & Docker</td>
<td width="33%" align="center">🎯 <b>Future Goals</b><br>Pest Prediction System<br>Mobile App for Farmers<br>Open Source Agri-Tech</td>
</tr>
</table>
</div>

<h3 align="center">📊 GitHub Journey</h3>

<div align="center">
<table>
<tr>
<td width="50%" align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Sachira263&theme=light&show_icons=true&count_private=true"/>
  <br/><br/>
  <img src="https://streak-stats.demolab.com/?user=Sachira263&count_private=true&theme=light"/>
</td>
<td width="50%" align="center">
  <img src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=Sachira263&theme=light&langs_count=10"/>
</td>
</tr>
</table>
</div>

<h3 align="center">🛠️ Technology Stack</h3>

<div align="center" class="fade-in">
  <b>Programming Languages</b><br/>
  <img src="https://skillicons.dev/icons?i=js,python,cpp,java" /><br/><br/>
  <b>Frontend & Backend</b><br/>
  <img src="https://skillicons.dev/icons?i=react,nodejs,express,flask,spring" /><br/><br/>
  <b>Databases & IoT</b><br/>
  <img src="https://skillicons.dev/icons?i=mongodb" /> 
  <img src="https://skillicons.dev/icons?i=arduino" class="sensor-rotate" style="margin-left:10px;" /><br/><br/>
  <b>DevOps & Tools</b><br/>
  <img src="https://skillicons.dev/icons?i=docker,git,github,postman,vscode" />
</div>

<div align="center" style="margin-top: 20px;">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=light&quote=The%20future%20of%20agriculture%20lies%20in%20data-driven%20decisions&author=Sachira%20Nadeesharika" />
</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer&color=0:FFFFFF,100:ADD8E6" />
</div>

<h4 align="center">💖 Thanks for visiting! Let's grow smarter agriculture together! 🌾</h4>
