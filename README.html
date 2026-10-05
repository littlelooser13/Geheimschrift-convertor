<!doctype html>
<html lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Primfaktor-Geheimschrift</title>
<meta name="description" content="Primfaktor-Geheimschrift: Texte verschlüsseln und Geheimcodes wieder entschlüsseln.">
<meta name="theme-color" content="#5b5ce2">

<style>
:root{
  color-scheme:light dark;
  --bg:light-dark(#f5f7fb,#0d1117);
  --surface:light-dark(#fff,#161b22);
  --surface2:light-dark(#f0f3f8,#202731);
  --text:light-dark(#18202a,#f1f5f9);
  --muted:light-dark(#64748b,#9aa7b7);
  --border:light-dark(#dbe2ea,#303946);
  --accent:light-dark(#5b5ce2,#8b8df7);
  --accent2:light-dark(#4546c8,#6d70ef);
}

*{box-sizing:border-box}

body{
  margin:0;
  font-family:Inter,ui-sans-serif,system-ui,-apple-system,Segoe UI,sans-serif;
  background:var(--bg);
  color:var(--text);
}

#app{
  min-height:100vh;
  background-color:var(--bg);
}

main{
  max-width:920px;
  margin:auto;
  padding:56px 22px 70px;
}

.hero{
  text-align:center;
  margin-bottom:34px;
}

.eyebrow{
  display:inline-block;
  padding:7px 11px;
  border:1px solid var(--border);
  border-radius:999px;
  color:var(--accent);
  font-size:.78rem;
  font-weight:700;
  letter-spacing:.04em;
}

.hero h1{
  font-size:clamp(2rem,5vw,3.5rem);
  line-height:1.05;
  margin:16px 0 12px;
  letter-spacing:-.04em;
}

.hero p{
  max-width:650px;
  margin:auto;
  color:var(--muted);
  font-size:1.05rem;
  line-height:1.6;
}

.card{
  background:var(--surface);
  border:1px solid var(--border);
  border-radius:20px;
  padding:24px;
  box-shadow:0 12px 40px rgba(0,0,0,.06);
}

label{
  display:block;
  font-weight:700;
  margin-bottom:10px;
}

textarea{
  width:100%;
  min-height:150px;
  resize:vertical;
  border:1px solid var(--border);
  background:var(--surface2);
  color:var(--text);
  border-radius:14px;
  padding:16px;
  font:inherit;
  outline:none;
  transition:.2s;
}

textarea:focus{
  border-color:var(--accent);
  box-shadow:0 0 0 3px color-mix(in srgb,var(--accent) 18%,transparent);
}

.bar{
  display:flex;
  gap:10px;
  align-items:center;
  margin-top:14px;
  flex-wrap:wrap;
}

.btn{
  border:0;
  border-radius:12px;
  padding:11px 16px;
  font:inherit;
  font-weight:700;
  cursor:pointer;
  background:var(--accent);
  color:white;
}

.btn:hover{
  background:var(--accent2);
}

.ghost{
  background:var(--surface2);
  color:var(--text);
  border:1px solid var(--border);
}

.hint{
  margin-left:auto;
  color:var(--muted);
  font-size:.85rem;
}

.output{
  margin-top:18px;
}

.outputbox{
  min-height:96px;
  white-space:pre-wrap;
  word-break:break-word;
  background:var(--surface2);
  border:1px dashed var(--border);
  border-radius:14px;
  padding:18px;
  font-family:ui-monospace,SFMono-Regular,Menlo,monospace;
  font-size:1.08rem;
  line-height:1.8;
}

.section{
  margin-top:28px;
}

.section h2{
  font-size:1.15rem;
  margin:0 0 12px;
}

.rules{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:12px;
}

.rule{
  padding:16px;
  border:1px solid var(--border);
  border-radius:14px;
  background:var(--surface);
}

.rule b{
  display:block;
  margin-bottom:5px;
}

.rule span{
  color:var(--muted);
  font-size:.9rem;
  line-height:1.45;
}

@media(max-width:650px){
  main{
    padding:35px 14px 50px;
  }

  .card{
    padding:17px;
  }

  .rules{
    grid-template-columns:1fr;
  }

  .hint{
    width:100%;
    margin-left:0;
  }
}
</style>
</head>

<body>

<div id="app">
<main>

<header class="hero">
  <span class="eyebrow">PRIMFAKTOR-CODE</span>
  <h1>Primfaktor-Geheimschrift</h1>
  <p>
    Wandle normale Sätze in deinen Geheimcode um —
    oder entschlüssele einen vorhandenen Code wieder zurück.
  </p>
</header>

<section class="card">

  <label for="input">Text oder Geheimschrift</label>

  <textarea
    id="input"
    placeholder="Normaltext: HALLO WELT"
  >HALLO WELT</textarea>

  <div class="bar">

    <button class="btn" id="encode">
      → Geheimschrift
    </button>

    <button class="btn ghost" id="decode">
      ← Entschlüsseln
    </button>

    <button class="btn ghost" id="copy">
      Ausgabe kopieren
    </button>

    <button class="btn ghost" id="clear">
      Leeren
    </button>

    <span class="hint">
      Geheimcodes müssen durch Leerzeichen getrennt sein.
    </span>

  </div>

  <div class="output">

    <label>Ausgabe</label>

    <div class="outputbox" id="output"></div>

  </div>

</section>

<section class="section">

  <h2>So funktioniert das System</h2>

  <div class="rules">

    <div class="rule">
      <b>1 · Buchstabe → Zahl</b>
      <span>
        A = 1, B = 2, … Z = 26
      </span>
    </div>

    <div class="rule">
      <b>2 · Primfaktoren</b>
      <span>
        Die Zahl wird zerlegt. Höchster Primfaktor und Faktorsumme werden verbunden.
      </span>
    </div>

    <div class="rule">
      <b>3 · Geheimcode</b>
      <span>
        Die entstandene Zahl wird als Buchstabe + Zahl dargestellt
        und kann wieder zurückgewandelt werden.
      </span>
    </div>

  </div>

</section>

</main>
</div>

<script>

function primeFactors(n){

  if(n === 1){
    return [1];
  }

  const factors = [];

  while(n % 2 === 0){
    factors.push(2);
    n /= 2;
  }

  let i = 3;

  while(i * i <= n){

    while(n % i === 0){
      factors.push(i);
      n /= i;
    }

    i += 2;
  }

  if(n > 1){
    factors.push(n);
  }

  return factors;
}


function letterToCode(letter){

  letter = letter.toUpperCase();

  if(!/^[A-Z]$/.test(letter)){
    return "";
  }

  const zahl = letter.charCodeAt(0) - 65 + 1;
  const factors = primeFactors(zahl);

  let highest;
  let sum;

  if(zahl === 1){

    highest = 1;
    sum = 2;

  }else{

    highest = Math.max(...factors);
    sum = factors.reduce((a,b) => a + b, 0);

  }

  const output = Number(
    String(highest) + String(sum)
  );

  const rest = ((output - 1) % 26) + 1;
  const count = Math.floor((output - 1) / 26);

  return String.fromCharCode(64 + rest) + (count + 1);
}


function encode(text){

  return [...text]
    .map(ch => ch === " " ? " " : letterToCode(ch))
    .join("");

}


function decodeCode(code){

  if(code.length < 2){
    return "";
  }

  const letter = code[0].toUpperCase();

  if(
    !/^[A-Z]$/.test(letter) ||
    !/^[A-Za-z][0-9]+$/.test(code)
  ){
    return "";
  }

  const zahl = Number(code.slice(1));

  const output =
    (zahl - 1) * 26 +
    (letter.charCodeAt(0) - 64);

  if(output < 1){
    return "";
  }

  for(let i = 1; i <= 26; i++){

    const original =
      String.fromCharCode(64 + i);

    const factors = primeFactors(i);

    const highest =
      i === 1 ? 1 : Math.max(...factors);

    const sum =
      i === 1
        ? 2
        : factors.reduce((a,b) => a + b, 0);

    const generated =
      Number(String(highest) + String(sum));

    if(generated === output){
      return original;
    }
  }

  return "?";
}


function decode(text){

  return text
    .split(" ")
    .filter(Boolean)
    .map(code => decodeCode(code) || "?")
    .join("");

}


const input =
  document.getElementById("input");

const output =
  document.getElementById("output");


function showEncoded(){

  output.textContent =
    encode(input.value);

}


function showDecoded(){

  output.textContent =
    decode(input.value);

}


input.addEventListener(
  "input",
  showEncoded
);


document
  .getElementById("encode")
  .onclick = showEncoded;


document
  .getElementById("decode")
  .onclick = showDecoded;


document
  .getElementById("clear")
  .onclick = () => {

    input.value = "";
    output.textContent = "";
    input.focus();

  };


document
  .getElementById("copy")
  .onclick = async () => {

    try{

      await navigator.clipboard.writeText(
        output.textContent
      );

      const button =
        document.getElementById("copy");

      const oldText =
        button.textContent;

      button.textContent =
        "Kopiert ✓";

      setTimeout(
        () => button.textContent = oldText,
        1200
      );

    }catch(error){

      alert("Kopieren wurde vom Browser blockiert.");

    }

  };


showEncoded();

</script>

</body>
</html>
