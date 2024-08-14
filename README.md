<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pakistan Armed Forces | SAQLAIN</title>
    <link href="https://fonts.googleapis.com/css2?family=Garamond:wght@400;700&display=swap" rel="stylesheet">

    <style>
body {
    font-family: 'Garamond', serif;
    margin: 0;
    padding: 0;
    background-color: black;
}


        header {
            background-color: #00401a;
            color: white;
            padding: 20px;
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        header p {
            margin: 10px 0 0;
        }

        nav ul {
            background-color: #006030;
            overflow: hidden;
            color: white;
            padding: 0;
            text-align: center;
            margin: 0;
            list-style: none;
        }

        nav ul li {
            display: inline;
            padding: 20px;
            animation: slideIn 1s ease-in-out;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        nav ul li a:hover {
            background-color: #00401a;
            padding: 20px;
            animation: backgroundPulse 0.5s infinite;
        }

        section {
            margin: 20px;
            padding: 20px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
            transition: transform 0.3s ease;
            animation: fadeInUp 1s ease-in-out;
        }

        section h2 {
            color: #006030;
            margin-top: 0;
        }

        section p {
            z-index: 2;
            position: relative;
        }

        .image-hover {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            opacity: 0;
            background-color: rgba(0, 0, 0, 0.5);
            display: flex;
            justify-content: center;
            align-items: center;
            transition: opacity 0.3s ease;
        }

        .image-hover img {
            max-width: 100%;
            max-height: 100%;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.5);
            transform: translateY(20px);
            animation: slideUp 0.5s ease-in-out;
        }

        section:hover .image-hover {
            opacity: 1;
        }

        section:hover .image-hover img {
            transform: translateY(0);
            animation: slideUp 0.5s ease-in-out;
            cursor: pointer;
        }

        .flag-container {
            position: relative;
            width: 100%;
            height: 200px;
            transform-origin: left;
            animation: wave 3s infinite ease-in-out;
            margin-bottom: 20px;
        }

        .flag {
            width: 100%;
            height: 100%;
            display: flex;
        }

        .green {
            background-color: #01411C;
            width: 70%;
            height: 100%;
            position: relative;
        }

        .white {
            background-color: white;
            width: 30%;
            height: 100%;
        }

        .moon-star {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 70%;
            height: 70%;
            background-image: url('/images/star_moon.jpg');
            mix-blend-mode: multiply;
            background-size: contain;
            background-repeat: no-repeat;
            background-position: center;
        }

        footer {
            background-color: #00401a;
            color: white;
            text-align: center;
            padding: 10px;
            position: relative;
            bottom: 0;
            width: 100%;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        @keyframes fadeInUp {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }

        @keyframes slideUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        @keyframes slideIn {
            from { transform: translateX(-100%); }
            to { transform: translateX(0); }
        }

        @keyframes backgroundPulse {
            0% { background-color: #00401a; }
            50% { background-color: #008040; }
            100% { background-color: #00401a; }
        }

        @keyframes wave {
            0% { transform: rotate(0deg); }
            25% { transform: rotate(-3deg); }
            50% { transform: rotate(0deg); }
            75% { transform: rotate(3deg); }
            100% { transform: rotate(0deg); }
        }
#container{
  background: linear-gradient(90deg, red, yellow, green);
  animation: bg 5s linear infinite;
}
@keyframes bg{
  100%{
    filter: hue-rotate(360deg);
  }
}
.click{
  font-weight: bold;
  color: whitesmoke;
  display: none;
}
.hidden{
   color: blue;
   text-decoration: underline;
   cursor: pointer;
}
.nWeb{
  background-color: #1e1e1e;
  color: whitesmoke;
  border: 2px dotted red;
  font-family: 'Courier New', Courier, monospace;
  box-shadow: 0px 0px 10px white;
  font-weight: bold;
  text-decoration: none;
  cursor: pointer;
}
.container {
            max-width: 800px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
.section {
            margin-bottom: 20px;
        }
.cut{
  cursor: pointer;
  width: 20px;
  height: 20px;
  float: right;
  position: relative;
  bottom: 80px;
  right: 20px;
}        
    </style>
</head>
<body>
    <header>
        <h1>Pakistan Armed Forces</h1>
        <p>Honoring the Heroes of Our Nation</p>
    </header>
    <div class="flag-container">
        <div class="flag">
            <div class="green">
                <div class="moon-star"></div>
            </div>
            <div class="white"></div>
        </div>
    </div>
    <nav>
        <ul>
            <li><a id="paf" href="#airforce">Air Force</a></li>
            <li><a id="pa" href="#army">Army</a></li>
            <li><a id="ssg" href="#ssg">SSG</a></li>
            <li><a id="saqlain" href="#others">Developer</a></li>
        </ul>
    </nav>
 <div id="container">
    <section id="airforce">
        <h2>Pakistan Air Force</h2>
        <p>The Pakistan Air Force (PAF) is the aerial warfare branch of the Pakistan Armed Forces, responsible for defending Pakistani airspace and conducting air operations.</p>
        <div class="image-hover">
            <img src="/images/Air_Force.jpg" alt="Pakistan Air Force">
        </div>
    </section>
    <section id="army">
        <h2>Pakistan Army</h2>
        <p>The Pakistan Army is the principal land warfare branch of the Pakistan Armed Forces. It plays a vital role in defending the nation and maintaining peace and security.</p>
        <div class="image-hover">
            <img src="/images/Pakistan-Army-2.jpg" alt="Pakistan Army">
        </div>
    </section>
    <section id="ssg">
        <h2>SSG Commandos</h2>
        <p>The Special Services Group (SSG) is the elite special operations force of the Pakistan Army, trained for specialized missions and critical operations.</p>
        <div class="image-hover">
            <img src="/images/Pak_SSG_Commando.jpg" alt="SSG Commandos">
        </div>
    </section>
    <section id="isi">
        <h2>Inter-Services Intelligence (ISI)</h2>
        <p>The ISI is Pakistan's premier intelligence agency, responsible for gathering intelligence and ensuring national security.</p>
        <div class="image-hover">
            <img src="/images/Pak_ISI.jpg" alt="ISI">
        </div>
    </section>
    <section id="others">
        <h2>Other Forces</h2>
        <p>In addition to the Army, Air Force, and SSG Commandos, Pakistan's defense is supported by the Navy, Frontier Corps, Rangers, and other security agencies.</p>
        <div class="image-hover">
            <img src="/images/All_Pak_Forces.jpg" alt="Other Forces">
        </div>
    </section>
   </div>
<div id="no">
  
<div id="apaf" class="click">
 <h1 class="hidden">Pakistan Air Force</h1><img id="cross1" class="cut" src="/images/x-mark-4-512.png" alt="click to remove">
<p>The Pakistan Air Force (PAF) is renowned for its exceptional bravery and courage. Throughout its history, PAF personnel have displayed remarkable valor in the face of adversity, often going beyond the call of duty to protect the nation's airspace and interests.</p>

<p>During conflicts, such as the Indo-Pakistani wars of 1965 and 1971, PAF pilots and ground crew exhibited extraordinary courage. Their daring missions, including high-risk aerial dogfights and precision strikes, played a crucial role in defending Pakistan and securing strategic advantages. The bravery of PAF personnel is not only celebrated in combat but also reflected in their unwavering commitment to duty during peacetime operations.</p>

<p>The PAF's courage extends beyond combat. In times of natural disasters and humanitarian crises, PAF personnel have consistently stepped up, providing relief and support to affected communities. Their resilience and readiness to face any challenge reinforce the values of bravery and selflessness that define the Pakistan Air Force.</p>

<h2>Notable Incident of Bravery</h2>
<p>One of the most notable examples of PAF bravery is the story of Squadron Leader M.M. Alam, who became a national hero for his incredible performance in the 1965 war. His remarkable ability to down multiple enemy aircraft in a single mission highlighted the skill and determination of the PAF. Such acts of heroism are emblematic of the PAF's spirit and dedication.</p>
</div>
<div id="aArmy" class="click">
  <h1 class="hidden">Pakistan Army</h1><img id="cross2" class="cut" src="/images/x-mark-4-512.png" alt="click to remove">
     <p>The Pakistan Army is renowned for its exceptional bravery and courage, qualities that have been demonstrated in numerous conflicts and peacekeeping missions. Soldiers of the Pakistan Army have consistently displayed unparalleled valor, dedication, and resilience in the face of daunting challenges.</p>
     
   <p>Throughout its history, the Pakistan Army has engaged in several significant conflicts, including the Indo-Pakistani wars of 1948, 1965, and 1971. During these conflicts, Pakistani soldiers exhibited extraordinary bravery, often under intense combat conditions. The Army's ability to hold strategic positions, execute daring operations, and protect national interests has earned it a distinguished reputation for heroism.</p>

   <p>The Army's bravery extends beyond the battlefield. In times of natural disasters and emergencies, Pakistani soldiers are often the first responders, providing aid and relief to affected communities. Their selfless service during disasters such as earthquakes, floods, and other crises underscores their unwavering dedication to the well-being of their fellow citizens.</p>
   
   <p>The Pakistan Army's commitment to duty and valor in the face of adversity continue to inspire and strengthen the nation's resolve. The bravery of its soldiers remains a cornerstone of the Army's legacy and a testament to their unwavering dedication to protecting and serving their country.</p>
   
   <h2>Notable Incident of Bravery</h2>
   <p>One of the most notable examples of the Pakistan Army's bravery is the defense of the Siachen Glacier, one of the highest and most challenging battlefields in the world. Soldiers stationed in this harsh environment face extreme weather and difficult terrain while performing their duties with courage and determination, reflecting their commitment to national security.</p>
</div>
<div id="pSsg" class="click">
  <h1 class="hidden">Pakistan SSG Commando</h1><img id="cross3" class="cut" src="/images/x-mark-4-512.png" alt="click to remove">
  <p>The Special Services Group (SSG) of the Pakistan Army is renowned for its elite status, exceptional bravery, and unparalleled courage. The SSG, often referred to as Pakistan’s special forces, is distinguished by its rigorous selection process, intense training, and remarkable operational capabilities.</p>

<p>SSG commandos have earned a distinguished reputation through their participation in various high-risk operations, including counter-terrorism, hostage rescue, and special reconnaissance missions. Their bravery is exemplified by their successful operations in challenging environments, from urban settings to remote mountainous regions.</p>

<p>The SSG’s role extends to combating insurgency and terrorism within Pakistan and abroad. Their expertise in unconventional warfare and their ability to operate in hostile environments make them a critical asset in maintaining national security. Their bravery in confronting threats head-on, often at great personal risk, underscores their dedication to their mission and their country.</p>

<p>Furthermore, the SSG’s rigorous training regimen prepares them for the most demanding and dangerous missions. Their physical endurance, mental resilience, and tactical proficiency are a testament to their unwavering commitment to excellence and their readiness to face any challenge with courage.</p>

<p>The Pakistan SSG Commandos' legacy of bravery and sacrifice continues to inspire and uphold the highest standards of military excellence. Their courage and dedication remain a cornerstone of their elite status and a symbol of their commitment to safeguarding Pakistan’s security and interests.</p>

<h2>Notable Incident of Bravery</h2>
<p>One notable example of their valor is their involvement in the rescue operation during the 2014 Peshawar school attack. The SSG commandos executed a daring and precise assault to rescue hostages and neutralize the terrorists, showcasing their bravery under extreme pressure. Their swift and courageous actions saved countless lives and demonstrated their commitment to protecting the nation.</p>
</div>
<div id="pSd" class="click">
  <h1 class="hidden">Muhammd Saqlain Shoulat</h1><img id="cross4" class="cut" src="/images/x-mark-4-512.png" alt="click to remove">
   <div class="section">
   <p>I am currently a student in the 1st Year of ICS and also a web developer and phishing attacker. I live in Kot Sultan. Balancing my studies with my interests in web development and cybersecurity, I am dedicated to advancing my skills in these fields.</p>
 </div>

 <div class="section">
   <h2>Intelligence and Dedication</h2>
   <p>My intelligence and dedication are reflected in my academic and practical pursuits. I approach challenges with a problem-solving mindset and a strong desire to learn and grow. Whether in my studies or in developing new projects, I consistently strive for excellence and seek innovative solutions.</p>
 </div>

 <div class="section">
   <h2>Aims and Aspirations</h2>
   <p>My aim is to make my city famous and to brighten my country’s name on the global stage. I am committed to honoring my father's name, Shoukat Ali, by contributing positively and making a significant impact. I aspire to bring recognition and pride to my community through my achievements and dedication.</p>
 </div>

 <div class="section">
   <h2>Love for Pakistan</h2>
   <p>My love for Pakistan is deep and unwavering. I hold great admiration for the ISI, Pakistan Army, Pakistan Air Force, and the Special Services Group (SSG) Commandos. Their bravery, dedication, and service to the nation inspire me and reinforce my commitment to supporting and celebrating the values they stand for.</p>
 </div>
 <a class="nWeb" href="https://saqlainshoukat.github.io/SaqlainShoukat/">More About Developer</a>
 <br><br>
 <h2>Support Me</h2>
 <p>1): Join My Youtube Channel. Click on "My Youtube Channel" button<br><a class="nWeb" href="https://youtube.com/@codingchatroom?si=ivmBCVjjpXKTmxqE">My Toutube Channel</a></p>
 
 <p>2): Join My TikTok Channel. Click on "My TikTok Account" button<br><a class="nWeb" href="https://www.tiktok.com/@saki_edits786?_t=8orOwxEni3b&_r=1">My TikTok Accountl</a></p>
 </div>
</div>
</div>
    <footer>
        <p>&copy; 2024 Pakistan Armed Forces Tribute | Independence Day | from Developer | Saqlain</p>
    </footer>
<script>
  alert("Pakistan Armed Forces Tribute | Independence Day | from Developer | Saqlain");
  document.getElementById("paf").onclick = function() {
    document.getElementById("container").style.display = "none";
    document.getElementById("apaf").style.display = "inline";
  };
  document.getElementById("pa").onclick = function() {
  document.getElementById("container").style.display = "none";
  document.getElementById("aArmy").style.display = "inline";
};
  document.getElementById("ssg").onclick = function() {
    document.getElementById("container").style.display = "none";
    document.getElementById("pSsg").style.display = "inline";
  };
  document.getElementById("saqlain").onclick = function() {
  document.getElementById("container").style.display = "none";
  document.getElementById("pSd").style.display = "inline";
};
//cross start from here:-
document.getElementById("cross1").onclick = function() {
  document.getElementById("apaf").style.display = "none";
  document.getElementById("container").style.display = "block";
};

document.getElementById("cross2").onclick = function() {
  document.getElementById("aArmy").style.display = "none";
  document.getElementById("container").style.display = "block";
};

document.getElementById("cross3").onclick = function() {
  document.getElementById("pSsg").style.display = "none";
  document.getElementById("container").style.display = "block";
};

document.getElementById("cross4").onclick = function() {
  document.getElementById("pSd").style.display = "none";
  document.getElementById("container").style.display = "block";
};
</script>
</body>
</html> 
