<!DOCTYPE html>
<html lang='en'>
<head>
  <meta charset="UTF-8">
  <title>lasagna</title>
  <link rel="icon" href="/recipe/thumbnails/recipe-icon.jpg">
  <link rel="stylesheet" href="/recipe/styles/recipe.css">
  <link href="https://fonts.googleapis.com/css2?family=Shadows+Into+Light&display=swap" rel="stylesheet">
  <style>
    html {
  font-family: "Shadows Into Light", Cursive;
  }
  .heading-title {
    font-size:50px;
    margin: 20px 0px 20px 40px;
    color: rgb(51, 51, 51);
    font-weight: 600;
  }
  .heading-subtitle {
    font-size:20px;
    margin: 20px 0px 20px 40px;
    width:700px;
    color: rgb(118, 118, 119);
  }
  h2 {
    font-size:20px;
    margin: 20px 0px 20px 40px;
    width:700px;
    color: #333333;
  }
  .ingredient-list-heading {
    font-size:16px;
    margin: 20px 0px 20px 40px;
    font-weight: 700;
    color: #333333;
  }
  .nutrition-info__heading-aside {
    font-size: 14px;
    font-weight: 400;
  }
  ul {
    color: green;
  }
  li {
    margin: 10px 10px 10px 10px;
    color: rgb(51, 51, 51);
    width: 30%;
  }
  .img-lasagna {
    font-size:16px;
    margin: 20px 0px 0px 40px;
  }
  .recipe-details_table {
    width:30%;
  }
  .recipe-details_table, .recipe-details_table-cell, .recipe-details_table-row {
    margin: 20px 0px 20px 40px;
    border:2px solid black;
    border-collapse: collapse;
  }
  .recipe-details_thead {
    background-color: #ff592f;
  }
  .container {
    display: flex;
    margin-left: 24px;
    margin-top: 12.8px;
    margin-right: 32px;
    margin-bottom: 20px;
    line-height: 18px;
    max-width: 700px;
    width: 100%;
  }
  .wrapper {
    margin: 0 auto;
  }
  p {
    margin-left: 14px;
  }
  .box-1 {
    width: 80px;
    height: 40px;
    font-size: 15px;
  }
  .box-2 {
    width: 120px;
    height: 41px;
  }
  .box-3 {
    width: 80px;
    height: 43px;
  }
  .box-4 {
    width: 115px;
    height: 40px;
  }
  .box-5 {
    width: 90px;
    height: 41px;
  }
  .table-lasagna {
    font-size: 30px;
    font-weight: 800;
    margin-left: 24px;
    margin-top: 17.6px;
    margin-right: 32px;
    margin-bottom: 0px;
  }
  .nutrition-info_table {
    width: 30%;
    margin: 0px 0px 20px 40px;
    border-collapse: collapse;
    border-bottom: #333333 2px solid;
  }
  .nutrition-info_heading:nth-child(1) {
    border-top: 2px solid black; 
    border-bottom: 2px solid black;
  }
  .nutrition-info_table-row1 {
    margin-top: 6px;
  }
  .container1 {
    display: flex;
    margin-left: 50px;
    margin-top: 20px;
    margin-right: 0px;
    margin-bottom: 20px;
    line-height: 20px;
    }
    .nbox-1 {
      width: 140px;
      height: 40px;
      font-size: 15px;
    }
    .nbox-2 {
      width: 140px;
      height: 41px;
    }
    .nbox-3 {
      width: 140px;
      height: 43px;
    }
    .nbox-4 {
      width: 140px;
      height: 40px;
    }
    @media (max-width: 768px) {
      .container {
        flex-direction: column;
        align-items: flex-start;
      }
      .recipe-details_table, .nutrition-info_table {
        width: 90%;
      }
    }
  </style>
</head>
<body>
<main class="wrapper">
<h1 class="heading-title">
  All-Day Meat Lasagna
</h1>
<p class="heading-subtitle">
  This complex lasagna is time consuming but worth the effort.
</p>
<img class="img-lasagna" src="https://www.seriouseats.com/thmb/cu8UvqAPgO8QgaQc8VHFivM3wz8=/750x0/filters:no_upscale():max_bytes(150000):strip_icc()/__opt__aboutcom__coeus__resources__content_migration__serious_eats__seriouseats.com__recipes__images__2014__07__lasanga-bolognese-f8c8a8171acc4b368d0ad8b8902df7fb.jpg" alt="A large slice of baked meat lasagna with melted cheese" width="" height="450px">
<table class="recipe-details_table">
  <tr class="recipe-details_table-row">
    <th class="recipe-details_thead">RECIPE DETAILS</th>
  </tr>
  <tr class="recipe-details_table-row">
    <td class="recipe-details_table-cell">
      <p class="table-lasagna">
        All-Day Meat Lasagna
      </p>
      <div class="container">
        <div class="box-1">
          Prep<br>20 mins
        </div>
        <div class="box-2">
          Cook<br>4 hrs 50 mins
        </div>
        <div class="box-3">
          Active<br>2 hrs
        </div>
        <div class="box-4">
          Total<br>5hrs 10 mins
        </div>
        <div class="box-5">
          Serves<br>8 servings
        </div>
      </div>
    </td>
  </tr>
</table>
<section class="ingreditents">
<h2>Ingredients</h2>
<p class="ingredient-list-heading">For the Ragù Bolognese:</p>
<ul>
  <li>2 tablespoons extra-virgin olive oil</li>
  <li>4 tablespoons butter</li>
  <li>2/3 pound ground lamb (or 85/15 ground beef)</li>
  <li>2/3 pound ground pork</li>
  <li>2/3 pound ground veal</li>
  <li>4 ounces chicken livers, finely chopped (optional)</li>
  <li>1 large onion, finely chopped (about 1 1/2 cups)</li>
  <li>2 large carrots, peeled, and cut into 1/4-inch dice (about 1 cup)</li>
  <li>3 large ribs celery, peeled, and cut into 1/4-inch dice (about 1 cup)</li>
  <li>4 cloves garlic, finely minced, or grated on a microplane grater</li>
  <li>1/2 cup fresh sage leaves, finely chopped</li>
  <li>Large pinch red pepper flakes (optional)</li>
  <li>1 (28-ounce) can crushed Italian plum tomatoes, preferably D.O.P. San Marzano</li>
  <li>1 1/2 cups dry red wine (white works fine as well)</li>
  <li>1 1/2 cups whole milk</li>
  <li>2 cups homemade chicken or veal stock (or 2 cups low-sodium canned chicken broth)</li>
  <li>2 bay leaves</li>
  <li>1 tablespoon Vietnamese or Thai fish sauce </li>
  <li>1/2 cup heavy cream </li>
  <li>Salt and freshly ground black pepper </li>
  <li>1/2 cup minced basil or parsley (or a mix of both)</li>
</ul>
<p class="ingredient-list-heading">For the Ricotta Mixture:</p>
<ul>
  <li>3 cups whole-milk ricotta (see note)</li>
  <li>Salt and freshly ground black pepper</li>
  <li>2 large eggs </li>
  <li>1/4 cup minced basil or parsley (or a mix of both)</li>
</ul>
<p class="ingredient-list-heading">For the Besciamella:</p>
<ul>
  <li>2 tablespoons butter</li>
  <li>2 tablespoons flour</li>
  <li>2 cloves garlic, finely minced, or grated on a microplane grater</li>
  <li>2 cups whole milk</li>
  <li>1/2 pound low-moisture whole milk mozzarella cheese, grated</li>
  <li>1/4 teaspoon freshly grated nutmeg</li>
  <li>Salt and freshly ground black pepper</li>
</ul>
<p class="ingredient-list-heading">To assemble:</p>
<ul>
  <li>Fifteen 4- by 8-inch sheets fresh rolled pasta, or 15 pieces no-boil lasagna noodles from 1 package (see note)</li>
  <li>4 ounces parmesan, preferably Parmigiano-Reggiano, grated on a microplane grater (about 2 cups)</li>
  <li>2 tablespoons minced basil or parsley (or a mix of both)</li>
</ul>
</section>
<section class="Instructions">
<h2>Instructions</h2>
<ol>
  <li>
    <strong>For the Ragù Bolognese:</strong> Heat butter and olive oil in large Dutch Oven over high heat, stirring occasionally, until butter has stopped foaming. Add lamb, pork, veal, and chicken livers, and cook, breaking up meat with wooden spoon, until no longer pink, 7-10 minutes. Remove from heat, transfer meat to strainer set in large bowl, allow to drain, then transfer drained liquid back to Dutch oven. Add onions, carrots, celery, garlic, sage, and red pepper flakes, and set over medium heat. Cook, stirring frequently, until vegetables are softened, but not browned, about 10 minutes.
  </li>
  <li>
    Return meat to pan, add tomatoes, wine, milk, stock, and bay leaves, and bring to a simmer over high heat. Reduce heat to low, partially cover, and simmer 2 1/2 to 3 hours, stirring occasionally, until liquid is slightly below level of meat, about 2 quarts of sauce total (you may need to add excess stock while cooking if your burner is cooking it too hot). A layer of fat may form on top during cooking, but do not skim it off. After cooking, remove bay leaves, add fish sauce and heavy cream and simmer until fat is emulsified, about 5 minutes. Season to taste with salt and black pepper. Remove from heat and allow to cool at room temperature for 30 minutes. Stir in parsley and basil. Bolognese will keep for up to 1 week in fridge, and will improve with time. Reheat until warm before using in lasagna.
  </li>
  <li>
    While the ragù is simmering, make the ricotta mixture. Place ricotta in bowl of food processor or stand mixer fitted with whisk attachment and process/mix until smooth. Season to taste with salt and pepper. Add two eggs and minced herbs, and process/mix until incoroporated. Set aside at room temperature until ready to use.
  </li>
  <li>
    <strong>Make the Besciamella:</strong> Heat butter in medium saucepan over medium-high heat until foaming subsides, stirring occasionally, about 1 minute. Add flour and stir with whisk until light blond in color and slightly nutty aroma develops, about 1 minute. Add garlic, and stir to combine. Whisking constantly, add milk in steady stream until fully incorporated. Bring to a simmer (mixture should thicken). Remove heat, add cheese and nutmeg, and whisk until fully melted. Whisking constantly, return to a simmer, remove from heat, and season to taste with salt and pepper. Set aside until ready to use.
  </li>
  <li>
    Adjust oven racks to lower middle and lowest positions and preheat oven to 375°F (190°C). If using no-boil lasagna noodles, place them in 13- by 9-inch baking dish and cover with hot tap water (or boiled water) and allow to soak for 10 minutes, changing water once during soaking time. Drain in single layer on clean kitchen towels, or paper towels. Cover with second kitchen towel or paper towels and pat dry.
  </li>
  <li>
    <strong>Assemble:</strong> Add 1/6th of meat ragù (about 1 1/3 cups) to the bottom of baking dish and drizzle with 1/2 cup besciamella. Place 3 sheets of fresh rolled pasta or 3 no-boil noodles on top of sauce (noodles will not quite touch each other; this is okay). Top with 1/6 of meat sauce, 1/2 cup besciamella, 1/3 cup parmesan, and another layer of pasta. Spread 1/2 of ricotta mixture on top of pasta with rubber spatula, top with 1/6 of meat sauce, 1/3 cup parmesan, and a third layer of pasta. Top with 1/6 of meat sauce, 1/2 cup besciamella, 1/3 cup parmesan, and a forth layer of pasta. Spread remaining 1/2 of ricotta mixture on top of noodles with rubber spatula, top with 1/6 of meat sauce, 1/3 cup parmesan, and the fifth and final layer of pasta. Cover with remaining 1/6 of meat sauce, remaining besciamella (about 1 cup), and remaining 2/3 cup parmesan. Baking dish should be very full at this point.
  </li>
  <li>
    Place foil-lined rimmed baking sheet on lower rack to catch drips, then place lasagna on upper rack and bake until edges are starting to crisp, and top is a bubbly, golden brown, about 45 minutes, rotating halfway through baking. Remove from oven and allow to cool at room temperature for 10 minutes. Sprinkle with herbs, and serve.
  </li>
</ol>
</section>
<aside class="nutrition">
<table class="nutrition-info_table">
  <thead>
    <tr>
      <th class="nutrition-info_heading" colspan="4">
      Nutrition Facts
      <span class="nutrition-info__heading-aside">(per serving)</span>
      </th>
    </tr>
  </thead>
  <tbody>
    <tr class="nutrition-info_table-row">
      <td class="nutrition-info_table-cell">
        <div class="container1">
          <div class="nbox-1">
            1062<br>Calories
          </div>
          <div class="nbox-2">
            61g<br>Fat
          </div>
          <div class="nbox-3">
            59g<br>Carbs
          </div>
          <div class="nbox-4">
            60g<br>Protein
          </div>
        </div>
      </td>
    </tr>
  </tbody>
</table>
</aside>
</main>
</body>
</html>
