# CookbookChallenge
6.25.26 1.38pm Catapult Challenge Project #1

## Classroom Specifications
For the Unit 2 Project, only the creation of a landing page was required. In this challenge project, work on creating a webpage with multiple pages.
https://www.theodinproject.com/lessons/foundations-recipes

### Project: Recipes - The Odin Project
It’s time to practice all of the HTML knowledge you have acquired. In this project, you are going to build a basic recipe website.

The website will consist of a main index page which will have links to a few recipes. The website won’t look very pretty by the time you’ve finished but it’s important to keep in mind that the purpose of this project is to build your HTML chops; we will revisit this project in the future to style it up with CSS.

### Assignment
#### Iteration 1: initial structure
* Within the odin-recipes directory, create an index.html file.
* Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.
#### Iteration 2: recipe page
* Create a new directory within the odin-recipes directory and name it recipes.
* Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use at Allrecipes. Be sure to include the usual boilerplate HTML. This boilerplate code should be in every .html file you create.
* For now, just include an h1 heading with the recipe’s name as its content.
* Back in the index.html file, add a link to the recipe page you just created. Example: Under the Odin Recipes heading, write out the link like so: href="recipes/recipename.html" "Recipe Title". The text of the link should again be the recipe name.
* Add a link back to the index page on your recipe page for easier navigation. You can place this link at the top or bottom of your recipe page (e.g., lasagna.html).
    * This allows users to quickly return to the home page after viewing the recipe.
#### Iteration 3: recipe page content
Your new recipe page should have the following content:
* A free image of the finished dish under the h1 heading that you added earlier.
* Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.
* Under the description, add an “Ingredients” heading followed by an unordered list of the ingredients needed for the recipe.
* Finally, under the ingredients list, add a “Steps” heading followed by an ordered list of the steps needed for making the dish.
#### Iteration 4: add more recipes
* Add two more recipes with identical page structures to the recipe page you’ve already created.
* Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.
    * Your links won’t be flashy, but for now, just focus on building them out.

### Viewing your project on the web
If you want to show your work (the project) to others, or submit a solution below, you will need to publish your site so that others can access it from the web, rather than just on your local machine. The good news is that if you have your project on GitHub (as described above), doing this is straightforward.

GitHub allows you to publish web projects directly from a GitHub repository. Doing this will allow you to access your project from your-github-username.github.io/your-github-repo-name.
Publishing from private repositories

A GitHub paid account is required to publish web projects from a private repository. Free accounts can only publish from public repositories.

There are a couple of ways to go about doing this, but the simplest is this:
* Ensure your main HTML file is named index.html and is located in the root (top-level) directory of your repository.
* Go to your GitHub repo on the web and click the Settings button as shown in the screenshot below. Screenshot pointing to the Settings located in an example repository
* Click on Pages on the left side bar.
* Change the Branch from none to main branch and click Save.
* It may take a few minutes (The GitHub website says up to 10, but we’ve seen it take up to an hour. Do not add a “theme” to your project, or you may have git conflicts, instead, be patient.) but your project should be accessible over the web from your-github-username.github.io/your-github-repo-name (obviously substituting your own details in the link).
* If your project does not publish after 1 hour, ensure that you have a file called index.html in the root of your repository and all the settings have been set correctly. Go to your repo on GitHub and click on Actions, if there are no entries, then go back to the settings, change the Branch from main branch to none and click Save, then change the Branch from none to main branch and click Save.
