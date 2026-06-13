## 🐍 Live Commit Flow

<svg width="100%" height="120" viewBox="0 0 620 120" xmlns="http://www.w3.org/2000/svg">

  <!-- Outer glow background -->
  <rect x="10" y="25" width="600" height="60" rx="14"
        fill="#0b1220" stroke="#00ffd5" stroke-width="2"/>

  <!-- Commit text -->
  <text x="30" y="60" fill="#ffffff" font-size="14" font-family="monospace">
    git commit -m "building scalable systems"
  </text>

  <!-- Snake path (slightly inset so it doesn't clip) -->
  <path id="snakePath"
        d="M 20 30 H 600 V 80 H 20 Z"
        fill="none"/>

  <!-- Glow snake trail layer -->
  <circle r="6" fill="#00ffd5">
    <animateMotion
      dur="3.2s"
      repeatCount="indefinite"
      rotate="auto">
      <mpath href="#snakePath"/>
    </animateMotion>
  </circle>

  <!-- Middle trail -->
  <circle r="4" fill="#00ffd5" opacity="0.6">
    <animateMotion
      dur="3.2s"
      begin="0.12s"
      repeatCount="indefinite"
      rotate="auto">
      <mpath href="#snakePath"/>
    </animateMotion>
  </circle>

  <!-- Tail trail -->
  <circle r="2.8" fill="#00ffd5" opacity="0.35">
    <animateMotion
      dur="3.2s"
      begin="0.24s"
      repeatCount="indefinite"
      rotate="auto">
      <mpath href="#snakePath"/>
    </animateMotion>
  </circle>

  <!-- Subtle border glow animation -->
  <rect x="10" y="25" width="600" height="60" rx="14"
        fill="none" stroke="url(#grad)" stroke-width="2"/>

  <defs>
    <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00ffd5">
        <animate attributeName="stop-color"
                 values="#00ffd5;#0066ff;#00ffd5"
                 dur="4s"
                 repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#0066ff">
        <animate attributeName="stop-color"
                 values="#0066ff;#00ffd5;#0066ff"
                 dur="4s"
                 repeatCount="indefinite"/>
      </stop>
    </linearGradient>
  </defs>

</svg>
