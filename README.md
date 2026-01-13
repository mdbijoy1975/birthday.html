# birthday.html
data:text/html;charset=utf-8,
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<title>শুভ জন্মদিন My happiness. My koliza</title>
<style>
body{
margin:0;
padding:0;
height:100vh;
overflow:hidden;
background:linear-gradient(135deg,#ff758c,#ff7eb3);
font-family:sans-serif;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
color:white;
}
.card{
background:rgba(255,255,255,0.15);
padding:30px;
border-radius:25px;
box-shadow:0 10px 30px rgba(0,0,0,.3);
animation:zoom 1.5s ease;
position:relative;
z-index:10;
}
@keyframes zoom{
from{transform:scale(0.7);opacity:0;}
to{transform:scale(1);opacity:1;}
}
h1{font-size:36px;margin-bottom:10px;}
p{font-size:18px;line-height:1.6;margin:10px 0;}
.heart{font-size:40px;animation:beat 1s infinite;}
@keyframes beat{
0%,100%{transform:scale(1);}
50%{transform:scale(1.3);}
}
.confetti{
position:absolute;
width:10px;
height:10px;
border-radius:50%;
animation:fall 4s linear infinite;
}
@keyframes fall{
to{transform:translateY(100vh) rotate(360deg);opacity:0;}
}
</style>
</head>
<body>

<div class="card">
<h1>🎂 শুভ জন্মদিন My happiness. My koliza 🎂</h1>
<p>
আমার জীবনের সবচেয়ে প্রিয় মানুষ তুমি ❤️<br>
তোমার হাসি আমার পৃথিবীকে আলোকিত করে ✨<br>
তুমি ছাড়া জীবন অসম্পূর্ণ 💖<br><br>
আজকের এই বিশেষ দিনে শুধু এটুকু বলি—<br>
<strong>আমি তোমাকে সারা জীবন ভালোবাসবো I love my jan 💕</strong>
</p>
<div class="heart">💓</div>
<p style="margin-top:15px;">— তোমার ভবিষ্যৎ স্বামী 😌</p>
</div>

<script>
// Confetti
function createConfetti(){
const c=document.createElement('div');
c.className='confetti';
c.style.left=Math.random()*100+'vw';
c.style.backgroundColor=`hsl(${Math.random()*360},100%,50%)`;
document.body.appendChild(c);
setTimeout(()=>c.remove(),4000);
}
setInterval(createConfetti,150);
</script>

<audio autoplay loop>
<source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
</audio>

</body>
</html>
