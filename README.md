<!-- 
    README for GitHub Profile 
    Theme: Dark / Space / Purple / Blue 
    Features: Blinking stars bar (top), Donut chart stats, Blue-purple waves (bottom)
-->

<!-- TOP BAR: Blinking Stars -->
<div style="position: relative; width: 100%; height: 80px; overflow: hidden; margin-bottom: -5px;">
  <svg width="100%" height="80" preserveAspectRatio="none" style="display: block;">
    <!-- Dark background -->
    <rect width="100%" height="80" fill="#1b1b2f" />

    <!-- A few blinking stars (circles) -->
    <circle cx="50"  cy="40" r="2" fill="#fff">
      <animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite" begin="0s"/>
    </circle>
    <circle cx="150" cy="20" r="1.5" fill="#fff">
      <animate attributeName="opacity" values="0;1;0" dur="2s" repeatCount="indefinite" begin="0.5s"/>
    </circle>
    <circle cx="250" cy="60" r="2.5" fill="#fff">
      <animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite" begin="1s"/>
    </circle>
    <circle cx="350" cy="30" r="2" fill="#fff">
      <animate attributeName="opacity" values="0;1;0" dur="3s" repeatCount="indefinite" begin="1.5s"/>
    </circle>
    <circle cx="450" cy="50" r="1.8" fill="#fff">
      <animate attributeName="opacity" values="0;1;0" dur="2.8s" repeatCount="indefinite" begin="0.7s"/>
    </circle>
    <circle cx="550" cy="25" r="2" fill="#fff">
      <animate attributeName="opacity" values="0;1;0" dur="3.2s" repeatCount="indefinite" begin="0.2s"/>
    </circle>
    <circle cx="650" cy="45" r="2" fill="#fff">
      <animate attributeName="opacity" values="0;1;0" dur="2.5s" repeatCount="indefinite" begin="1.2s"/>
    </circle>
  </svg>
</div>

<!-- MAIN CONTENT -->
<div style="background: #1b1b2f; color: #fff; padding: 1rem; text-align: center;">
  <h1 style="margin: 0.5rem 0; font-size: 2.2rem;">itsnot</h1>
  <h2 style="margin: 0.2rem 0; font-weight: normal; color: #6a0dad;">Protostarship</h2>
  <p style="margin: 0.5rem 0 1rem; font-style: italic;">idk, randomly doing things :D</p>
  <p style="margin-bottom: 1.5rem;">1 follower • 1 following</p>

  <!-- ABOUT / BIO -->
  <div style="max-width: 600px; margin: 0 auto; text-align: left; background: rgba(255,255,255,0.05); padding: 1rem; border-radius: 8px;">
    <h3>About Me</h3>
    <p>
      Hello there! I'm <strong>itsnot</strong>, a curious explorer who loves dabbling in code, 
      art, and random experiments. I call myself a “Protostarship” traveler—forever on a journey, 
      never fully formed, and always seeking the next cosmic idea. 
    </p>
    <p>
      I enjoy building tiny prototypes, discovering new languages and frameworks, 
      and occasionally conjuring up creative chaos. 
    </p>
  </div>

  <!-- Donut Chart Stats (static example) -->
  <div style="margin-top: 2rem; margin-bottom: 2rem; display: flex; justify-content: center; align-items: center;">
    <svg width="200" height="200" viewBox="0 0 42 42">
      <!-- Background ring -->
      <circle 
        cx="21" cy="21" r="15.91549430918954"
        fill="transparent"
        stroke="#2f2f2f"
        stroke-width="3"
      ></circle>

      <!-- Segment 1 -->
      <circle 
        cx="21" cy="21" r="15.91549430918954"
        fill="transparent"
        stroke="#6a0dad"
        stroke-width="3"
        stroke-dasharray="30 70"
        stroke-dashoffset="25"
      >
        <!-- Animate from full circle to final offset -->
        <animate attributeName="stroke-dashoffset" from="100" to="25" dur="2s" fill="freeze" />
      </circle>

      <!-- Segment 2 -->
      <circle 
        cx="21" cy="21" r="15.91549430918954"
        fill="transparent"
        stroke="#00bfff"
        stroke-width="3"
        stroke-dasharray="40 60"
        stroke-dashoffset="55"
      >
        <animate attributeName="stroke-dashoffset" from="100" to="55" dur="2s" fill="freeze" begin="0.5s"/>
      </circle>

      <!-- Center text -->
      <text x="50%" y="50%" text-anchor="middle" fill="#fff" dy=".3em" font-size="5">Live Stats</text>
    </svg>
  </div>
</div>

<!-- BOTTOM BAR: Blue-Purple Waves -->
<div style="margin-top: -5px;">
  <svg viewBox="0 0 1440 320" style="display: block; width: 100%; height: auto;">
    <defs>
      <linearGradient id="waveGradient" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#6a0dad" />
        <stop offset="100%" stop-color="#00bfff" />
      </linearGradient>
    </defs>
    <path 
      fill="url(#waveGradient)" 
      fill-opacity="1" 
      d="M0,64L48,96C96,128,192,192,288,224C384,256,480,256,576,213.3C672,171,768,85,864,53.3C960,21,1056,43,1152,69.3C1248,96,1344,128,1392,144L1440,160L1440,320L1392,320C1344,320,1248,320,1152,320C1056,320,960,320,864,320C768,320,672,320,576,320C480,320,384,320,288,320C192,320,96,320,48,320L0,320Z"
    ></path>
  </svg>
</div>
