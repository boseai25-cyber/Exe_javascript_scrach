5a. Create a <script> element. Inside the <script>, create a variable called 'name', and save your name in this variable (as a string).

5b. Continuing from 5a, display the message 'My name is: ${name}' in the console (insert the 'name' variable created in 5a into this message).

5c. At a restaurant, you order 1 coffee ($5), 2 bagels ($3 each), and 1 soup ($9). Calculate the cost and save it in a variable called 'cost'.

5d. Continuing from 5c, display 'Cost of food: $${cost}' in the console.

5e. Let's say the restaurant charges a 10% tax. Using the 'cost' variable from 5c, calculate the tax (hint: multiply by 0.1), and save the result in a variable.

5f. Continuing from 5e, display 'Tax (10%): $$(tax}' in the console.

5g. Continuing from 5f, calculate the total (cost + tax), save it in a variable called 'totalCost', and display the message 'Total cost: $${totalCost)' in the console.

5h. In the Cart Quantity project, add 2 more buttons '+4' and '+5', which increase the quantity by 4 and 5 when you click them. Try using +=

5i. In the Cart Quantity project, add a button 'Remove from cart', which decreases the cart quantity by 1.

5j. Add 2 buttons '-2' and '-3', which decrease the quantity by 2 and 3.

5k. Use the shortcuts -- and -= in 5i and 5j.

51. Add the HTML structure (<!DOCTYPE html>, <html>, <head>, <body>).Add a <title> with the text 'Calculator'

5m. Create these 5 buttons:1 2 3 + =

5n. Create a <script>, create a variable called 'calculation', and save an empty string inside: let calculation = '';(This variable will store the calculation like '1 + 2' or '11 + 2 + 2')

50. When we click the 'l' button:
Add the string '1' to the calculation variable: calculation += '1';
Display the calculation in the console: console.log(calculation);

5p. Do the same for the '2', '3', and '+' buttons (add ' + ' instead of '+').

5q. When we click the '=' button, use the code: eval(calculation); (eval(...) converts the calculation string into actual math)
Save the result back in 'calculation': calculation = eval(calculation);
Display the result in the console: console.log(calculation);

5r. Create the rest of the buttons in the calculator. To create multiple rows of buttons, put the buttons inside <p> elements like this:
