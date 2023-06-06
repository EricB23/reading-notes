# Class 03 Reading Notes

## When should you use an unordered list in your HTML document?

When you're trying to list items but don't want them to be in numerical order.

## How do you change the bullet style of unordered list items?

You can do this by changing the list type like <ol type='i'>

## When should you use an ordered list vs an unorder list in your HTML document?

When your creating a numbered list you should use ordered but if you just want a bulleted list use an unordered list.

Ordered list can be used for steps in a recipe or directions.

## Describe two ways you can change the numbers on list items provided by an ordered list?

By using Roman numerals or by using the start attributes.

## Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Padding and Margin would be supporting cast that has cameos throughout the movie and keep the pacing and direction of the movie. They keep things in shape!

## List and describe the four parts of an HTML elements box as referred to by the box model

Content, Padding, Border, Margin.
Content is the area where the content is displayed, padding sits around the content as white space, the border box wraps the content and any padding, and margins is the outermost layer wrapping the content, border as whitespace between this box and other elements.

## What data types can you store inside of an Array?

Strings, numbers, objects, and booleans.

## Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

Yes it is! It can be properly used and the different values can be seen as well. It also had valid data types in it.

 const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

## List five shorthand operators for assignment in javascript and describe what they do

x &&= y the logical AND assignment operator only assigns if x is truthy determines if both values on each side of the operator returns a true value.

x += f sets the value of x = x +f

x == y this is an operator that compares two operands to see if their values

## Read the code below and evaluate the last expression and explain what the result would be and why

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

The answer would be 10dog because false doesn't have any value and 10 is equal to nothing so it would be added to the string that dog is.

## Describe a real world example of when a conditional statement should be used in a JavaScript program

If the users password input is equal to the users password in the db.

When to run certain code blocks. An example of this could be if a user is logged in.

Using a conditional to determin if a workers hours passed a certain threshold to be considered overtime if(hoursWorked > 40)

## Give an example of when a Loop is useful in JavaScript

Rendering elements based on a specific need.

When a user is supposed to have a valid input. while (userInput !== userPassword){
  
}
