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
~~~
<html>
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
![ex-7(1)](https://github.com/Blessytheboral/Ex07_Web-Design/assets/127816463/b9a29ee8-1939-44aa-92b4-5e29a11f59c4)
![ex-7(2)](https://github.com/Blessytheboral/Ex07_Web-Design/assets/127816463/232b2084-a3dd-4212-a378-f599028550fe)
![ex-7(3)](https://github.com/Blessytheboral/Ex07_Web-Design/assets/127816463/00b98646-c631-480f-a460-606dbfee647b)
![ex-7(4)](https://github.com/Blessytheboral/Ex07_Web-Design/assets/127816463/16db180a-e48b-4ebe-bd62-e38fd4b2b561)



## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
