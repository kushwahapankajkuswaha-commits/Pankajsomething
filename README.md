<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>JaxStudyHub</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:#f4f8ff;
color:#222;
}

header{
background:#1565C0;
color:whit
nav{
background:#0Dtext-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:12px;
font-weight:bold;
}

.hero{
padding:50px 20px;
text-align:center;
}

.hero h1{
font-size:36px;
}

.button{
display:inline-block;
background:#1565C0;
color:white;
padding:12px 24px;
text-decoration:none;
border-radius:8px;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:20px;
padding:20px;
}

.card{
background:white;
padding:20px;
width:220px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,0.2);
text-align:center;
}

footer{
background:#0D47A1;
color:white;
text-align:center;
padding:15px;
margin-top:20px;
}
</style>

</head>

<body>

<header>
<h1>📚 JaxStudyHub</h1>
<p>Free MP Board Class 10 Study Website</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">Math</a>
<a href="#">Science</a>
<a href="#">SST</a>
<a href="#">English</a>
</nav>

<section class="hero">
<h1>Welcome to JaxStudyHub</h1>
<p>Notes • Important Questions • PDFs • Board Preparation</p>
<br><br>
<a href="#" class="button">Start Learning</a>
</section>

<section class="cards">

<div class="card">
<h2>📘 Mathematics</h2>
<p>Chapter-wise Notes</p>
</div>

<div class="card">
<h2>🔬 Science</h2>
<p>Easy Explanations</p>
</div>

<div class="card">
<h2>🌍 Social Science</h2>
<p>Important Questions</p>
</div>

<div class="card">
<h2>📖 English</h2>
<p>Grammar & Literature</p>
</div>

</section>

<footer>
© 2026 JaxStudyHub | Made by Pankaj
</footer>

</body>
  </html>
  
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080d1b">
<meta name="description" content="The story of Pankaj — a student, dreamer, and creator building his future.">
<title>The Story of Pankaj</title>

<style>
*{margin:0;padding:0;box-sizing:border-box}
html{scroll-behavior:smooth}
body{
  background:#080d1b;color:#edf2ff;
  font-family:Arial,sans-serif;line-height:1.7;
}
a{color:inherit;text-decoration:none}
nav{
  position:sticky;top:0;z-index:10;
  background:#080d1bee;backdrop-filter:blur(12px);
  border-bottom:1px solid #25314b;padding:15px 6%;
  display:flex;justify-content:space-between;align-items:center;
}
.logo{font-weight:800;color:#8bb8ff;letter-spacing:1px}
nav a{font-size:13px;color:#b9c6df}
.hero{
  min-height:85vh;padding:90px 8%;
  display:flex;flex-direction:column;justify-content:center;
  background:radial-gradient(ellipse at 80% 20%,#17376b 0%,transparent 48%),
             radial-gradient(ellipse at 10% 90%,#172044 0%,transparent 40%);
}
.tag{color:#8bb8ff;letter-spacing:3px;font-size:12px}
h1{font-size:clamp(44px,10vw,85px);line-height:1.08;margin:22px 0}
h1 span{color:#8bb8ff}
.hero p{max-width:590px;color:#bac7df;font-size:17px}
.btn{
  display:inline-block;margin-top:28px;padding:12px 22px;
  border:1px solid #729ee8;border-radius:7px;
  background:#18325b;color:white;cursor:pointer;
}
section{padding:75px 8%;scroll-margin-top:65px}
.heading{font-size:32px;margin-bottom:10px}
.sub{color:#9eacc8;margin-bottom:28px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
.card{
  padding:23px;border:1px solid #273550;border-radius:13px;
  background:linear-gradient(145deg,#121c31,#0b1120);
}
.card h3{margin-bottom:9px;color:#a9c9ff}
.card p{color:#acb9d0;font-size:14px}
.number{font-size:27px;margin-bottom:10px}
.timeline{border-left:2px solid #456ba7;margin:30px 0 0 8px;padding-left:25px}
.event{position:relative;margin-bottom:30px}
.event:before{
  content:"";position:absolute;left:-32px;top:8px;
  width:12px;height:12px;background:#8bb8ff;border-radius:50%;
}
.event h3{color:#a9c9ff}
.event p{color:#acb9d0;font-size:14px}
.quote{
  border-left:3px solid #8bb8ff;padding:20px 25px;
  background:#111b30;border-radius:0 10px 10px 0;
  font-size:20px;
}
input,textarea{
  width:100%;margin:8px 0 15px;padding:13px;
  color:white;background:#101a2c;border:1px solid #354563;
  border-radius:7px;font:inherit;
}
footer{text-align:center;padding:35px 15px;color:#8d9ab4;border-top:1px solid #26334a}
.small{font-size:12px;color:#7f91b3}
@media(max-width:500px){
 nav{padding:13px 5%}nav a{font-size:11px}
 section{padding:55px 6%}.hero{padding:65px 6%}
}
</style>
</head>

<body>
<nav>
  <a class="logo" href="#home">YOUR PANKAJ.</a>
  <a href="#story">MY STORY ↓</a>
</nav>

<header class="hero" id="home">
  <div class="tag">MY LIFE • MY DREAMS • MY JOURNEY</div>
  <h1>The Story<br>of <span>Pankaj.</span></h1>
  <p>
    A student. A dreamer. A creator.
    I am not at my destination yet.
    I am building the person I want to become,
    one day at a time.
  </p>
  <div>
    <a class="btn" href="#story">Explore My Journey ↗</a>
  </div>
  <p class="small" style="margin-top:35px">UNDERSTAND → LEARN → CREATE → GROW</p>
</header>

<section id="story">
  <h2 class="heading">01. My Story</h2>
  <p class="sub">Every big journey begins somewhere.</p>
  <div class="card">
    <h3>Still becoming.</h3>
    <p>
      My name is Pankaj Kushwaha. I am a student who wants
      to learn more, think creatively, and build something
      meaningful with technology.
      My story is not finished. Every challenge, lesson,
      and new idea is another page.
    </p>
  </div>
</section>

<section id="student">
  <h2 class="heading">02. The Student</h2>
  <p class="sub">My classroom is only the beginning.</p>
  <div class="grid">
    <div class="card">
      <div class="number">📚</div>
      <h3>Class 10 Journey</h3>
      <p>
        I am working towards my Class 10 board exams.
        My goal is to improve my understanding, practise
        consistently, and become more confident in every subject.
      </p>
    </div>
    <div class="card">
      <div class="number">🧠</div>
      <h3>My Study System</h3>
      <p>
        Understand → Memorise → Recall → Practice → Revise.
        I want to learn concepts properly instead of only
        memorising answers.
      </p>
    </div>
    <div class="card">
      <div class="number">📈</div>
      <h3>My Progress</h3>
      <p>
        My previous school results taught me that progress
        is possible. Now I want to keep improving through
        regular practice and honest effort.
      </p>
    </div>
  </div>
</section>

<section id="dreams">
  <h2 class="heading">03. The Dreamer</h2>
  <p class="sub">Big dreams. Small steps. Consistent action.</p>
  <div class="grid">
    <div class="card">
      <div class="number">🎓</div>
      <h3>IIT Bombay</h3>
      <p>
        One of my big goals is to work towards IIT Bombay.
        I know it takes preparation, patience, and discipline.
      </p>
    </div>
    <div class="card">
      <div class="number">💻</div>
      <h3>Software Engineering</h3>
      <p>
        I want to explore programming, solve problems,
        create useful software, and understand how technology works.
      </p>
    </div>
    <div class="card">
      <div class="number">🌍</div>
      <h3>Future Me</h3>
      <p>
        I want to keep learning, become independent,
        and create opportunities through my skills.
      </p>
    </div>
  </div>
</section>

<section id="creator">
  <h2 class="heading">04. The Creator</h2>
  <p class="sub">My creative side deserves its own chapter.</p>
  <div class="grid">
    <div class="card">
      <div class="number">🎬</div>
      <h3>YouTube</h3>
      <p>
        I enjoy making videos, exploring ideas, and learning
        how creators tell stories through editing.
      </p>
    </div>
    <div class="card">
      <div class="number">🎨</div>
      <h3>Editing & Design</h3>
      <p>
        Thumbnails, visual effects, music edits, and creative
        experiments help me develop my own style.
      </p>
    </div>
    <div class="card">
      <div class="number">🌐</div>
      <h3>JaxStudyHub</h3>
      <p>
        I want to build digital projects and explore how
        websites can make learning more useful and interesting.
      </p>
    </div>
  </div>
</section>

<section id="timeline">
  <h2 class="heading">05. My Timeline</h2>
  <p class="sub">The chapters that make up my journey.</p>
  <div class="timeline">
    <div class="event">
      <h3>The Learning Years</h3>
      <p>Building my school foundation and discovering how I learn best.</p>
    </div>
    <div class="event">
      <h3>The Comeback</h3>
      <p>Taking my studies seriously and working towards better results.</p>
    </div>
    <div class="event">
      <h3>The Creator Era</h3>
      <p>Exploring video editing, YouTube, coding, and new ideas.</p>
    </div>
    <div class="event">
      <h3>My Next Chapter</h3>
      <p>Board exams, new skills, projects, and bigger goals still ahead.</p>
    </div>
  </div>
</section>

<section id="mindset">
  <h2 class="heading">06. What I Believe</h2>
  <div class="quote">
    "I don't need to have everything figured out today.
    I just need to keep learning, keep creating,
    and keep moving forward."
  </div>
</section>

<section id="future">
  <h2 class="heading">07. The Unwritten Future</h2>
  <p class="sub">This chapter belongs to the person I become.</p>
  <div class="card">
    <h3>My future is still being written.</h3>
    <p>
      More knowledge. More projects. More experiences.
      More reasons to be proud of the effort I put in.
      I will keep adding new milestones as my journey grows.
    </p>
  </div>
</section>

<section id="notes">
  <h2 class="heading">08. A Note to My Future Self</h2>
  <p class="sub">
    Write a message for the future. It stays in this page
    while the page remains open.
  </p>
  <label for="futureNote">Dear future Pankaj,</label>
  <textarea id="futureNote" rows="5"
    placeholder="What do you want your future self to remember?"></textarea>
  <button class="btn" onclick="showNote()">Read My Note</button>
  <p id="noteResult" style="margin-top:18px;white-space:pre-wrap"></p>
</section>

<footer>
  <p class="logo">YOUR PANKAJ.</p>
  <p>My story. My dreams. My journey.</p>
  <p class="small">Made with curiosity and code.</p>
  <p class="small">© <span id="year"></span> Pankaj</p>
</footer>

<script>
document.getElementById("year").textContent =
  new Date().getFullYear();

function showNote(){
  const note = document.getElementById("futureNote").value.trim();
  const result = document.getElementById("noteResult");

  if(!note){
    result.textContent = "Write something for your future self first.";
    return;
  }

  result.textContent = "Dear future Pankaj,\n\n" + note;
}
</script>

</body>
</html>
