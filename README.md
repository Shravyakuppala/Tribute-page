# Tribute-page.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Tribute to Nick Vujicic</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header class="header">
    <nav class="navbar">
      <a href="#home" class="nav-logo">Tribute to Nick Vujicic</a>
      <ul class="nav-links">
        <li><a href="#home">Home</a></li>
        <li><a href="#achievements">Achievements</a></li>
        <li><a href="#Quotes">Quotes</a></li>
      </ul>
    </nav>
    <div class="header-content" id="home">
      <h1>LIFE LESSONS FROM NICK VUJICIC</h1>
      <p> Nick Vujicic has inspired the world with their unparalleled contributions and achievements.</p>
    </div>
  </header>
  <div class="image">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQdxGDN5BW2exi8er6dmSV_UsZsvUkkYc5QYw&s" height="400" width="400">
    <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2lio3HK4AhrdLXf1rsUPpKZveS1qzysEwyA&s" height="400" width="400">
  </div>

  <main class="main-content">
    <section class="about" id="about">
     <h2>About Nick Vujicic</h2>  
      <p>
        Nick Vujicic is an Australian preacher and motivational speaker. Nicholas James Vujicic was born on 4th December 1982 with Tetra-amelia syndrome, a rare disorder characterized by the absence of all four limbs.Being born without arms and legs, his childhood was filled with constant bullying and teasing at school, which left him feeling depressed — even attempting suicide at age 10. However, Vujicic fought through hard times, turning obstacles and failures into learning opportunities.ecause Vujicic does not let his disability overtake his life, he has learned how drive, beat a drum, write, pen an autobiography, use the computer, play tennis, and even surf. Vujicic presents motivational speeches worldwide, on life with a disability, hope, and finding meaning in life.He knows how to use a computer and can type up to 45 words per minute using the "heel and toe" method. He has also learned to throw tennis balls, play drum pedals, get a glass of water, comb his hair, brush his teeth, answer the phone and shave, in addition to participating in golf, swimming, and even sky-diving.Nick Vujicic's life was a constant battle of self-acceptance and grief, but his mother made him realize that his imperfection is a perfect inspiration to others. It was his life's turning point where his mother showed him a piece of article from a newspaper about a man who's still happy even with disability.He found that self-confidence and belief to face individuals. He decided to share his life story and inspire others to better their lives and the world around them. Nick believes that God chose him to tell each and everyone that they are too precious to him and he will never give up on them.ick's focal statement was that "God can use anyone, it doesn't matter who you are", and this fit perfectly with the theme of WOW, which was Chosen.
      </p>
    </section>

    <section class="achievements" id="achievements">
      <h2>Achievements</h2>
      <div class="achievement-grid">
        <div class="achievement-card">
          <h3>Achievement 1</h3>
          <ul>
          <p>
            <li>Founder, President and Chief Executive Officer: Life Without Limbs, US; Attitude Is Altitude, US, a motivational organization seeking to help individuals meet life's challenges with purpose, perspective, principles and perseverance; motivational speaker, evangelist, author, director and producer in music and video.</li>
            <li>Vujicic is also an accomplished author, publishing books such as,
            </li> 
            <li>“Life Without Limits: Inspiration for a Ridiculously Good Life” (2012), “Unstoppable: The Incredible Power of Faith in Action” (2013), “Stand Strong: You Can Overcome Bullying (and Other Stuff That Keeps You Down)” (2015),
            </li>
            </p>
        </ul>
        </div>
        <div class="achievement-card">
          <h3>Achievement 2</h3>
          <ul>
          <p>
            <li>Author: Vujicic wrote the book Life Without Limits: Inspiration for a Ridiculously Good Life.</li>
            <li></li>Motivational speaker: Vujicic is a world-renowned motivational speaker who inspires audiences with his message of hope and positive mindset.</li>
          </p>
          </ul>
        </div>
        <div class="achievement-card">
          <h3>Achievement 3</h3>
          <ul>
          <p>
            <li>Graduation: Vujicic graduated from Griffith University in Queensland, Australia with a degree in Accounting & Financial Planning in 2003.</li> 
            <li>Young Australian of the Year nomination: Vujicic was nominated for Young Australian of the Year in 2005.</li>
            <li>Life Without Limbs: Vujicic founded the non-profit organization, Life Without Limbs.</li>
          </p>
        </ul>
        </div>
      </div>
    </section>
    <section class="Quotes",id="Quotes">
      <div class="Quotes">
      <h2>Quotes</h2>
      <ul>
        <p>
          <li>“If you can't get a miracle, become one.”</li>
          <li>“I have the choice to be angry at God for what i don't have, or be thankful for what i do have.”</li>
          <Li>“Pain is Pain. Broken is Broken. FEAR is the Biggest Disability of all. And will PARALYZE you More Than Being in a Wheelchair.”</Li>
          <li>“Don't put your life on hold so that you can dwell on the unfairness of past hurts.”</li>
          <li>“If I fail, I try again, and again, and again.”</li>
        </p>
      </ul>
    </div>
    </section>

    
  </main>

  <footer class="footer">
    <p>© 2024 Tribute to Nick Vujicic. Designed by Shravya.</p>
  </footer>
</body>
</html>

#Tribute-page.css

 {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}


body {
  font-family: 'Arial', sans-serif;
  color: #333;
  background-color: #f4f4f9;
  line-height: 1.6;
}

.navbar {
  background: #34355e;
  display: flex;
  justify-content: space-between;
  padding: 15px 20px;
  color: white;
}

.nav-logo {
  font-size: 1.5rem;
  text-decoration: none;
  color: rgb(255, 255, 255);
}

.nav-links {
  list-style: none;
  display: flex;
}

.nav-links li {
  margin: 0 15px;
}

.nav-links a {
  text-decoration: none;
  color: white;
  font-size: 1rem;
}

.nav-links a:hover {
  text-decoration: underline;
}

/* Header styles */
.header {
  text-align: center;
  background: #2c3e50;
  color: white;
  padding: 50px 20px;
}

.header-content h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.header-content p {
  font-size: 1.2rem;
}

/* Main content */
.main-content {
  padding: 20px;
  max-width: 1200px;
  margin: 0 auto;
}

.about, .Quotes .achievements {
  margin-bottom: 50px;
}

.about h2, .Quotes h2, .achievements h2 {
  font-size: 2rem;
  color: #34495e;
  margin-bottom: 10px;
}

p {
  font-size: 1rem;
  color: #555;
}
.achievement-grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
}

.achievement-card {
  background: #ecf0f1;
  border-radius: 8px;
  padding: 20px;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
  flex: 1 1 calc(33% - 20px);
  text-align: center;
}

.achievement-card h3 {
  color: #2c3e50;
  margin-bottom: 10px;
}
.Quotes-grid {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  
}
.footer {
  text-align: center;
  background: #38345e;
  color: rgb(255, 255, 255);
  padding: 20px 0;
  font-size: 0.9rem;
}
