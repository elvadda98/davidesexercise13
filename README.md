<!DOCTYPE html>
<html lang="it">
<head>
<meta charset="UTF-8">
<title>Past Continuous vs Past Perfect – Grammar Trainer</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>
:root{
  --brand:#64d404;
  --bg:#f2fbf6;
  --card:#ffffff;
  --text:#1f2d1f;
  --muted:#5f6f5f;
  --border:#d9ead3;
  --ok:#2e9e44;
  --bad:#d9534f;
}

*{box-sizing:border-box}

body{
  margin:0;
  font-family:system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;
  background:linear-gradient(135deg,#eafff2,#eef7ff);
  color:var(--text);
  padding:20px;
}

.app{
  max-width:900px;
  margin:auto;
  background:var(--card);
  border-radius:20px;
  border:1px solid var(--border);
  overflow:hidden;
}

header{
  padding:20px;
  background:linear-gradient(90deg,var(--brand),#a5ef7c);
}

h1{margin:0}
.sub{opacity:.9}

.slide{
  display:none;
  padding:24px;
}
.slide.active{display:block}

.card{
  background:#fff;
  border-radius:16px;
  padding:20px;
  border:1px solid var(--border);
}

.box{
  border:1px solid var(--border);
  border-radius:12px;
  padding:14px;
  margin-bottom:14px;
}

.example{
  background:#f1fbee;
  border-left:4px solid var(--brand);
  padding:10px;
  border-radius:8px;
  margin-top:8px;
}

button{
  border-radius:10px;
  border:1px solid var(--border);
  background:#f6fff2;
  padding:8px 14px;
  cursor:pointer;
  font-weight:600;
}

button.primary{
  background:var(--brand);
  color:#143000;
  border:none;
}

.nav{
  display:flex;
  justify-content:space-between;
  padding:14px;
  border-top:1px solid var(--border);
}

input[type=text], textarea{
  padding:6px 8px;
  border-radius:8px;
  border:1px solid var(--border);
  font-size:15px;
}

.opt{
  padding:10px;
  border:1px solid var(--border);
  border-radius:10px;
  margin:6px 0;
  cursor:pointer;
  background:#f8fff6;
}

.correct{background:#c9f2c9}
.wrong{background:#ffd4d4}

.small{color:var(--muted); font-size:14px}
</style>
</head>

<body>
<div class="app">

<header>
  <h1>Past Continuous vs Past Perfect</h1>
  <div class="sub">Spiegazione + esercizi progressivi</div>
</header>

<!-- SLIDE 1 -->
<section class="slide active">
<div class="card">
<h2>1️⃣ Past Continuous – spiegazione</h2>

<div class="box">
<p>
Usiamo il <b>Past Continuous</b> per parlare di un’azione che
<b>stava succedendo in un preciso momento del passato</b>.
</p>

<p><b>Forma:</b> was / were + verbo + ING</p>

<p>
👉 In italiano spesso equivale a:
<br><i>stavo facendo qualcosa</i>
</p>

<div class="example">
At 8 pm I <b>was studying</b>.<br>
(Alle 8 stavo studiando)
</div>

<p class="small">
💡 Il Past Continuous spesso fa da “sfondo” a un’altra azione.
</p>
</div>
</div>
</section>

<!-- SLIDE 2 -->
<section class="slide">
<div class="card">
<h2>2️⃣ Past Perfect – spiegazione</h2>

<div class="box">
<p>
Usiamo il <b>Past Perfect</b> per parlare di un’azione che è
<b>successa prima di un’altra azione nel passato</b>.
</p>

<p><b>Forma:</b> had + past participle</p>

<p>
👉 In italiano spesso equivale a:
<br><i>avevo fatto qualcosa</i>
</p>

<div class="example">
When I arrived, they <b>had already left</b>.<br>
(Quando sono arrivato, erano già andati via)
</div>

<p class="small">
⏱️ Serve a chiarire l’ordine degli eventi.
</p>
</div>
</div>
</section>

<!-- SLIDE 3 -->
<section class="slide">
<div class="card">
<h2>3️⃣ Scegli il tempo corretto</h2>

<p>1) At 9 pm I ___ TV.</p>
<div class="opt" onclick="mcq(this,true)">was watching</div>
<div class="opt" onclick="mcq(this,false)">watched</div>
<div class="opt" onclick="mcq(this,false)">had watched</div>

<p>2) By the time we arrived, the film ___</p>
<div class="opt" onclick="mcq(this,false)">was starting</div>
<div class="opt" onclick="mcq(this,true)">had started</div>
<div class="opt" onclick="mcq(this,false)">started</div>
</div>
</section>

<!-- SLIDE 4 -->
<section class="slide">
<div class="card">
<h2>4️⃣ Cosa è successo prima?</h2>

<p>
When I arrived, she had finished dinner.
</p>

<div class="opt" onclick="mcq(this,true)">
Ha finito di cenare prima che io arrivassi
</div>
<div class="opt" onclick="mcq(this,false)">
Ha finito di cenare dopo che io sono arrivato
</div>
</div>
</section>

<!-- SLIDE 5 -->
<section class="slide">
<div class="card">
<h2>5️⃣ Completa le frasi</h2>

<p>
I was ___ when you called. (study)
</p>

<input type="text" data-a="studying">

<p>
By the time we arrived, they had ___ . (leave)
</p>

<input type="text" data-a="left">

<button class="primary" onclick="checkInputs()">Check</button>
<div id="res1"></div>
</div>
</section>

<!-- SLIDE 6 -->
<section class="slide">
<div class="card">
<h2>6️⃣ Scrivi nei gap</h2>

<p>
I <input type="text" data-a="was working"> when the phone rang.
</p>

<p>
She was tired because she <input type="text" data-a="had studied"> all day.
</p>

<p>
By the time we arrived, the meeting <input type="text" data-a="had finished">.
</p>

<button class="primary" onclick="checkInputs()">Check</button>
</div>
</section>

<!-- SLIDE 7 -->
<section class="slide">
<div class="card">
<h2>7️⃣ Listening (attenzione!)</h2>

<button class="primary" onclick="play()">🔊 Play</button>

<div id="listen"></div>
<div id="listenRes"></div>
</div>
</section>

<!-- SLIDE 8 -->
<section class="slide">
<div class="card">
<h2>8️⃣ Speaking guidato</h2>

<p>
Completa e dì la frase ad alta voce:
</p>

<p class="example">
At 9 pm yesterday, I was ________.
</p>

<p class="small">
(Usa un’azione reale)
</p>
</div>
</section>

<!-- SLIDE 9 -->
<section class="slide">
<div class="card">
<h2>9️⃣ Pronuncia</h2>

<p class="example">
I was reading when the lights went out.
</p>

<button class="primary"
onclick="speechSynthesis.speak(new SpeechSynthesisUtterance('I was reading when the lights went out'))">
🔊 Listen
</button>
</div>
</section>

<!-- SLIDE 10 -->
<section class="slide">
<div class="card">
<h2>🔟 Produzione libera</h2>

<p>
Scrivi un breve testo (5–7 righe) usando:
</p>
<ul>
<li>almeno 2 Past Continuous</li>
<li>almeno 2 Past Perfect</li>
<li>when / by the time</li>
</ul>

<textarea rows="6" style="width:100%"></textarea>
</div>
</section>

<div class="nav">
<button onclick="prev()">⬅ Prev</button>
<button onclick="next()">Next ➡</button>
</div>

</div>

<script>
let i=0;
const slides=document.querySelectorAll('.slide');

function show(){
slides.forEach((s,n)=>s.classList.toggle('active',n===i));
}
function next(){if(i<slides.length-1){i++;show();}}
function prev(){if(i>0){i--;show();}}

function mcq(el,ok){
el.classList.add(ok?'correct':'wrong');
}

function checkInputs(){
document.querySelectorAll('input[data-a]').forEach(i=>{
if(i.value.trim().toLowerCase()===i.dataset.a){
i.style.background='#c9f2c9';
}else{
i.style.background='#ffd4d4';
}
});
}

const listens=[
"I was working when you called.",
"I had worked when you called.",
"I worked when you called.",
"I had been working when you called."
];
let correct=0;

function play(){
correct=Math.floor(Math.random()*listens.length);
speechSynthesis.speak(new SpeechSynthesisUtterance(listens[correct]));
const d=document.getElementById('listen');
d.innerHTML='';
listens.forEach((s,n)=>{
const o=document.createElement('div');
o.className='opt';
o.innerText=s;
o.onclick=()=>o.classList.add(n===correct?'correct':'wrong');
d.appendChild(o);
});
}
</script>

</body>
</html>
