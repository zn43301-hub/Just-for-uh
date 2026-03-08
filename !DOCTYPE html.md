<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<title>Secret Letter</title>  
  
<style>  
  
body{  
    background:#556B2F;  
    font-family: 'Georgia', serif;  
    color:white;  
    display:flex;  
    justify-content:center;  
    align-items:center;  
    height:100vh;  
    margin:0;  
}  
  
.container{  
    text-align:center;  
    max-width:800px;  
}  
  
.envelope{  
    width:200px;  
    height:140px;  
    background:#6B8E23;  
    position:relative;  
    margin:auto;  
    cursor:pointer;  
    border-radius:6px;  
}  
  
.envelope:before{  
    content:"";  
    position:absolute;  
    top:-70px;  
    left:0;  
    border-left:100px solid transparent;  
    border-right:100px solid transparent;  
    border-bottom:70px solid #556B2F;  
}  
  
.hidden{  
    display:none;  
}  
  
input{  
    padding:10px;  
    border:none;  
    border-radius:5px;  
    margin-top:10px;  
}  
  
button{  
    padding:10px 20px;  
    border:none;  
    border-radius:5px;  
    background:#3e4d1c;  
    color:white;  
    margin-top:10px;  
    cursor:pointer;  
}  
  
.message{  
    background:#6B8E23;  
    padding:30px;  
    border-radius:10px;  
    text-align:left;  
    line-height:1.6;  
    overflow:auto;  
    max-height:70vh;  
}  
  
h1{  
    margin-bottom:30px;  
}  
  
</style>  
</head>  
  
<body>  
  
<div class="container">  
  
<div id="step1">  
<h1>Click the Envelope</h1>  
<div class="envelope" onclick="openEnvelope()"></div>  
</div>  
  
<div id="step2" class="hidden">  
<h2>Enter Password</h2>  
<input id="pass1" type="password" placeholder="Password">  
<br>  
<button onclick="checkPass1()">Open</button>  
</div>  
  
<div id="step3" class="hidden">  
<h2>Enter Second Password</h2>  
<input id="pass2" type="password" placeholder="Password">  
<br>  
<button onclick="checkPass2()">Open</button>  
</div>  
  
<div id="step4" class="hidden message">  
  
<p>  
Mere ladlyyyyy future begummmm<br><br>  
  
Ma jane se pehle ye kahna chahta k    
I promise that k nikah k bad tm ne jasa Socha hua hm wase h life guzre g    
Blkay us se b kahin gunah zayda axhe    
Ma gurente deta k hmre life same wase h ho g jasa tm chahti jasa hm dono ne mil kr socha hua ❤️    
  
<br><br>  
  
Jasa tm ne muje call pr bataya thaaaaaaa bilkul wasaaa hiiiii    
Jasa tm chahti ek ghr ho us ma srf ma or tm    
  
<br><br>  
  
Hm mil kr cooking krein    
Ma talwat kru or mere shoulder pr tmra sr    
Bilkul asa he ho ga begum    
I promise 🤍    
  
<br><br>  
  
Ma talwat pr ke sunao ga tm mere shoulder pr sr rkna 🤍    
Dherrr sare batein krein ge hr topic k relatedd    
  
<br><br>  
  
Kabheeee ma bolo gaaa tm sunaaa    
Kabhe tm bolna ma suno gaaaa    
  
<br><br>  
  
Sameeeee dressing krein g jaha b jain ge    
Tme khd apne hatho se kana kilaua kro ga    
Tme khd apne hato se mehndi lagaya kro gaa    
  
<br><br>  
  
Apne hatho se tmre hatho ma churian pehnaya kru ga ❤️    
Khd tme rings pehnaya kro ga apne se 🤍    
  
<br><br>  
  
Tmre balo pr brush b ma h kia kru ga 🫠❤️    
  
<br><br>  
  
Hr chzzz hm mil kr krein h    
Bs ma itna kahna chahta jasa tm chahti hm waseeee h life gusre g mere ladlyyyy begummmmm 🤍    
  
<br><br>  
  
Tmra hathh kabhii ni chorne wala    
Ekele ma bi nahi or na h sb k smne 🤍    
  
<br><br>  
  
Begummmm ma tm se behadd pyar krta    
Khd se b zaydaaaaaaaaaaaaaaa    
  
<br><br>  
  
Maaaa srfff tmraaaaa huuuuuuu    
SRF TMAAAHARAAAA    
  
<br><br>  
  
I will really missss uhh alotttt Begummmmmm 🫠❤️    
  
<br><br>  
  
And I will alwaysssss love uhhhh the way uh want 🫠🤍    
Loveeeee uh alottt begummm 🤍  
</p>  
  
</div>  
  
</div>  
  
<script>  
  
function openEnvelope(){  
document.getElementById("step1").classList.add("hidden");  
document.getElementById("step2").classList.remove("hidden");  
}  
  
function checkPass1(){  
let p=document.getElementById("pass1").value;  
if(p==="zanoor"){  
document.getElementById("step2").classList.add("hidden");  
document.getElementById("step3").classList.remove("hidden");  
}else{  
alert("Wrong Password");  
}  
}  
  
function checkPass2(){  
let p=document.getElementById("pass2").value;  
if(p==="10-8-2005"){  
document.getElementById("step3").classList.add("hidden");  
document.getElementById("step4").classList.remove("hidden");  
}else{  
alert("Wrong Password");  
}  
}  
  
</script>  
  
</body>  
</html>  
