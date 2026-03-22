<!DOCTYPE html>
<html lang="gu">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shree Karni Solar Enterprise</title>
<style>
body {font-family: Arial; margin:0;}
header {background:#0a7d3b; color:white; padding:20px; text-align:center;}
nav {background:#222; padding:10px; text-align:center;}
nav a {color:white; margin:10px; text-decoration:none;}
section {padding:40px; text-align:center;}
.services {display:flex; flex-wrap:wrap; justify-content:center;}
.services div {border:1px solid #ddd; margin:10px; padding:20px; width:220px; border-radius:10px;}
footer {background:#111; color:white; padding:15px; text-align:center;}
.whatsapp {position:fixed; bottom:20px; right:20px; background:#25D366; color:white; padding:15px; border-radius:50%; text-decoration:none; font-size:22px;}
input, textarea {width:80%; padding:10px; margin:10px; border-radius:5px; border:1px solid #ccc;}
button {background:green; color:white; padding:10px 20px; border:none; border-radius:5px;}
img {max-width:100%; border-radius:10px;}
.hero {background:url('https://images.unsplash.com/photo-1509395176047-4a66953fd231') no-repeat center/cover; color:white; padding:100px 20px;}
</style>
</head>

<body>

<header>
<h1>Shree Karni Solar Enterprise</h1>
<p>તમારા ભવિષ્યને સોલરથી ઉજળું બનાવો ☀️</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#projects">Projects</a>
<a href="#contact">Contact</a>
</nav>

<section class="hero">
<h2>Save Electricity | Earn with Solar</h2>
<p>Government Subsidy Available</p>
<button onclick="window.location.href='#contact'">Free Quote મેળવો</button>
</section>

<section id="services">
<h2>અમારી સેવાઓ</h2>
<div class="services">
<div>☀️ Solar Panel Installation</div>
<div>🏠 Solar Rooftop System</div>
<div>🚜 Solar Water Pump</div>
<div>🔧 Maintenance & Service</div>
</div>
</section>

<section id="projects">
<h2>અમારા પ્રોજેક્ટ્સ</h2>
<img src="https://images.unsplash.com/photo-1584270354949-1c5a6d8c3c4f">
<p>Residential & Commercial Solar Installations</p>
</section>

<section id="gallery">
<h2>અમારી ગેલેરી</h2>
<div class="services">
<img src="solar1.jpg" alt="project1">
<img src="solar2.jpg" alt="project2">
<img src="solar3.jpg" alt="project3">
</div>
<p>અમારા રિયલ સોલર પ્રોજેક્ટ્સ</p>
</section>

<section id="about">
<h2>અમારા વિશે</h2>
<p>Shree Karni Solar Enterprise વિશ્વસનીય સોલર સેવા પ્રદાતા છે. અમે ઘર, બિઝનેસ અને ખેતી માટે સસ્તા અને ગુણવત્તાવાળા સોલર સોલ્યુશન આપીએ છીએ.</p>
</section>

<section id="contact">
<h2>સંપર્ક કરો</h2>
<p>📞 9274565072</p>
<p>📍 Gujarat, India</p>

<form onsubmit="sendWhatsApp(); return false;">
<input type="text" id="name" placeholder="તમારું નામ" required><br>
<input type="tel" id="phone" placeholder="મોબાઇલ નંબર" required><br>
<textarea id="message" placeholder="તમારો મેસેજ"></textarea><br>
<button type="submit">મોકલો</button>
</form>
</section>

<a class="whatsapp" href="https://wa.me/919274565072" target="_blank">💬</a>

<footer>
<p>© 2026 Shree Karni Solar Enterprise</p>
</footer>

<script>
function sendWhatsApp() {
var name = document.getElementById('name').value;
var phone = document.getElementById('phone').value;
var message = document.getElementById('message').value;

var url = "https://wa.me/919274565072?text="
+ "Name: " + name + "%0a"
+ "Phone: " + phone + "%0a"
+ "Message: " + message;

window.open(url, '_blank');
}
</script>

</body>
</html>
<img src="solar4.jpg">
<img src="solar5.jpg">
<img src="solar6.jpg">
<img src="solar7.jpg">
<img src="solar8.jpg">
<img src="solar9.jpg">
