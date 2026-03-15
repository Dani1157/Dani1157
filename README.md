# 👋 Hey, I'm Dani!

<div align="center">

## ✨ Design Engineer • Creative Developer • AI Explorer ✨

<br>

<!-- STATS BADGES -->
![GitHub followers](https://img.shields.io/github/followers/Dani1157?style=for-the-badge&logo=github&color=6c5ce7)
![GitHub stars](https://img.shields.io/github/stars/Dani1157?style=for-the-badge&logo=github&color=ffb86c)
![Profile views](https://img.shields.io/badge/Views-1000+-brightgreen?style=for-the-badge&logo=eye&logoColor=white)
![Age](https://img.shields.io/badge/Age-21-blue?style=for-the-badge&logo=birthday&logoColor=white)

<br>

<!-- TECH STACK BADGES -->
### 🛠️ Tech Stack

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

<br>

<!-- AI TOOLS BADGES -->
### 🤖 AI Tools I Use

![Cursor](https://img.shields.io/badge/Cursor-000000?style=for-the-badge&logo=cursor&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-8B5CF6?style=for-the-badge&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Firefly](https://img.shields.io/badge/Firefly-FF6B6B?style=for-the-badge&logo=adobe&logoColor=white)
![Copilot](https://img.shields.io/badge/Copilot-6A1B9A?style=for-the-badge&logo=github&logoColor=white)
![Midjourney](https://img.shields.io/badge/Midjourney-000000?style=for-the-badge&logo=midjourney&logoColor=white)

<br>

<!-- GITHUB STATS CARDS -->
### 📊 GitHub Stats

![Dani's GitHub stats](https://github-readme-stats.vercel.app/api?username=Dani1157&show_icons=true&theme=tokyonight&hide_border=true&count_private=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Dani1157&layout=compact&theme=tokyonight&hide_border=true)

[![GitHub Streak](https://streak-stats.demolab.com?user=Dani1157&theme=tokyonight&hide_border=true)](https://git.io/streak-stats)

<br>

<!-- FEATURED PROJECTS -->
### 🚀 Featured Projects

[![Drimify Demo](https://github-readme-stats.vercel.app/api/pin/?username=Dani1157&repo=drimify-case-study&theme=tokyonight&hide_border=true)](https://github.com/Dani1157/drimify-case-study)
[![My Portfolio](https://github-readme-stats.vercel.app/api/pin/?username=Dani1157&repo=my-portfolio&theme=tokyonight&hide_border=true)](https://github.com/Dani1157/my-portfolio)
[![Vinyl Desk](https://github-readme-stats.vercel.app/api/pin/?username=Dani1157&repo=Vinyl-Desk&theme=tokyonight&hide_border=true)](https://github.com/Dani1157/Vinyl-Desk)
[![NEXUS CSS](https://github-readme-stats.vercel.app/api/pin/?username=Dani1157&repo=-AI-Chat-Interface&theme=tokyonight&hide_border=true)](https://github.com/Dani1157/-AI-Chat-Interface)

<br>

<!-- CONNECT WITH ME -->
### 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dani-dudley-59776026b)
[![Portfolio Vercel](https://img.shields.io/badge/Portfolio%20(Vercel)-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://my-portfolio-one-gamma-92.vercel.app)
[![Portfolio GitHub](https://img.shields.io/badge/Portfolio%20(GitHub%20Pages)-222222?style=for-the-badge&logo=githubpages&logoColor=white)](https://dani1157.github.io/my-portfolio/)
[![Discord](https://img.shields.io/badge/Discord-dani0569.-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/users/dani0569.)
[![Email](https://img.shields.io/badge/Email-Dazai48@yahoo.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Dazai48@yahoo.com)

<br>
<br>

## 🎮 SPACE INVADERS MINI-GAME

Play right here in my profile! Use **A** (left) and **D** (right) to move, **SPACE** to shoot.

<div align="center">
  <canvas id="gameCanvas" width="500" height="300" style="border: 2px solid #8B5CF6; border-radius: 10px; background: #0a0c14;"></canvas>
</div>

<script>
  (function() {
    const canvas = document.getElementById('gameCanvas');
    if (!canvas) return;
    
    const ctx = canvas.getContext('2d');
    
    // Game variables
    let player = { x: 225, width: 50, height: 20 };
    let bullets = [];
    let enemies = [];
    let score = 0;
    let gameOver = false;
    let gameWin = false;
    let keys = {};
    
    // Create enemies
    for (let i = 0; i < 5; i++) {
      for (let j = 0; j < 3; j++) {
        enemies.push({
          x: 50 + i * 80,
          y: 30 + j * 30,
          width: 40,
          height: 20,
          alive: true
        });
      }
    }
    
    // Keyboard controls
    window.addEventListener('keydown', (e) => {
      if (e.key === 'a' || e.key === 'A') keys.left = true;
      if (e.key === 'd' || e.key === 'D') keys.right = true;
      if (e.key === ' ') {
        e.preventDefault();
        if (!gameOver && !gameWin) {
          bullets.push({
            x: player.x + player.width/2 - 2,
            y: 270,
            width: 4,
            height: 10
          });
        }
      }
      if (e.key === 'r' || e.key === 'R') resetGame();
    });
    
    window.addEventListener('keyup', (e) => {
      if (e.key === 'a' || e.key === 'A') keys.left = false;
      if (e.key === 'd' || e.key === 'D') keys.right = false;
    });
    
    function resetGame() {
      player.x = 225;
      bullets = [];
      enemies = [];
      score = 0;
      gameOver = false;
      gameWin = false;
      
      for (let i = 0; i < 5; i++) {
        for (let j = 0; j < 3; j++) {
          enemies.push({
            x: 50 + i * 80,
            y: 30 + j * 30,
            width: 40,
            height: 20,
            alive: true
          });
        }
      }
    }
    
    function update() {
      if (gameOver || gameWin) return;
      
      // Move player
      if (keys.left && player.x > 0) player.x -= 5;
      if (keys.right && player.x < 450) player.x += 5;
      
      // Move bullets
      bullets = bullets.filter(b => b.y > 0);
      bullets.forEach(b => b.y -= 5);
      
      // Check collisions
      bullets.forEach((bullet, bIndex) => {
        enemies.forEach((enemy, eIndex) => {
          if (enemy.alive &&
              bullet.x < enemy.x + enemy.width &&
              bullet.x + bullet.width > enemy.x &&
              bullet.y < enemy.y + enemy.height &&
              bullet.y + bullet.height > enemy.y) {
            enemy.alive = false;
            bullets.splice(bIndex, 1);
            score += 10;
          }
        });
      });
      
      // Check win condition
      if (enemies.every(e => !e.alive)) {
        gameWin = true;
      }
      
      // Check if enemies reached bottom
      enemies.forEach(enemy => {
        if (enemy.alive && enemy.y + enemy.height > 280) {
          gameOver = true;
        }
      });
    }
    
    function draw() {
      // Clear canvas
      ctx.fillStyle = '#0a0c14';
      ctx.fillRect(0, 0, 500, 300);
      
      // Draw player
      ctx.fillStyle = '#8B5CF6';
      ctx.fillRect(player.x, 280, player.width, 10);
      
      // Draw bullets
      ctx.fillStyle = '#00fff5';
      bullets.forEach(b => ctx.fillRect(b.x, b.y, b.width, b.height));
      
      // Draw enemies
      enemies.forEach(enemy => {
        if (enemy.alive) {
          ctx.fillStyle = '#ff6b6b';
          ctx.fillRect(enemy.x, enemy.y, enemy.width, enemy.height);
        }
      });
      
      // Draw score
      ctx.fillStyle = '#fff';
      ctx.font = '16px monospace';
      ctx.fillText(`Score: ${score}`, 10, 20);
      
      // Draw game over / win
      if (gameOver) {
        ctx.fillStyle = '#ff6b6b';
        ctx.font = '24px monospace';
        ctx.fillText('GAME OVER', 150, 150);
        ctx.font = '12px monospace';
        ctx.fillText('Press R to restart', 170, 180);
      }
      
      if (gameWin) {
        ctx.fillStyle = '#00fff5';
        ctx.font = '24px monospace';
        ctx.fillText('YOU WIN! 🎉', 150, 150);
        ctx.font = '12px monospace';
        ctx.fillText('Press R to play again', 170, 180);
      }
    }
    
    function gameLoop() {
      update();
      draw();
      requestAnimationFrame(gameLoop);
    }
    
    gameLoop();
  })();
</script>

<div align="center">
  <p><kbd>A</kbd> Move Left • <kbd>D</kbd> Move Right • <kbd>SPACE</kbd> Shoot • <kbd>R</kbd> Restart</p>
  <p>⭐ Score: <span id="scoreDisplay">0</span> • Defeat all enemies to win!</p>
</div>

<br>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=100&section=footer)

</div>
