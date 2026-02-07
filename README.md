<p align="center">
  <svg width="500" height="100" viewBox="0 0 500 100" xmlns="http://www.w3.org/2000/svg">
    <style>
      .text {
        font-family: 'Kaiti', 'STKaiti', serif;
        font-size: 60px;
        font-weight: bold;
        fill: none;
        stroke: #333; /* 初始颜色 */
        stroke-width: 2;
        stroke-dasharray: 500;
        stroke-dashoffset: 500;
        animation: draw 3s ease-in-out forwards, glow 2s infinite 3s;
      }

      @keyframes draw {
        to { stroke-dashoffset: 0; }
      }

      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 2px #ff4500); stroke: #ff4500; }
        50% { filter: drop-shadow(0 0 15px #ff0000); stroke: #ffd700; }
      }
    </style>
    <text x="50%" y="70%" text-anchor="middle" class="text">一剑开天门</text>
  </svg>
</p>
