<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<title>우리의 크리스마스 🎄</title>

<style>
body {
  margin: 0;
  font-family: 'Apple SD Gothic Neo', sans-serif;
  background: linear-gradient(to bottom, #0b1d3a, #1e3c72);
  color: #333;
  overflow-x: hidden;
}

/* 눈 내리기 */
.snow {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  pointer-events: none;
  z-index: 1;
}

/* 배경 크리스마스 아이콘 */
.bg-icon {
  position: fixed;
  z-index: 2;
  opacity: 0.85;
}

.tree {
  bottom: 0;
  left: 30px;
  width: 180px;
}

.santa {
  top: 40px;
  right: 30px;
  width: 160px;
}

.rudolph {
  bottom: 40px;
  right: 40px;
  width: 150px;
}

/* 메인 컨텐츠 */
header {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
  color: #fff;
  z-index: 3;
  position: relative;
}

header h1 {
  font-size: 3rem;
}

header p {
  opacity: 0.9;
}

/* 카드 형식 */
section {
  max-width: 800px;
  margin: 0 auto;
  padding: 100px 20px;
  position: relative;
  z-index: 3;
}

.memory, .letter {
  background: #fff;
  border-radius: 25px;
  padding: 50px;
  margin-bottom: 120px;
  box-shadow: 0 15px 40px rgba(0,0,0,0.2);
  text-align: center;
}

.memory img {
  width: 100%;
  border-radius: 20px;
  margin-bottom: 25px;
}

.memory h2 {
  margin-bottom: 15px;
}

.letter h2 {
  margin-bottom: 30px;
}

footer {
  text-align: center;
  color: #ffffff;
  padding: 60px;
  opacity: 0.7;
  z-index: 3;
  position: relative;
}
</style>
</head>

<body>

<!-- 눈 -->
<canvas class="snow"></canvas>

<!-- 배경 크리스마스 아이콘 -->

<header>
  <h1>우리의 크리스마스 🎄</h1>
  <p>스크롤하면서 우리의 이야기를 꺼내볼게</p>
</header>

<section>
  <div class="memory">
    <img src="images/memory1.jpg">
    <h2>서민금융 진흥원에서 시작한 우리의 만남</h2>
    <p>모든 시작은 여기서 부터였어</p>
  </div>

  <div class="memory">
    <img src="images/memory2.jpg">
    <h2>처음 여행</h2>
    <p>너랑 떠난 그 길이 아직도 선명해.</p>
  </div>

  <div class="memory">
    <img src="images/memory3.jpg">
    <h2>같이 러닝 뛰던 날</h2>
    <p>네 웃음이 아직도 기억나.</p>
  </div>

  <div class="memory">
    <img src="images/memory4.jpg">
    <h2>청계천 데이트</h2>
    <p>이때 더 많이 사랑하게 됐어.</p>
  </div>

  <div class="memory">
    <img src="images/memory6.jpg">
    <h2>지금도 계속되는 우리</h2>
    <p>앞으로의 이야기가 더 기대돼.</p>
  </div>

  <div class="letter">
    <h2>To. 너에게 🎅💌</h2>
    <p>
      이 페이지를 만들면서<br>
      우리가 얼마나 많은 순간을 함께했는지 다시 느꼈어.<br><br>
      크리스마스의 기적이 있다면<br>
      그건 바로 너를 만난 거야.<br><br>
      메리 크리스마스 🎄<br>
      그리고 언제나 사랑해.
    </p>
  </div>
</section>

<footer style="font-size:12px; opacity:0.7;">
  Music by <a href="https://pixabay.com/users/sigmamusicart-36860929/?utm_source=link-attribution&utm_medium=referral&utm_campaign=music&utm_content=434436" style="color:white;">
    Mikhail Smusev
  </a> from 
  <a href="https://pixabay.com/" style="color:white;">
    Pixabay
  </a>
</footer>

<!-- 배경음악 -->
<audio id="bgm" loop>
  <source src="music/christmas-434436.mp3" type="audio/mpeg">
</audio>

<script>
// 배경음악 자동 재생 + 볼륨 설정
const bgm = document.getElementById('bgm');
bgm.volume = 0.3; // 0~1 사이, 0.3 = 30%

window.addEventListener('load', () => {
  const playPromise = bgm.play();
  if (playPromise !== undefined) {
    playPromise.catch(() => {
      // 모바일/브라우저 자동 재생 정책 대비
      window.addEventListener('scroll', () => {
        bgm.play();
      }, { once: true });
    });
  }
});
</script>

<!-- 눈 내리는 JS -->
<script>
const canvas = document.querySelector('.snow');
const ctx = canvas.getContext('2d');
canvas.width = window.innerWidth;
canvas.height = window.innerHeight;

let snowflakes = [];
for (let i = 0; i < 150; i++) {
  snowflakes.push({
    x: Math.random() * canvas.width,
    y: Math.random() * canvas.height,
    r: Math.random() * 4 + 1,
    d: Math.random() * 1
  });
}

function drawSnow() {
  ctx.clearRect(0, 0, canvas.width, canvas.height);
  ctx.fillStyle = "rgba(255,255,255,0.8)";
  ctx.beginPath();
  for (let i = 0; i < snowflakes.length; i++) {
    let f = snowflakes[i];
    ctx.moveTo(f.x, f.y);
    ctx.arc(f.x, f.y, f.r, 0, Math.PI * 2, true);
  }
  ctx.fill();
  moveSnow();
}

function moveSnow() {
  for (let i = 0; i < snowflakes.length; i++) {
    let f = snowflakes[i];
    f.y += Math.pow(f.d, 2) + 1;
    if (f.y > canvas.height) {
      snowflakes[i] = {
        x: Math.random() * canvas.width,
        y: 0,
        r: f.r,
        d: f.d
      };
    }
  }
}

setInterval(drawSnow, 33);
</script>

</body>
</html>
