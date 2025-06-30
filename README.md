# LetsCODE
Code 

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Odin Recipes</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
      background-color: #f9f9f9;
    }
    h1 {
      color: #2c3e50;
      text-align: center;
      font-size: 2.5em;
    }
    h2 {
      color: #34495e;
      margin: 10px 0;
      cursor: pointer;
      padding: 10px;
      border-radius: 5px;
      transition: background-color 0.3s;
    }
    h2:hover {
      background-color: #ecf0f1;
    }
    .main-recipe h2 {
      background-color: #e8f4f8;
      border: 2px solid #2980b9;
      border-radius: 5px;
    }
    .recipe, .main-recipe {
      margin-bottom: 20px;
    }
    .recipe-content {
      display: none;
      padding: 10px;
    }
    .recipe-content.show {
      display: block;
    }
    .main-recipe {
      background-color: #e8f4f8;
      border: 2px solid #2980b9;
      padding: 10px;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    h3 {
      color: #34495e;
      margin-top: 15px;
    }
    ul, ol {
      margin: 10px 0;
      padding-left: 20px;
    }
    li {
      margin: 5px 0;
    }
  </style>
</head>
<body>
  <h1>Odin Recipes</h1>

  <div class="main-recipe" id="lasagna">
    <h2>Lasagna (Main Recipe)</h2>
    <div class="recipe-content">
      <h3>Ingredients</h3>
      <ul>
        <li>1 lb ground beef</li>
        <li>1 onion, chopped</li>
        <li>2 cloves garlic, minced</li>
        <li>1 (28 oz) can crushed tomatoes</li>
        <li>2 (6 oz) cans tomato paste</li>
        <li>1 (15 oz) can tomato sauce</li>
        <li>1/2 cup water</li>
        <li>2 tbsp sugar</li>
        <li>1 tbsp dried basil</li>
        <li>1 tsp Italian seasoning</li>
        <li>1 tsp salt</li>
        <li>1/4 tsp black pepper</li>
        <li>12 lasagna noodles</li>
        <li>15 oz ricotta cheese</li>
        <li>1 egg</li>
        <li>3 cups shredded mozzarella cheese</li>
        <li>3/4 cup grated Parmesan cheese</li>
      </ul>
      <h3>Instructions</h3>
      <ol>
        <li>Preheat oven to 375°F (190°C).</li>
        <li>In a large skillet, cook ground beef, onion, and garlic over medium heat until beef is browned. Drain excess fat.</li>
        <li>Stir in crushed tomatoes, tomato paste, tomato sauce, and water. Add sugar, basil, Italian seasoning, salt, and pepper. Simmer for 30 minutes, stirring occasionally.</li>
        <li>Cook lasagna noodles in boiling water for 8-10 minutes until al dente. Drain and set aside.</li>
        <li>In a bowl, mix ricotta cheese with egg and a pinch of salt.</li>
        <li>In a 9x13 inch baking dish, spread a layer of meat sauce. Arrange 4 noodles over the sauce, then spread a layer of ricotta mixture, followed by mozzarella. Repeat layers, ending with meat sauce and topping with Parmesan and remaining mozzarella.</li>
        <li>Cover with foil and bake for 25 minutes. Remove foil and bake for an additional 10-15 minutes until cheese is bubbly and golden.</li>
        <li>Let stand for 10 minutes before serving.</li>
      </ol>
    </div>
  </div>

  <div class="recipe" id="indian-curry">
    <h2>Indian Curry (Chicken Tikka Masala)</h2>
    <div class="recipe-content">
      <h3>Ingredients</h3>
      <ul>
        <li>1 lb boneless chicken breast, cubed</li>
        <li>1 cup plain yogurt</li>
        <li>2 tbsp lemon juice</li>
        <li>2 tsp ground cumin</li>
        <li>1 tsp ground coriander</li>
        <li>1 tsp paprika</li>
        <li>1 tsp turmeric</li>
        <li>1 tsp garam masala</li>
        <li>1/2 tsp cayenne pepper</li>
        <li>1 tbsp ginger, grated</li>
        <li>2 cloves garlic, minced</li>
        <li>2 tbsp vegetable oil</li>
        <li>1 onion, finely chopped</li>
        <li>1 (14 oz) can crushed tomatoes</li>
        <li>1 cup heavy cream</li>
        <li>1/4 cup fresh cilantro, chopped</li>
        <li>Salt to taste</li>
      </ul>
      <h3>Instructions</h3>
      <ol>
        <li>In a bowl, mix yogurt, lemon juice, cumin, coriander, paprika, turmeric, garam masala, cayenne, ginger, and garlic. Add chicken cubes, coat well, and marinate for at least 1 hour in the refrigerator.</li>
        <li>Heat oil in a large skillet over medium heat. Add onion and cook until soft and golden, about 5-7 minutes.</li>
        <li>Add marinated chicken (discard excess marinade) and cook until browned, about 5 minutes.</li>
        <li>Stir in crushed tomatoes and simmer for 15 minutes, stirring occasionally.</li>
        <li>Add heavy cream and simmer for another 5-10 minutes until sauce thickens. Adjust salt to taste.</li>
        <li>Garnish with fresh cilantro and serve with rice or naan.</li>
      </ol>
    </div>
  </div>

  <div class="recipe" id="chicken-pot-pie">
    <h2>Chicken Pot Pie</h2>
    <div class="recipe-content">
      <h3>Ingredients</h3>
      <ul>
        <li>1 lb boneless chicken breast, cooked and shredded</li>
        <li>1/3 cup butter</li>
        <li>1/3 cup all-purpose flour</li>
        <li>1/2 cup chopped onion</li>
        <li>1/2 tsp salt</li>
        <li>1/4 tsp black pepper</li>
        <li>1 3/4 cups chicken broth</li>
        <li>2/3 cup milk</li>
        <li>2 cups mixed vegetables (carrots, peas, corn)</li>
        <li>2 (9-inch) unbaked pie crusts</li>
      </ul>
      <h3>Instructions</h3>
      <ol>
        <li>Preheat oven to 425°F (220°C).</li>
        <li>In a saucepan, melt butter over medium heat. Add onion and cook until soft, about 5 minutes.</li>
        <li>Stir in flour, salt, and pepper to form a paste. Gradually whisk in chicken broth and milk. Cook, stirring constantly, until thickened, about 5-7 minutes.</li>
        <li>Add shredded chicken and mixed vegetables to the sauce. Remove from heat.</li>
        <li>Place one pie crust in a 9-inch pie dish. Pour the chicken mixture into the crust.</li>
        <li>Cover with the second pie crust, seal the edges, and cut small slits in the top for ventilation.</li>
        <li>Bake for 30-35 minutes until the crust is golden brown. Let cool for 10 minutes before serving.</li>
      </ol>
    </div>
  </div>

  <script>
    document.querySelectorAll('h2').forEach(header => {
      header.addEventListener('click', () => {
        const content = header.nextElementSibling;
        content.classList.toggle('show');
        console.log(`Toggled ${header.textContent} section`);
      });
    });
  </script>
</body>
</html>
