# webcraft
WebCraft is a curated collection of web development projects, components, and experiments. It showcases responsive design, interactive UI elements, and modern front-end techniques using HTML, CSS, JavaScript, and more. Perfect for learning, building, and crafting beautiful web experiences.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WebCraft</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>WebCraft</h1>
    <p>Crafting beautiful web experiences with HTML, CSS, and JavaScript.</p>
    <button id="cta-button">Learn More</button>
  </header>

  <section class="features">
    <div class="feature-card">
      <h2>Responsive Design</h2>
      <p>Looks great on any device with flexible layouts and fluid elements.</p>
    </div>
    <div class="feature-card">
      <h2>Interactive UI</h2>
      <p>Enhance user experience with dynamic interactions and animations.</p>
    </div>
    <div class="feature-card">
      <h2>Clean Code</h2>
      <p>Built with modular, maintainable, and semantic code practices.</p>
    </div>
  </section>

  <footer>
    <p>© 2025 WebCraft. Made with ❤️ for the web.</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Segoe UI", sans-serif;
  background-color: #f9f9f9;
  color: #333;
  line-height: 1.6;
}

header {
  text-align: center;
  padding: 4rem 2rem;
  background: linear-gradient(135deg, #00b4db, #0083b0);
  color: white;
}

header h1 {
  font-size: 3rem;
  margin-bottom: 1rem;
}

header p {
  font-size: 1.2rem;
  margin-bottom: 2rem;
}

#cta-button {
  background-color: white;
  color: #0083b0;
  border: none;
  padding: 0.8rem 1.5rem;
  font-size: 1rem;
  border-radius: 25px;
  cursor: pointer;
  transition: background 0.3s ease;
}

#cta-button:hover {
  background-color: #e0f7fa;
}

.features {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 2rem;
  padding: 3rem 2rem;
}

.feature-card {
  background-color: white;
  padding: 2rem;
  border-radius: 10px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}

.feature-card h2 {
  color: #0083b0;
  margin-bottom: 1rem;
}

footer {
  text-align: center;
  padding: 2rem;
  background-color: #f0f0f0;
  font-size: 0.9rem;
}

document.getElementById("cta-button").addEventListener("click", () => {
  alert("Thanks for your interest in WebCraft! More features coming soon.");
});
