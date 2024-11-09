<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Streaming Service</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #141414;
            color: white;
        }
        header {
            background-color: #e50914;
            padding: 20px;
            text-align: center;
        }
        h1 {
            margin: 0;
        }
        nav {
            margin: 20px 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
        }
        .featured {
            display: flex;
            overflow-x: auto;
            padding: 20px;
        }
        .movie {
            min-width: 200px;
            margin-right: 15px;
            border-radius: 5px;
            overflow: hidden;
            position: relative;
        }
        .movie img {
            width: 100%;
            border-radius: 5px;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background-color: #222;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>My Streaming Service</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">TV Shows</a>
        <a href="#">Movies</a>
        <a href="#">My List</a>
    </nav>
</header>

<main>
    <h2>Featured Movies & Shows</h2>
    <div class="featured">
        <div class="movie">
            <img src="https://via.placeholder.com/200x300?text=Movie+1" alt="Movie 1">
        </div>
        <div class="movie">
            <img src="https://via.placeholder.com/200x300?text=Movie+2" alt="Movie 2">
        </div>
        <div class="movie">
            <img src="https://via.placeholder.com/200x300?text=Movie+3" alt="Movie 3">
        </div>
        <div class="movie">
            <img src="https://via.placeholder.com/200x300?text=Movie+4" alt="Movie 4">
        </div>
        <div class="movie">
            <img src="https://via.placeholder.com/200x300?text=Movie+5" alt="Movie 5">
        </div>
    </div>
</main>

<footer class="footer">
    <p>&copy; 2023 My Streaming Service</p>
</footer>

</body>
</html>
