# GitHub README Banner (Black + Purple UI/UX Theme)

Save the following code as **`banner.svg`** in your GitHub profile repository.

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="1280" height="360" viewBox="0 0 1280 360">

  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#08080B"/>
      <stop offset="50%" stop-color="#111827"/>
      <stop offset="100%" stop-color="#6D28D9"/>
    </linearGradient>

    <linearGradient id="purple" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#A855F7"/>
      <stop offset="100%" stop-color="#7C3AED"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="8" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="1280" height="360" fill="url(#bg)"/>

  <circle cx="1110" cy="70" r="150" fill="#8B5CF6" opacity="0.08"/>
  <circle cx="1180" cy="300" r="190" fill="#A855F7" opacity="0.05"/>

  <!-- UI / UX Logo -->
  <g transform="translate(80,85)" filter="url(#glow)">
      <polygon
          points="90,0 180,50 180,150 90,200 0,150 0,50"
          fill="none"
          stroke="url(#purple)"
          stroke-width="6"/>

      <path
        d="M55 55
           Q90 25 125 55
           Q90 85 55 115
           Q90 145 125 115"
        fill="none"
        stroke="#A855F7"
        stroke-width="6"
        stroke-linecap="round"/>

      <circle cx="90" cy="85" r="6" fill="#FFFFFF"/>
  </g>

  <!-- Name -->
  <text
      x="320"
      y="120"
      font-size="56"
      font-family="Segoe UI, Arial"
      fill="white"
      font-weight="700">
      SARAVANAKUMAR
  </text>

  <!-- Title -->
  <text
      x="320"
      y="165"
      font-size="24"
      font-family="Segoe UI"
      fill="#C4B5FD">
      UI / UX DESIGNER
  </text>

  <!-- Subtitle -->
  <text
      x="320"
      y="205"
      font-size="18"
      font-family="Segoe UI"
      fill="#D1D5DB">
      User Research • Wireframing • Prototyping • Design Systems
  </text>

  <!-- Divider -->
  <line
      x1="320"
      y1="230"
      x2="780"
      y2="230"
      stroke="#8B5CF6"
      stroke-width="3"/>

  <!-- Feature Cards -->
  <g transform="translate(930,70)">
      <rect width="240" height="60" rx="14"
            fill="#15151F"
            stroke="#7C3AED"/>

      <text
          x="25"
          y="38"
          font-size="18"
          fill="white"
          font-family="Segoe UI">
          FIGMA
      </text>

      <rect y="85" width="240" height="60" rx="14"
            fill="#15151F"
            stroke="#7C3AED"/>

      <text
          x="25"
          y="123"
          font-size="18"
          fill="white"
          font-family="Segoe UI">
          CANVA
      </text>

      <rect y="170" width="240" height="60" rx="14"
            fill="#15151F"
            stroke="#7C3AED"/>

      <text
          x="25"
          y="208"
          font-size="18"
          fill="white"
          font-family="Segoe UI">
          USER EXPERIENCE
      </text>
  </g>

</svg>
```

## README.md

```md
<p align="center">
  <img src="./banner.svg" width="100%" alt="Saravanakumar UI UX Banner">
</p>
```

**Recommended GitHub theme**

* Background: `#08080B`
* Primary Purple: `#7C3AED`
* Accent Purple: `#A855F7`
* Text: `#FFFFFF`
* Secondary Text: `#D1D5DB`
