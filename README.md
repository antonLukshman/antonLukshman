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
    
    .wave-hand {
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
  
  <!-- First text: "Hi there" with waving hand emoji (using a path for reliability) -->
  <g class="wave-hand" style="animation: fadeIn 0.3s ease-out forwards, wave 1.5s 3s infinite; animation-delay: 0.1s;">
    <path d="M220,65 c1.71,0.22 2.78,0.51 3.25,1.45 c1.44,2.16 2.89,4.33 4.33,6.49 c0.33,0.5 0.94,0.88 1.42,0.89 c0.5,0.01 1.12,-0.37 1.47,-0.77 c0.31,-0.36 0.36,-0.99 0.36,-1.51 c-0.01,-4.97 -0.04,-9.93 -0.06,-14.9 c0,-1.32 0.63,-1.99 1.61,-1.99 c0.98,0 1.55,0.67 1.55,1.99 c0,3.16 0.04,6.33 0.04,9.49 c0,0.34 0,0.67 0,1.14 c0.53,-0.24 0.91,-0.34 1.2,-0.55 c0.37,-0.27 0.76,-0.6 0.95,-0.99 c1.75,-3.6 3.46,-7.23 5.16,-10.85 c0.23,-0.49 0.39,-1.03 0.68,-1.46 c0.86,-1.3 2.68,-0.99 3.04,0.51 c0.15,0.62 -0.05,1.42 -0.31,2.02 c-1.44,3.21 -2.94,6.4 -4.42,9.59 c-0.11,0.23 -0.21,0.46 -0.39,0.84 c0.57,0.15 1.12,0.22 1.61,0.45 c0.38,0.18 0.79,0.56 0.93,0.95 c0.74,2.07 1.38,4.18 2.05,6.28 c0.35,1.07 -0.15,1.93 -1.11,2.18 c-0.96,0.25 -1.8,-0.22 -2.17,-1.3 c-0.46,-1.33 -0.91,-2.66 -1.27,-4.01 c-0.18,-0.66 -0.54,-0.92 -1.21,-0.89 c-0.54,0.02 -1.09,0.01 -1.72,0.01 c0,1.76 0.02,3.44 -0.01,5.12 c-0.01,0.64 -0.06,1.31 -0.25,1.91 c-0.26,0.83 -0.95,1.13 -1.75,0.74 c-0.5,-0.24 -0.94,-0.89 -1.1,-1.45 c-0.25,-0.88 -0.23,-1.85 -0.25,-2.78 c-0.04,-1.16 -0.01,-2.33 -0.01,-3.56 c-0.35,0 -0.67,0 -0.99,0 c-0.65,0 -1.3,0.01 -1.95,-0.03 c-0.4,-0.02 -0.86,-0.06 -1.18,-0.26 c-0.41,-0.25 -0.78,-0.63 -0.99,-1.04 c-0.8,-1.51 -1.55,-3.06 -2.21,-4.63 c-0.39,-0.93 -0.07,-1.79 0.85,-2.09 c0.93,-0.3 1.7,0.15 2.12,1.13 c0.38,0.89 0.79,1.78 1.16,2.67 c0.13,0.31 0.27,0.44 0.63,0.42 c0.45,-0.02 0.91,0 1.46,0 c0,-2.61 0.01,-5.15 -0.01,-7.7 c0,-0.63 -0.12,-1.26 -0.28,-1.87 c-0.22,-0.86 0.03,-1.56 0.77,-1.85 c0.83,-0.32 1.61,0.06 1.96,0.99 c0.11,0.29 0.11,0.62 0.11,0.94 c0.01,3.33 0.01,6.66 0.02,9.99 c0,0.4 0.07,0.56 0.52,0.53 c0.52,-0.03 1.05,-0.01 1.63,-0.01 c0,-4.07 0.01,-8.08 -0.01,-12.1 c0,-0.65 -0.06,-1.31 -0.2
