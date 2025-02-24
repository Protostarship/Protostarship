# itsnot – Protostarship

<!-- 
  Markdown that references external SVG files: stars.svg and waves.svg
  Place stars.svg, waves.svg, and this README.md in the same directory.
  Note: GitHub may not allow <use> references in README preview.
-->

<!-- TOP BAR: Blinking Stars (references stars.svg) -->
<svg width="100%" height="80" preserveAspectRatio="none">
  <use xlink:href="./src/stars.svg#stars" />
</svg>

<div align="center" style="background: #1b1b2f; color: #fff; padding: 1rem; font-family: sans-serif;">
  <h1 style="margin: 0.5rem 0;">itsnot</h1>
  <h2 style="margin: 0.2rem 0; color: #6a0dad;">Protostarship</h2>
  <p><em>idk, randomly doing things :D</em></p>
  <p>1 follower • 1 following</p>

  <div style="max-width: 600px; margin: 1rem auto; background: rgba(255,255,255,0.05); padding: 1rem; border-radius: 8px; text-align: left;">
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

  <!-- Donut Chart (static example) -->
  <div style="margin: 2rem 0;">
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
      <text x="50%" y="50%" text-anchor="middle" fill="#fff" dy=".3em" font-size="5">
        Live Stats
      </text>
    </svg>
  </div>
</div>

<!-- BOTTOM BAR: Blue-Purple Waves (references waves.svg) -->
<svg width="100%" height="auto" preserveAspectRatio="none">
  <use xlink:href="./src/waves.svg#waves" />
</svg>

