# Jayden Mai's Portfolio

This is a personal portfolio website showcasing games programmed by Jayden Mai. The site features an about section, a list of game projects with links, and contact information. It uses a sleek dark theme with interactive card hover effects and a fade-in animation on page load.

---

## Project Structure

### 1. HTML

The HTML file defines the structure of the portfolio, divided into three main sections:

- **About Me:** A brief personal introduction.
- **Games I Program:** Cards linking to interactive game projects hosted on CodePen.
- **Contact Info:** Email contact details.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Portfolio</title>
  <!-- CSS will be linked or included here -->
</head>
<body>
  <div class="container">
    <h1>🎮 Jayden Mai's Portfolio</h1>

    <section class="about">
      <h2>About Me</h2>
      <p>Hey there! My name is Jayden Mai, I am a senior in Mt Eden High School, I live in Hayward and I'm currently 17 years old. I am a 3x sport athlete and will be attending Chabot College next year. I will also possibly attend the Air Force the following year.</p>
    </section>

    <section class="projects">
      <h2>Games I Program</h2>
      <div class="project-cards">
        <div class="card">
          <a href="https://codepen.io/asian-Kid/pen/OPJObNB" target="_blank" class="title">Guess the Number</a>
          <p>Try to guess the secret number. The game gives you hints — too high or too low — until you get it right!</p>
        </div>
        <div class="card">
          <a href="https://codepen.io/asian-Kid/pen/azbqbGq" target="_blank" class="title">Fifteen Puzzle</a>
          <p>A classic sliding puzzle where you arrange numbers 1–15 into the correct order. Challenge your logic and speed!</p>
        </div>
        <div class="card">
          <a href="https://codepen.io/asian-Kid/pen/gbOjXyv" target="_blank" class="title">Tic-Tac-Toe</a>
          <p>The classic X and O game. Play against a friend and try to get three in a row before your opponent does!</p>
        </div>
        <div class="card">
          <a href="https://codepen.io/asian-Kid/pen/LEEzJzd" target="_blank" class="title">Click Challenge</a>
          <p>Click the button as many times as you can before time runs out. It’s all about speed and timing!</p>
        </div>
      </div>
    </section>

    <section class="contact">
      <h2>Contact Info</h2>
      <p>Feel free to contact me through email at <a href="mailto:JaydenMai1234@gmail.com">JaydenMai1234@gmail.com</a></p>
    </section>
  </div>

  <!-- JavaScript will be linked or included here -->

</body>
</html>
