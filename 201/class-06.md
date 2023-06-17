# Reading Notes Class 06

## How would you describe an object to a non-technical friend you grew up with?

Basically an object is just a collection of information that has functions or equations related to it.

## What are some advantages to creating object literals?

It's easier to manage several items by giving them individuality and it's easier to work with than an array. Object literals in JS allows us to create plain JS objects.

## How do objects differ from arrays?

arrays use numbers to access elements while objects use properties to access elements.

## Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation

When you need a person's age or first name.

## Evaluate the code below. What does the term this refer to and what is the advantage to using this?

This refers to the dog, it's useful because if you have to create more than one this enables you to use the same method more than once.

const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

## What is the DOM?

The DOM is a programming interface for web documents, It represents the page so that programs can change the document structure, style, and content.

## Briefly describe the relationship between the DOM and JavaScript

You write in Javascript but you use DOM to access the document and its elements. DOM isn't a programming language but without DOM, Javascript wouldn't have any model or notion of web pages.
