# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
~~~<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
~~~
## OUTPUT

![answer](https://github.com/Divyapriyadiya/Ex07_Web-Design/assets/128477941/39ca024d-06b5-4e00-a0ba-d6b84b84053f)

![answe 1](https://github.com/Divyapriyadiya/Ex07_Web-Design/assets/128477941/72cdf462-6795-497b-99a4-f3796a610d04)

![answer 2](https://github.com/Divyapriyadiya/Ex07_Web-Design/assets/128477941/85135d4c-f5e0-46d8-b368-e3f66c10d2c8)




## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.

