# Flexbox-CSS-Grid-Puzzle-Assignment.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Puzzle Assignment</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="grid-container">

    <header class="section header">
      <h1>Your Name: Jane Doe</h1>
      <p>Puzzle: Butterflies</p>
    </header>

    <main class="section puzzle-container">
      <h2>Solved Puzzle</h2>
      <div class="flex-puzzle">
        <img src="images/piece1.jpg" alt="piece1">
        <img src="images/piece2.jpg" alt="piece2">
        <img src="images/piece3.jpg" alt="piece3">
        <img src="images/piece4.jpg" alt="piece4">
        <img src="images/piece5.jpg" alt="piece5">
        <img src="images/piece6.jpg" alt="piece6">
        <img src="images/piece7.jpg" alt="piece7">
        <img src="images/piece8.jpg" alt="piece8">
        <img src="images/bad-piece.jpg" alt="bad piece" class="hidden-piece">
      </div>
    </main>

    <footer class="section footer">
      <p>Completed on: May 21, 2025</p>
    </footer>

  </div>
</body>
</html>

body {
  font-family: Arial, sans-serif;
  margin: 0;
  background-color: #f0f0f0;
}

.grid-container {
  display: grid;
  grid-template-areas:
    "header"
    "main"
    "footer";
  gap: 20px;
  padding: 20px;
}

.section {
  background: white;
  padding: 20px;
  border-radius: 10px;
}

.header {
  grid-area: header;
  background-color: #d1ecf1;
}

.puzzle-container {
  grid-area: main;
}

.footer {
  grid-area: footer;
  text-align: center;
  background-color: #d4edda;
}

.flex-puzzle {
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
  margin-top: 10px;
  justify-content: center;
}

.flex-puzzle img {
  width: 100px;
  height: 100px;
  object-fit: cover;
  border: 2px solid #444;
  border-radius: 5px;
}

.hidden-piece {
  display: none;
}
