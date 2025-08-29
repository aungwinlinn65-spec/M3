<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Manga Library</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
    }
    header {
      background: #222;
      color: white;
      padding: 15px;
      text-align: center;
    }
    .search-box {
      text-align: center;
      margin: 20px;
    }
    input {
      padding: 10px;
      width: 300px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(180px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
      text-align: center;
    }
    .card img {
      width: 100%;
      height: auto;
    }
    .card h3 {
      margin: 10px;
    }
    .chapter-list {
      padding: 20px;
    }
    .chapter-list a {
      display: block;
      margin: 5px 0;
      padding: 10px;
      background: #eee;
      text-decoration: none;
      color: #333;
      border-radius: 5px;
    }
    .chapter-list a:hover {
      background: #ddd;
    }
  </style>
</head>
<body>

  <header>
    <h1>📚 Manga Library</h1>
  </header>

  <div class="search-box">
    <input type="text" id="search" placeholder="Search manga...">
  </div>

  <div class="grid" id="manga-list">
    <!-- Example Manga -->
    <div class="card">
      <a href="manga1.html">
        <img src="https://placehold.co/200x300" alt="Manga Cover">
        <h3>Love in Spring</h3>
      </a>
    </div>
    <div class="card">
      <a href="manga2.html">
        <img src="https://placehold.co/200x300" alt="Manga Cover">
        <h3>Shadow Hunter</h3>
      </a>
    </div>
  </div>

</body>
</html>