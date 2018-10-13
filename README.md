Problems: 
* We want a grocery list from all of the ingredients on http://www.eatingwell.com/article/288729/7-day-vegetarian-meal-plan-1200-calories/ 
* There are linked recipes, so we want to get the ingredients for those as well
* The linked URLs are not formatted in the same way, with bullets before each ingredient 
* Recipes have a list item structure, meal plan page does not
* Need a way to seperate instructions from ingredients
* EVERYTHING IS TERRIBLE

Requirements:
* Match like ingredients and add quantities together. Some are whole numbers and some are fractions
* Output one full list

Build requirements:
1. Python 3.6
2. Packages, installed with pip3:
 * requests
 * BeautifulSoup4

Notes:
* The *.txt files are from manipulating the data with bash
