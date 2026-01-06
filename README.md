[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22139691)
# 7-2-JS-More-on-Variables

## Video

[Video](https://youtu.be/wrtJ-KI6lL0) <-- Make sure to watch this video first

## Directions

### Step #1 - A mouth! <br>

Our frog has no mouth! Use the ellipse function to draw a wide mouth on the frog's face, centering the mouth at the same `x` and `y` as the face. Make it big enough to eat a lot of flies!
<br>

### Step #2 - Draw eyes <br>

The frog already has eyeballs, but no pupils. How will he find the tasty flies if he can't see them?? Draw them using two rectangles, and use the `x` and `y` coordinates to position them inside the eyeballs (adding or subtracting as necessary).
<br><br>
Hint: Take a look at the code for the eyeballs and do something similar to position the pupils.
<br>

### Step #3 - Play! <br>

Add more code to the pde - variables, shapes, colors, etc.

# Extras

### Move Frog with Cursor

Check to see if your `x` and `y` variables work by adding this line of code to end of the `draw()` function.

`x = mouseX;`<br>
`y = mouseY;`

Now when you run your mouse over the canvas the frog should follow your cursor.

### Randomly Color Frog

Try adding these variables outside of the `draw()` function

`var randRed = random(0,255);`<br>
`var randGreen = random(0,255);`<br>
`var randBlue = random(0,255);`

Inside of the draw() add this line

`fill (randRed, randGreen, randBlue);`
