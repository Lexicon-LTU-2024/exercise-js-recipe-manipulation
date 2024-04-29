## Exercises on DOM Manipulation Part 1

### Getting data from the DOM. 

#### In this exercise you will try and get some data from the provided recipe website. Fire up the index.html on your live server.

Use the appropriate methods and properties available to you to get the correct data from the "correct" recipe. All answers should be saved in some variable and logged to the console. If you don't know the right method or property to use, see this link for all available ones: https://www.w3schools.com/jsref/dom_obj_all.asp

1. What is the name of the recipe?
2. What HTML tag is used to display the Recipe name?
3. What is the font size of the paragraph tag with the class _"description"_.
4. What is the value of the `alt` atrribute on the image?
5. What is the dimensions and the url of the image? Create an object that looks like this, and log it to the console:

```js
{
  url: string
  height: number,
  width: number,
}
```

6. How many ingredients has the paste?
7. Which is the forth element in the list containing the ingredients for the paste?
8. Create an an array of objects from the instructions. Each element in the array should be an object that looks like this:

```js
{
  order: number;
  text: instruction;
}
```

## Exercises in DOM manipulation Part 2

In this exercise you will be using the same pre-built webside. What's special about this website is that it comes in two versions. One which is the "correct" one and one that has many "errors" in it. Your task is to correct these errors with the aid of JavaScript. All of the right answers, styling, formatting and texts can be found in the correct version of the site. So there is your reference so to speak.

Each question in the following list of questions aims at a specific error on the website, and it goes from top to bottom and left to right on the website.

The solution to all these question can be reached by using the different DOM manipulation methods and properties that you might have or might not have learned during the course. Some googling might be required. This link might help you:
https://www.w3schools.com/jsref/dom_obj_all.asp

1. The logo text of the site has the wrong color. Change it to the correct one.
2. The alignment of the elements inside the header element are wrong. Change it to the correct one. `Hint`, check the flex properties for the correct alignment. Here is a link that might help:
https://css-tricks.com/snippets/css/a-guide-to-flexbox/
3. The header has a border at the bottom, but it has the wrong color. Change it do the correct one.
4. The recipe name is wrong, change it to the correct one.
5. The clock icon beneath the recipe name has disappeared and been replaced by a text instead. This can be fixed by adding a class to that element.
6. The estimated time of the recipe is also incorrect. Change it to the correct time estimation.
7. The src path to the image is wrong, or atleast it's showing the wrong image. Change it to the correct one. The available images can be found in the assets folder.
8. The background color of the ingredients list container is wrong. Fix it.
9. The ingredients are divided in to two parts, one for the bottom and one for the paste. In the list of the ingredients to the bottom, there is a text instead of two list items. Remove the text and add those two list items.
10. The third ingredient in the list of ingredients to the paste is wrong. Change that specific ingredient to the correct one.
11. There is also a missing ingredient in the list of ingredients to the paste. Look and see what it is and add that one the the end of the list.
12. The text "Instructions" to the left, beneath the image, has some shadow styling applied to it. Remove that styling.
13. Two list elements of the list of instructions are incorrect. Find them and change them to the correct ones.
