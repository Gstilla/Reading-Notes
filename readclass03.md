# Class 03 Read

## When should you use an unordered list in your HTML document?
* You should use an unordered list in your HTML document when you want to present a list of items that don't have a specific order or hierarchy.
 For example, a list of bullet points, a list of features, or a list of ingredients.

## How do you change the bullet style of unordered list items?
* To change the bullet style of unordered list items, you can use CSS.
You can select the unordered list using its tag name (ul) or class name (if you've assigned one),
and then use the list-style-type property to set the type of bullet you want.

## Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

** Once upon a time, in the land of HTML, there was a box named Element. Element was a proud and well-respected member of the community, but he often felt incomplete. 
He had four distinct sides: a top, a bottom, a left, and a right, but they were all plain and unadorned.

One day, Element met two other boxes named Margin and Padding. 
Margin was a friendly but aloof character, while Padding was warm and inviting. 
Margin and Padding were fascinated by Element's four sides, and they introduced themselves. Margin explained that he was there to keep Element away from other elements and prevent them from getting too close. Padding, on the other hand, said he was there to provide Element with comfort and support.

Element was intrigued, and Margin and Padding started to show him how they could help.
Margin explained that he could make Element look more prominent by pushing other elements away. 
Padding, in turn, could make Element look more comfortable by giving him some space inside.
Element realized that Margin and Padding could help him feel complete by providing him with the space and distance he needed to stand out.

Margin and Padding were now happy to work with Element, and together they formed the Box Model. 
The Box Model was made up of four parts: Content, Padding, Border, and Margin.
Content was the innermost part of Element, where his text and images lived. 
Padding was the space between Content and Border, where Padding could provide comfort and Margin could provide distance. Border was the visible outline around Element, and Margin was the space between Border and other elements.

In the end, Element was no longer incomplete. Thanks to Margin and Padding, he could stand out and be comfortable in his own skin. And with the Box Model, he had a clear understanding of the four parts of his box and how they could work together to make him look his best.
 So, to summarize, the role of Margin and Padding in the story titled "The Box Model" is to provide space and distance to the box's content, as well as comfort and support to the box itself. The four parts of an HTML element's box, as referred to by the box model, are Content, Padding, Border, and Margin.
 
Content is the innermost part of the box, Padding is the space between Content and Border, Border is the visible outline around the box, and Margin is the space between Border and other elements.


## List and describe the four parts of an HTML elements box as referred to by the box model.

* Content: The actual content of the HTML element.
* Padding: The space between the content and the border of the element.
* Border: The line that surrounds the element, separating it from other elements.
* Margin: The space between the border of the element and surrounding elements.

* Together, these four parts make up the complete box that an HTML element is displayed in on a web page. The size of the box is determined by the sum of the content, padding, border, and margin. 



## What are the data types that can be stored inside of an Array?
* In JavaScript, an Array can store any data type, including numbers, strings, boolean values, objects, and even other arrays.


## The following code declares an array in JavaScript: let people = ["Alice", "Bob", "Charlie", "Dave"]; Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

* Yes, the people array is a valid JavaScript array. To access the values stored in the array, you can use the array indexing notation, which starts at 0. For example, if you wanted to access the first value in the array, you would use people[0]. If you wanted to access the second value, you would use people[1], and so on.

## List five shorthand operators for assignment in javascript and describe what they do

* += - adds the value on the right to the variable on the left and assigns the result to the variable on the left.
* -= - subtracts the value on the right from the variable on the left and assigns the result to the variable on the left.
* *= - multiplies the variable on the left by the value on the right and assigns the result to the variable on the left.
* /= - divides the variable on the left by the value on the right and assigns the result to the variable on the left.
* %= - divides the variable on the left by the value on the right and assigns the remainder to the variable on the left.
* Using shorthand operators can make code more concise and easier to read, especially in cases where the same variable is used multiple times in an expression. For example, instead of writing x = x + 5, you can write x += 5.

## Read the code below and evaluate the last expression and explain what the result would be and why.

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
* In JavaScript, the + operator is used for both addition and string concatenation, depending on the types of the operands involved. When used with a string operand, it concatenates the strings.
In this expression, the parentheses (a + c) evaluate to the number 10 (since false is treated as 0 in a numeric context), which is then concatenated with the string 'dog' to form the string '10falsedog'.
So the final result of the expression is the string '10falsedog'


## Describe a real world example of when a conditional statement should be used in a JavaScript program.

* A real-world example of when a conditional statement should be used in a JavaScript program is in an e-commerce website's shopping cart functionality.
When a user adds items to their shopping cart, the website needs to calculate the total cost of the items and apply any discounts or promotions that may be available. The calculation of the total cost may be different based on the number of items in the cart, the type of items, and whether or not the user is a registered member.
In this case, a conditional statement can be used to check the number of items in the cart, the user's membership status, and the type of items in the cart. Depending on the results of these checks, different calculations may need to be performed to arrive at the correct total cost.
For example, if the user is a registered member, they may be entitled to a discount on certain items in their cart. The conditional statement can check if the user is a registered member and if any of the items in the cart are eligible for the discount. If both conditions are true, the discount can be applied to the total cost of the items.
In this way, conditional statements can be used to make the shopping cart functionality more dynamic and flexible, and to provide users with a customized shopping experience.

## Give an example of when a Loop is useful in JavaScript.

* In this example, the for loop starts at index 0, and iterates over each element in the numbers array. On each iteration, it adds the value of the current element to the sum variable. Finally, the loop ends and the sum variable contains the total sum of all the numbers in the array.

let numbers = [1, 2, 3, 4, 5];
let sum = 0;

for (let i = 0; i < numbers.length; i++) {
  sum += numbers[i];
}

console.log(sum); // output: 15

