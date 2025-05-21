# Flexbox-CSS-Grid-Puzzle-Assignment.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Puzzle Assignment</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="grid-container">

    <!-- Section 1: Student info and puzzle choice -->
    <header class="section header">
      <h1>Your Name: Jane Doe</h1>
      <p>Chosen Puzzle: Butterflies</p>
    </header>

    <!-- Section 2: Puzzle Assembled with Flexbox -->
    <section class="section puzzle">
      <h2>Flex Puzzle Pieced Together</h2>
      <div class="flex-container">
        <img src="images/piece1.jpg" alt="Piece 1">
        <img src="images/piece2.jpg" alt="Piece 2">
        <img src="images/piece3.jpg" alt="Piece 3">
        <img src="images/piece4.jpg" alt="Piece 4">
        <img src="images/piece5.jpg" alt="Piece 5">
        <img src="images/piece6.jpg" alt="Piece 6">
        <img src="images/piece7.jpg" alt="Piece 7">
        <img src="images/piece8.jpg" alt="Piece 8">
        <img src="images/bad-piece.jpg" alt="Faulty Piece" class="hidden">
      </div>
    </section>

    <!-- Section 3: Explanation -->
    <section class="section explanation">
      <h2>How the Puzzle Was Solved</h2>
      <ul>
        <li>Used <strong>Flexbox</strong> to arrange puzzle pieces in rows with wrapping.</li>
        <li>Used the <code>display: none;</code> property to hide the faulty puzzle piece.</li>
        <li>The puzzle is solved correctly by placing the right pieces in order.</li>
        <li>All puzzle pieces are stored inside the <code>images/</code> folder.</li>
      </ul>
    </section>

    <!-- Section 4: Date -->
    <footer class="section footer">
      <p>Assignment completed on: May 21, 2025</p>
    </footer>

  </div>
</body>
</html>
  

