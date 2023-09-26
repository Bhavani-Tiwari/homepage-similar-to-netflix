# homepage-similar-to-netflix
A webpage that is similar to Netflix homepage 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Netflix Clone</title>
</head>
<body>
    <header>
        <!-- Navigation bar -->
        <nav>
            <img src="netflix-logo.png" alt="Netflix Logo">
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">TV Shows</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">New & Popular</a></li>
                <li><a href="#">My List</a></li>
            </ul>
        </nav>

        <!-- Hero Section -->
        <div class="hero">
            <h1>Unlimited movies, TV shows, and more.</h1>
            <p>Watch anywhere. Cancel anytime.</p>
            <button>Watch Free For 30 Days</button>
        </div>
    </header>
    <!-- Content Section (Example: Movie Categories) -->
    <section class="content">
        <h2>Popular Movies</h2>
        <div class="movies">
            <!-- Movie Cards Go Here -->
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 Netflix Clone</p>
    </footer>
</body>
</html>


/* Reset some default styles for better alignment */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
}

/* Header Styles */
header {
    background: url('netflix-bg.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 0;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav ul li:last-child {
    margin-right: 0;
}

nav a {
    text-decoration: none;
    color: #fff;
    font-weight: bold;
}

/* Hero Section Styles */
.hero {
    max-width: 800px;
    margin: 0 auto;
}

.hero h1 {
    font-size: 3rem;
    margin-bottom: 20px;
}

.hero p {
    font-size: 1.5rem;
    margin-bottom: 20px;
}

button {
    padding: 15px 30px;
    background-color: #e50914;
    color: #fff;
    font-weight: bold;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

/* Content Section Styles (customize as needed) */
.content {
    padding: 40px;
}

h2 {
    font-size: 2rem;
    margin-bottom: 20px;
}

/* Footer Styles */
footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: #fff;
}

