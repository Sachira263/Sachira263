<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sachira — IoT Profile</title>

  <style>
    :root {
      --bg1: #FFFFFF;
      --bg2: #ADD8E6;
      --accent: #0066cc;
      --iot-green: #00ff00;
      --iot-dark: #006400;
    }

    html,body {
      height:100%;
      margin:0;
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
      background: linear-gradient(to bottom, var(--bg1), var(--bg2));
      color:#000;
    }

    .container{max-width:980px;margin:24px auto;padding:18px}

    .header-img{
      display:block;
      margin:0 auto 12px;
      border-radius:12px;
      box-shadow:0 6px 18px rgba(0,0,0,0.08);
    }

    .fade-in{ animation:fade 2s ease-in-out infinite alternate; }
    @keyframes fade { 0%{opacity:.6} 100%{opacity:1} }

    .slide-in{ animation:slide 3s infinite alternate; }
    @keyframes slide { 0%{transform:translateX(-10px)} 100%{transform:translateX(10px)} }

    .led-blink{ width:14px;height:14px;border-radius:50%;display:inline-block;margin-right:10px;
      animation:ledblink 1s infinite; vertical-align:middle;
      box-shadow:0 0 10px rgba(0,255,0,0.6);
      background:var(--iot-green);
    }
    @keyframes ledblink{
      0%{background:var(--iot-green);box-shadow:0 0 10px rgba(0,255,0,0.6)}
      50%{background:var(--iot-dark);box-shadow:none}
      100%{background:var(--iot-green);box-shadow:0 0 10px rgba(0,255,0,0.6)}
    }

    .sensor-rotate{ width:40px; height:auto; display:inline-block; vertical-align:middle;
      animation:spin 4s linear infinite;
    }
    @keyframes spin{ from{transform:rotate(0deg)} to{transform:rotate(360deg)} }

    .data-pulse{ width:16px;height:16px;border-radius:50%;display:inline-block;margin:0 10px;
      animation:pulse 1.5s infinite; background:#00aaff; vertical-align:middle;
    }
    @keyframes pulse{ 0%{transform:scale(1);box-shadow:0 0 5px rgba(0,170,255,0.5)}
      50%{transform:scale(1.2);box-shadow:0 0 18px rgba(0,255,255,0.25)}
      100%{transform:scale(1);box-shadow:0 0 5px rgba(0,170,255,0.5)} }

    .signal-wave{ width:16px;height:16px;border-radius:50%;display:inline-block;margin-left:10px;
      background:#0f0; animation:wave 2s infinite; vertical-align:middle;
    }
    @keyframes wave{
      0%{box-shadow:0 0 0 0 rgba(0,255,0,0.5)}
      70%{box-shadow:0 0 0 15px rgba(0,255,0,0)}
      100%{box-shadow:0 0 0 0 rgba(0,255,0,0.5)}
    }

    .datetime{ font-size:14px; color:#000; margin-top:10px; text-align:center; }

    /* Responsive */
    @media (max-width:640px){
      .container{padding:12px}
      .sensor-rotate{width:32px}
    }
  </style>
</head>
<body>
  <div class="container" role="main">
    <img class="header-img fade-in" src="https://capsule-render.vercel.app/api?type=waving&height=250&section=header&color=0:FFFFFF,100:ADD8E6&text=Hello,%20I'm%20Sachira&fontColor=000000&fontSize=50&animation=twinkling&stroke=000000&strokeWidth=1" alt="Header" />

    <h2 style="text-align:center;margin:6px 0 4px;">💡 Undergraduate Student | IoT & Embedded Systems Enthusiast</h2>
    <div style="text-align:center;margin-bottom:12px">
      <span class="led-blink" title="LED"></span>
      <img class="sensor-rotate" src="https://skillicons.dev/icons?i=arduino" alt="Sensor" />
      <span class="data-pulse" title="Data pulse"></span>
      <span class="signal-wave" title="Signal wave"></span>
    </div>

    <div style="text-align:center" class="slide-in">
      <img src="https://readme-typing-svg.herokuapp.com?font=Poppins&size=22&duration=3000&pause=1000&color=000000&background=FFFFFF00&center=true&vCenter=true&width=800&height=50&lines=Crop+Recommendation+System+Developer;Real-time+IoT+Sensor+Integration;Building+Sustainable+Farming+Solutions" alt="typing" />
    </div>

    <div class="datetime" id="datetime">Last updated: —</div>

    <hr style="margin:18px 0"/>

    <!-- rest of README content can go here (GitHub README will still show this text) -->
    <p><strong>Currently building:</strong> Crop Recommendation System, IoT Sensor Integration, Microservices.</p>
    <p style="font-size:13px;color:#333">To display this animated page on GitHub, enable <strong>GitHub Pages</strong> for the repo and point to this file.</p>
  </div>

  <script>
    function updateDateTime(){
      const now = new Date();
      // Set the date/time you want — your earlier code hard-set it for demo:
      // now.setHours(20,8,0,0);
      const options = { weekday:'long', year:'numeric', month:'long', day:'numeric',
                        hour:'2-digit', minute:'2-digit', timeZone:'Asia/Colombo', timeZoneName:'short' };
      document.getElementById('datetime').innerText = 'Last Updated: ' + now.toLocaleString('en-US', options);
    }
    updateDateTime();
    setInterval(updateDateTime, 60_000);
  </script>
</body>
</html>
