<style>
  body {
    background: linear-gradient(to bottom, #FFFFFF, #ADD8E6);
    margin: 0;
    padding: 0;
    min-height: 100vh;
    font-family: Arial, sans-serif;
  }

  /* Smooth fade-in for header */
  .fade-in {
    animation: fade 2s ease-in-out infinite alternate;
  }
  @keyframes fade {
    0% { opacity: 0.7; }
    100% { opacity: 1; }
  }

  /* Slide effect for tagline */
  .slide-in {
    animation: slide 3s ease-in-out infinite alternate;
  }
  @keyframes slide {
    0% { transform: translateX(-8px); }
    100% { transform: translateX(8px); }
  }

  /* IoT LED blink */
  .led-blink {
    animation: blink 1s infinite;
  }
  @keyframes blink {
    0%, 100% { background: #00ff00; box-shadow: 0 0 10px #00ff00; }
    50% { background: #006400; box-shadow: none; }
  }

  /* Sensor rotation */
  .sensor-rotate {
    animation: rotate 4s linear infinite;
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
    0%, 100% { transform: scale(1); box-shadow: 0 0 5px #00f; }
    50% { transform: scale(1.2); box-shadow: 0 0 20px #0ff; }
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

  /* Date/Time */
  .datetime {
    font-size: 16px;
    color: #000000;
    margin-top: 10px;
  }

  /* Responsive tables */
  table {
    max-width: 90%;
    border-collapse: collapse;
  }
  td {
    padding: 10px;
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
