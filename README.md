```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Netflix Homepage</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <img src="netflix_logo.png" alt="Netflix Logo">
    </div>
    <nav>
      <ul>
        <li><a href="#">Home</a></li>
        <li><a href="#">TV Shows</a></li>
        <li><a href="#">Movies</a></li>
        <li><a href="#">New & Popular</a></li>
        <li><a href="#">My List</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section class="hero">
      <h1>Welcome to Netflix</h1>
      <p>Unlimited movies, TV shows, and more.</p>
      <button>Sign In</button>
    </section>

    <section class="categories">
      <h2>Browse by Category</h2>
      <div class="category">
        <img src="category_image_1.jpg" alt="Category 1">
        <h3>Category 1</h3>
      </div>
      <div class="category">
        <img src="category_image_2.jpg" alt="Category 2">
        <h3>Category 2</h3>
      </div>
      <!-- Add more categories as needed -->
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Netflix</p>
  </footer>
</body>
</html>
```

And the accompanying CSS (styles.css):

```css
/* Resetting default browser styles */
body, h1, h2, h3, p, ul, li {
  margin: 0;
  padding: 0;
}

/* Basic styling */
body {
  font-family: Arial, sans-serif;
}

header {
  background-color: #111;
  color: #fff;
  padding: 20px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.logo img {
  height: 40px;
}

nav ul {
  list-style: none;
}

nav ul li {
  display: inline;
  margin-right: 20px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

main {
  padding: 20px;
}

.hero {
  text-align: center;
  margin-bottom: 40px;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 20px;
}

.hero button {
  background-color: red;
  color: #fff;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  font-size: 1rem;
  cursor: pointer;
}

.categories {
  text-align: center;
}

.category {
  margin-bottom: 20px;
}

.category img {
  width: 200px;
  height: 300px;
  margin-bottom: 10px;
}

footer {
  background-color: #111;
  color: #fff;
  text-align: center;
  padding: 10px;
}
```
