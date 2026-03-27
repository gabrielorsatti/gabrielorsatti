<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=80&duration=800&pause=2000&color=FF006E&center=true&vCenter=true&width=500&height=120&lines=6️⃣7️⃣" alt="67" />

<!-- ANIMATION SVG 67 avec les mains -->
<img src="https://svg-banners.vercel.app/api?type=glitch&text1=gabrielorsatti&width=800&height=100" alt="" />

<svg width="700" height="420" viewBox="0 0 700 420" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Fond dégradé animé -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0d0d0d">
        <animate attributeName="stop-color" values="#0d0d0d;#1a0033;#001a33;#0d0d0d" dur="4s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" style="stop-color:#1a0033">
        <animate attributeName="stop-color" values="#1a0033;#0d0d0d;#330011;#1a0033" dur="4s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <!-- Couleurs flash -->
    <filter id="neon">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="glow">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <!-- Fond -->
  <rect width="700" height="420" fill="url(#bgGrad)" rx="24"/>

  <!-- Étoiles / confettis en fond -->
  <circle cx="60" cy="40" r="3" fill="#FF006E" opacity="0.8">
    <animate attributeName="cy" values="40;380;40" dur="3.1s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0;0.8" dur="3.1s" repeatCount="indefinite"/>
  </circle>
  <circle cx="150" cy="80" r="4" fill="#FFBE0B" opacity="0.9">
    <animate attributeName="cy" values="80;10;80" dur="2.4s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="150;180;150" dur="2.4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="60" r="3" fill="#8338EC" opacity="0.7">
    <animate attributeName="cy" values="60;350;60" dur="2.8s" repeatCount="indefinite"/>
  </circle>
  <circle cx="500" cy="30" r="5" fill="#06D6A0" opacity="0.8">
    <animate attributeName="cy" values="30;390;30" dur="3.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.8;0;0.8" dur="3.5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="350" cy="15" r="4" fill="#FF006E" opacity="0.6">
    <animate attributeName="cy" values="15;400;15" dur="2.2s" repeatCount="indefinite"/>
    <animate attributeName="cx" values="350;320;350" dur="2.2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="80" cy="200" r="3" fill="#FFBE0B" opacity="0.7">
    <animate attributeName="cx" values="80;650;80" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="620" cy="300" r="4" fill="#FB5607" opacity="0.8">
    <animate attributeName="cx" values="620;50;620" dur="4.2s" repeatCount="indefinite"/>
  </circle>

  <!-- ===== PERSONNAGE GAUCHE - fait le "6" avec son corps ===== -->
  <!-- Tête -->
  <g filter="url(#neon)">
    <circle cx="155" cy="80" r="38" fill="#FFD93D" stroke="#FF006E" stroke-width="4"/>
    <!-- Yeux qui bougent -->
    <circle cx="142" cy="73" r="7" fill="#0d0d0d"/>
    <circle cx="168" cy="73" r="7" fill="#0d0d0d"/>
    <circle cx="144" cy="71" r="3" fill="white">
      <animate attributeName="cx" values="144;146;144" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="170" cy="71" r="3" fill="white">
      <animate attributeName="cx" values="170;172;170" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <!-- Sourire -->
    <path d="M138 92 Q155 108 172 92" stroke="#0d0d0d" stroke-width="3" fill="none" stroke-linecap="round"/>
    <!-- Joues roses -->
    <circle cx="130" cy="88" r="8" fill="#FF6B9D" opacity="0.5"/>
    <circle cx="180" cy="88" r="8" fill="#FF6B9D" opacity="0.5"/>
    <!-- Cheveux -->
    <path d="M117 72 Q120 40 155 38 Q190 40 193 72" fill="#1a1a1a" stroke="none"/>
    <path d="M117 72 Q112 55 120 45" stroke="#1a1a1a" stroke-width="8" fill="none" stroke-linecap="round"/>
  </g>

  <!-- Corps gauche -->
  <rect x="128" y="118" width="54" height="80" rx="10" fill="#8338EC" stroke="#FF006E" stroke-width="3">
    <animate attributeName="fill" values="#8338EC;#FF006E;#06D6A0;#FFBE0B;#8338EC" dur="2s" repeatCount="indefinite"/>
  </rect>

  <!-- Jambes gauche -->
  <rect x="128" y="192" width="22" height="70" rx="8" fill="#3A86FF" stroke="#FFBE0B" stroke-width="2">
    <animateTransform attributeName="transform" type="rotate" values="0 139 192;-8 139 192;0 139 192;8 139 192;0 139 192" dur="0.8s" repeatCount="indefinite"/>
  </rect>
  <rect x="158" y="192" width="22" height="70" rx="8" fill="#3A86FF" stroke="#FFBE0B" stroke-width="2">
    <animateTransform attributeName="transform" type="rotate" values="0 169 192;8 169 192;0 169 192;-8 169 192;0 169 192" dur="0.8s" repeatCount="indefinite"/>
  </rect>
  <!-- Chaussures -->
  <ellipse cx="139" cy="262" rx="18" ry="10" fill="#FF006E"/>
  <ellipse cx="169" cy="262" rx="18" ry="10" fill="#FF006E"/>

  <!-- BRAS GAUCHE - fait le 6 (index tendu, autres doigts fermés, pouce tendu) -->
  <!-- Bras droit du perso (fait le "6") -->
  <g>
    <!-- bras -->
    <rect x="182" y="122" width="16" height="55" rx="8" fill="#FFD93D" stroke="#FF006E" stroke-width="2" transform="rotate(35 190 150)"/>
    <!-- Main -->
    <circle cx="213" cy="168" r="18" fill="#FFD93D" stroke="#FF006E" stroke-width="2"/>
    <!-- Doigts pour le 6: index levé + pouce levé -->
    <!-- Pouce vers le haut -->
    <rect x="196" y="148" width="10" height="26" rx="5" fill="#FFD93D" stroke="#FF006E" stroke-width="1.5" transform="rotate(-20 201 161)"/>
    <!-- Index levé -->
    <rect x="212" y="140" width="10" height="30" rx="5" fill="#FFD93D" stroke="#FF006E" stroke-width="1.5"/>
    <!-- Autres doigts fermés -->
    <rect x="222" y="154" width="9" height="18" rx="4" fill="#FFD93D" stroke="#FF006E" stroke-width="1"/>
    <rect x="229" y="157" width="8" height="15" rx="4" fill="#FFD93D" stroke="#FF006E" stroke-width="1"/>

    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="0.4s" repeatCount="indefinite"/>
  </g>

  <!-- Bras gauche du perso -->
  <rect x="100" y="122" width="16" height="55" rx="8" fill="#FFD93D" stroke="#06D6A0" stroke-width="2" transform="rotate(-25 108 150)">
    <animateTransform attributeName="transform" type="rotate" values="-25 108 150;-35 108 150;-25 108 150" dur="0.6s" repeatCount="indefinite" additive="sum"/>
  </rect>

  <!-- ===== TEXTE "67" au centre ===== -->
  <g filter="url(#glow)">
    <text x="350" y="200" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="140" font-weight="900" fill="none" stroke="#FF006E" stroke-width="4">
      <animate attributeName="stroke" values="#FF006E;#FFBE0B;#06D6A0;#8338EC;#FB5607;#FF006E" dur="1s" repeatCount="indefinite"/>
      67
    </text>
    <text x="350" y="200" text-anchor="middle" font-family="'Arial Black', sans-serif" font-size="140" font-weight="900" fill="#FFBE0B" opacity="0.15">
      <animate attributeName="fill" values="#FFBE0B;#FF006E;#8338EC;#06D6A0;#FFBE0B" dur="1s" repeatCount="indefinite"/>
      67
    </text>
  </g>

  <!-- ===== PERSONNAGE DROIT - fait le "7" avec son corps ===== -->
  <!-- Tête -->
  <g filter="url(#neon)">
    <circle cx="545" cy="80" r="38" fill="#FFD93D" stroke="#06D6A0" stroke-width="4"/>
    <!-- Yeux -->
    <circle cx="532" cy="73" r="7" fill="#0d0d0d"/>
    <circle cx="558" cy="73" r="7" fill="#0d0d0d"/>
    <circle cx="534" cy="71" r="3" fill="white">
      <animate attributeName="cx" values="534;532;534" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="560" cy="71" r="3" fill="white">
      <animate attributeName="cx" values="560;558;560" dur="1.5s" repeatCount="indefinite"/>
    </circle>
    <!-- Sourire langue tirée (goofball) -->
    <path d="M528 92 Q545 108 562 92" stroke="#0d0d0d" stroke-width="3" fill="none" stroke-linecap="round"/>
    <ellipse cx="545" cy="103" rx="10" ry="7" fill="#FF6B9D"/>
    <!-- Joues -->
    <circle cx="520" cy="88" r="8" fill="#FF6B9D" opacity="0.5"/>
    <circle cx="570" cy="88" r="8" fill="#FF6B9D" opacity="0.5"/>
    <!-- Cheveux -->
    <path d="M507 72 Q510 40 545 38 Q580 40 583 72" fill="#1a1a1a"/>
    <path d="M583 72 Q588 55 580 45" stroke="#1a1a1a" stroke-width="8" fill="none" stroke-linecap="round"/>
    <!-- étoile dans les cheveux -->
    <text x="538" y="55" font-size="14" fill="#FFBE0B">★</text>
  </g>

  <!-- Corps droit -->
  <rect x="518" y="118" width="54" height="80" rx="10" fill="#06D6A0" stroke="#FFBE0B" stroke-width="3">
    <animate attributeName="fill" values="#06D6A0;#FFBE0B;#FF006E;#8338EC;#06D6A0" dur="2s" repeatCount="indefinite" begin="1s"/>
  </rect>

  <!-- Jambes droit -->
  <rect x="518" y="192" width="22" height="70" rx="8" fill="#FB5607" stroke="#06D6A0" stroke-width="2">
    <animateTransform attributeName="transform" type="rotate" values="0 529 192;8 529 192;0 529 192;-8 529 192;0 529 192" dur="0.8s" repeatCount="indefinite" begin="0.4s"/>
  </rect>
  <rect x="548" y="192" width="22" height="70" rx="8" fill="#FB5607" stroke="#06D6A0" stroke-width="2">
    <animateTransform attributeName="transform" type="rotate" values="0 559 192;-8 559 192;0 559 192;8 559 192;0 559 192" dur="0.8s" repeatCount="indefinite" begin="0.4s"/>
  </rect>
  <!-- Chaussures -->
  <ellipse cx="529" cy="262" rx="18" ry="10" fill="#8338EC"/>
  <ellipse cx="559" cy="262" rx="18" ry="10" fill="#8338EC"/>

  <!-- BRAS DROIT - fait le 7 (index levé, autres fermés) -->
  <!-- Bras gauche du perso (fait le "7" avec index tendu en diag) -->
  <g>
    <rect x="490" y="120" width="16" height="55" rx="8" fill="#FFD93D" stroke="#06D6A0" stroke-width="2" transform="rotate(-35 498 148)"/>
    <!-- Main -->
    <circle cx="467" cy="165" r="18" fill="#FFD93D" stroke="#06D6A0" stroke-width="2"/>
    <!-- Doigts pour le 7: index tendu en diagonal, pouce -->
    <!-- Index en diagonale haute-gauche -->
    <rect x="450" y="138" width="10" height="32" rx="5" fill="#FFD93D" stroke="#06D6A0" stroke-width="1.5" transform="rotate(-25 455 154)"/>
    <!-- Autres doigts fermés -->
    <rect x="455" y="162" width="9" height="18" rx="4" fill="#FFD93D" stroke="#06D6A0" stroke-width="1"/>
    <rect x="447" y="165" width="8" height="15" rx="4" fill="#FFD93D" stroke="#06D6A0" stroke-width="1"/>
    <rect x="439" y="167" width="8" height="13" rx="4" fill="#FFD93D" stroke="#06D6A0" stroke-width="1"/>
    <!-- Pouce -->
    <rect x="466" y="159" width="10" height="20" rx="5" fill="#FFD93D" stroke="#06D6A0" stroke-width="1.5" transform="rotate(30 471 169)"/>

    <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="0.4s" repeatCount="indefinite" begin="0.2s"/>
  </g>

  <!-- Bras droit du perso droit -->
  <rect x="584" y="122" width="16" height="55" rx="8" fill="#FFD93D" stroke="#FFBE0B" stroke-width="2" transform="rotate(25 592 150)">
    <animateTransform attributeName="transform" type="rotate" values="25 592 150;35 592 150;25 592 150" dur="0.6s" repeatCount="indefinite" additive="sum"/>
  </rect>

  <!-- Onomatopées / texte déco -->
  <text x="80" y="370" font-family="'Arial Black', sans-serif" font-size="18" font-weight="900" fill="#FF006E" filter="url(#neon)">
    🔥 GOOFY AH 🔥
    <animate attributeName="fill" values="#FF006E;#FFBE0B;#06D6A0;#FF006E" dur="0.7s" repeatCount="indefinite"/>
  </text>

  <text x="440" y="370" font-family="'Arial Black', sans-serif" font-size="18" font-weight="900" fill="#06D6A0" filter="url(#neon)">
    ✨ BASED ✨
    <animate attributeName="fill" values="#06D6A0;#8338EC;#FFBE0B;#06D6A0" dur="0.7s" repeatCount="indefinite" begin="0.35s"/>
  </text>

  <!-- Éclairs déco -->
  <text x="290" y="360" font-size="28" fill="#FFBE0B" filter="url(#neon)">
    ⚡
    <animateTransform attributeName="transform" type="rotate" values="0 304 345;15 304 345;-15 304 345;0 304 345" dur="0.5s" repeatCount="indefinite"/>
  </text>
  <text x="360" y="365" font-size="22" fill="#FF006E">
    💜
    <animateTransform attributeName="transform" type="scale" values="1 1;1.3 1.3;1 1" dur="0.6s" repeatCount="indefinite"/>
  </text>

  <!-- Arcs-en-ciel déco coins -->
  <text x="10" y="30" font-size="28">🌈</text>
  <text x="645" y="30" font-size="28">🌈</text>

  <!-- Stars -->
  <text x="30" y="300" font-size="20" fill="#FFBE0B" filter="url(#neon)">
    ★
    <animate attributeName="opacity" values="1;0;1" dur="0.6s" repeatCount="indefinite"/>
  </text>
  <text x="650" y="300" font-size="20" fill="#FF006E" filter="url(#neon)">
    ★
    <animate attributeName="opacity" values="0;1;0" dur="0.6s" repeatCount="indefinite"/>
  </text>

</svg>

---

<img src="https://readme-typing-svg.demolab.com?font=Black+Ops+One&size=28&duration=1200&pause=500&color=FFBE0B&center=true&vCenter=true&multiline=true&width=600&height=60&lines=gabriel+orsatti+%F0%9F%94%A5+six+seven+%E2%9C%8C%EF%B8%8F" alt="gabriel orsatti" />

<img src="https://readme-typing-svg.demolab.com?font=Permanent+Marker&size=20&duration=2000&pause=1000&color=06D6A0&center=true&vCenter=true&multiline=true&width=700&height=100&lines=Welcome+to+my+profile+%F0%9F%91%8B;Drop+a+%E2%AD%90+if+u+fw+the+vibe;67+no+cap+%F0%9F%94%A5%F0%9F%94%A5%F0%9F%94%A5" alt="Typing SVG" />

---

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,react,nodejs,python,git&perline=6" />
</p>

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=gabrielorsatti&show_icons=true&theme=radical&hide_border=true&bg_color=0d0d0d&title_color=FF006E&icon_color=FFBE0B&text_color=ffffff" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=gabrielorsatti&theme=radical&hide_border=true&background=0d0d0d&ring=FF006E&fire=FFBE0B&currStreakLabel=06D6A0" />
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=gabrielorsatti&color=FF006E&style=for-the-badge&label=PROFILE+VIEWS" />
</p>

</div>
