# OlajideAdebayoFrank-Portfolio
 Portfolio of Olajide Adebayo Frank  A comprehensive, responsive one-page portfolio website showcasing my expertise as a Webmaster, Cloud Security Engineer, Pen Tester, and Public Health professional. This project features my personal profile, a curated selection of my web development projects
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Olajide Adebayo Frank - Portfolio</title>
  <style>
    /* Reset some default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
      line-height: 1.6;
      background-color: #f0f4f8;
      color: #333;
    }

    /* Header Styling */
    header {
      background-color: #2c3e50;
      color: #ecf0f1;
      padding: 20px 0;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 999;
    }

    header h1 {
      font-size: 2.5em;
      margin-bottom: 0.5em;
    }

    header p {
      font-size: 1.2em;
      font-weight: 300;
    }

    /* Navigation Styles */
    nav {
      margin-top: 15px;
    }

    nav a {
      color: #ecf0f1;
      margin: 0 15px;
      text-decoration: none;
      font-weight: 600;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #3498db;
    }

    /* Main Content Styles */
.main {
  max-width: 1200px;
  margin: 40px auto;
  padding: 0 20px;
}

.section {
  margin-bottom: 60px;
}

.section h2 {
  font-size: 2em;
  margin-bottom: 20px;
  color: #2c3e50;
  border-bottom: 2px solid #3498db;
  display: inline-block;
  padding-bottom: 5px;
}

.profile-img {
  width: 200px;
  height: 200px;
  border-radius: 50%;
  object-fit: cover;
  border: 4px solid #3498db;
  margin-bottom: 20px;
  transition: transform 0.3s, box-shadow 0.3s;
}
.profile-img:hover {
  transform: scale(1.05);
  box-shadow: 0 4px 15px rgba(0,0,0,0.2);
}

/* About Section */
.about {
  font-size: 1.1em;
  line-height: 1.6;
  text-align: center;
  max-width: 800px;
  margin: 0 auto;
  padding: 20px;
  background-color: #ffffff;
  border-radius: 10px;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

/* Projects / Websites */
.websites {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.website-card {
  background-color: #ecf0f1;
  border-radius: 8px;
  padding: 15px;
  flex: 1 1 250px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
  transition: transform 0.3s, box-shadow 0.3s;
}

.website-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 8px 20px rgba(0,0,0,0.2);
}

.website-card h3 {
  margin-bottom: 10px;
  color: #2c3e50;
}

.website-card a {
  color: #2980b9;
  text-decoration: none;
  font-weight: 600;
}

.website-card a:hover {
  text-decoration: underline;
}

/* Contact Section */
.contact-info {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: 1.2em;
  padding: 20px;
  background-color: #ffffff;
  border-radius: 10px;
  max-width: 600px;
  margin: 0 auto;
  box-shadow: 0 4px 15px rgba(0,0,0,0.1);
}

.contact-info p {
  margin: 10px 0;
  display: flex;
  align-items: center;
  gap: 10px;
}

a.contact-link {
  color: #2980b9;
  text-decoration: none;
  word-break: break-all;
}

a.contact-link:hover {
  text-decoration: underline;
}

/* Footer */
footer {
  background-color: #2c3e50;
  color: #ecf0f1;
  text-align: center;
  padding: 15px 10px;
  margin-top: 50px;
}

button {
  background-color: #3498db;
  color: #fff;
  border: none;
  padding: 12px 25px;
  border-radius: 5px;
  cursor: pointer;
  font-size: 1em;
  margin-top: 20px;
  transition: background-color 0.3s;
}

button:hover {
  background-color: #2980b9;
}

/* Smooth Scroll */
html {
  scroll-behavior: smooth;
}
</style>
</head>
<body>

<header>
  <h1>Olajide Adebayo Frank</h1>
  <p>Webmaster | Cloud Security Engineer | Pen Tester | M.sc Public Health</p>
  <nav>
    <a href="#about">About</a>
    <a href="#websites">Websites</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<main class="main">

  <!-- About Section -->
  <section id="about" class="section">
    <h2>About Me</h2>
    <img src="image.png" alt="Olajide Adebayo Frank" class="profile-img" />
    <div class="about">
      <p>
        Hello! I'm <strong>Olajide Adebayo Frank</strong>, a passionate Webmaster, Cloud Security Engineer, and Penetration Tester with a solid background in Public Health, holding a Master's degree in the field. I specialize in creating secure, efficient, and innovative digital solutions. I love exploring the intersection of health and technology, and I am dedicated to enhancing cybersecurity and web development practices.
      </p>
      <p>
        Feel free to explore my showcased projects and websites below. Whether you're interested in my cybersecurity expertise, web development, or public health insights, I aim to provide value and innovative solutions.
      </p>
    </div>
  </section>

  <!-- Websites / Projects -->
  <section id="websites" class="section">
    <h2>My Websites & Projects</h2>
    <div class="websites">
      <div class="website-card">
        <h3>Chizykleen</h3>
        <a href="https://chizykleen.com.ng" target="_blank" rel="noopener noreferrer">Visit Website</a>
      </div>
      <div class="website-card">
        <h3>Sofco Homes</h3>
        <a href="https://sofcohomes.com" target="_blank" rel="noopener noreferrer">Visit Website</a>
      </div>
      <div class="website-card">
        <h3>Primal Nail Studio</h3>
        <a href="https://primalnailstudio.com" target="_blank" rel="noopener noreferrer">Visit Website</a>
      </div>
      <div class="website-card">
        <h3>Verdant Photo Studio</h3>
        <a href="https://verdantphotostudio.com" target="_blank" rel="noopener noreferrer">Visit Website</a>
      </div>
      <div class="website-card">
        <h3>CodeHaven Academy</h3>
        <a href="https://codehavenacademy.com" target="_blank" rel="noopener noreferrer">Visit Website</a>
      </div>
      <div class="website-card">
        <h3>Teprim</h3>
        <a href="https://teprim.com" target="_blank" rel="noopener noreferrer">Visit Website</a>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="section">
    <h2>Contact Me</h2>
    <div class="contact-info">
      <p><strong>Phone:</strong> +2347062649450</p>
      <p><strong>Email:</strong> <a class="contact-link" href="mailto:olajideadebayo93@gmail.com">olajideadebayo93@gmail.com</a></p>
      <p><strong>GitHub:</strong> <a class="contact-link" href="https://github.com/Olajide-Adebayo-Frank" target="_blank" rel="noopener noreferrer">View Cybersecurity Projects</a></p>
    </div>
  </section>

</main>

<footer>
  <p>&copy; 2024 Olajide Adebayo Frank. All rights reserved.</p>
</footer>

<script>
  // Optional: Add some interactivity if needed
  // For example, a button to scroll to top
  // But for now, the smooth scrolling via CSS is enough
</script>

</body>
</html>
