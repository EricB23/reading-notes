# Class 07 notes

## What is control flow?

Control flow is the order in which the computer executes statements in a script. Code is ran in order from first line in the file to the last line unless the computer comes across a structure like a conditional and/or loop.

## What is a JavaScript function?

A Javascript Function is a block of code designed to perform a particular task. And is executed when 'something' calls it.

function myfunction(p1,p2){
    return p1*p2;
}

## What does it mean to invoke - or call - a function?

When an event occurs,like a user clicking a button, or when it is invoked by the code or is automatically or self-invoked.

## What are the parenthesis () for when you define a function?

The () operator is used to call the funtion.

<p>Invoke (call) a function that converts from Fahrenheit to Celsius:</p>
<p id="demo"></p>

<script>
function toCelsius(f) {
  return (5/9) * (f-32);
}

let value = toCelsius(77);
document.getElementById("demo").innerHTML
</script>