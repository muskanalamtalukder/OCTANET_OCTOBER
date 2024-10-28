# OCTANET_OCTOBER
Creating and Deploying a Landing Page
1. Landing Page (Front Page)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Healthy Recipes</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Healthy Recipes</h1>
    <p>Discover recipes for a healthier life</p>
    <a href="login.html" class="cta-button">Get Started</a>
  </header>

  <section class="featured">
    <h2>Featured Recipes</h2>
    <div class="recipe-grid">
      <div class="recipe-card">
        <img src="recipe1.jpg" alt="Avocado Toast">
        <p>Avocado Toast</p>
      </div>
      <!-- More recipes here -->
    </div>
  </section>
</body>
</html>
2. Login Page

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Login - Healthy Recipes</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="login-container">
    <h2>Login</h2>
    <form action="dashboard.html">
      <label for="username">Username</label>
      <input type="text" id="username" name="username" required>
      <label for="password">Password</label>
      <input type="password" id="password" name="password" required>
      <button type="submit">Login</button>
    </form>
  </div>
</body>
</html>
3. Dashboard

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dashboard - Healthy Recipes</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <header>
    <h1>Welcome, [User]!</h1>
  </header>
  
  <section class="trending">
    <h2>Trending Recipes</h2>
    <div class="recipe-grid">
      <div class="recipe-card">Recipe #1</div>
      <!-- More recipes -->
    </div>
  </section>

  <div class="search-box">
    <input type="text" placeholder="Search for recipes...">
    <button>Search</button>
  </div>
</body>
</html>
4. Recipes Page

<section class="recipes">
  <h2>All Recipes</h2>
  <div class="recipe-grid">
    <div class="recipe-card">
      <img src="recipe1.jpg" alt="Recipe 1">
      <p>Recipe Name</p>
      <button class="add-to-cart">Add to Cart</button>
    </div>
    <!-- Repeat for more recipes -->
  </div>
</section>
5. Trending Section

<div class="trending">
  <h2>Trending</h2>
  <div class="recipe-grid">
    <div class="recipe-card">
      <img src="recipe2.jpg" alt="Trending Recipe">
      <p>Recipe Name</p>
    </div>
    <!-- More trending recipes -->
  </div>
</div>
6. Search Box

<div class="search-box">
  <input type="text" id="search" placeholder="Search for recipes...">
  <button onclick="searchRecipe()">Search</button>
</div>
<script>
function searchRecipe() {
  let searchTerm = document.getElementById('search').value;
  alert("Searching for: " + searchTerm);
}
</script>
7. Profile Details Page

<section class="profile">
  <h2>Your Profile</h2>
  <p><strong>Username:</strong> [User]</p>
  <p><strong>Email:</strong> user@example.com</p>
  <div class="favorites">
    <h3>Your Favorite Recipes</h3>
    <div class="recipe-grid">
      <!-- List of favorited recipes -->
    </div>
  </div>
</section>
8. Add to Cart Functionality

<script>
function addToCart(recipeName) {
  alert(recipeName + " has been added to your cart!");
}
</script>
<button onclick="addToCart('Recipe Name')">Add to Cart</button>
