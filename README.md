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

## OUTPUT

![1](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/96f0f4ba-2fc9-41c7-8a2c-d188faf891d2)
![2](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/3bdc3262-dcb7-4ae0-9e0b-d75bdd9e5948)
![3](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/7f6ed962-001a-4068-970b-f4ab9475a085)
![4](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/d4bbc024-ae28-4821-9f14-d4ecb9fca564)
![5](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/5d2a70a5-0b96-4438-add8-9d1a69a0ac6f)
![6](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/3e5e7df5-e4e5-41db-b514-a9adb68d2722)
![7](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/8460d8a4-edd8-4ac0-9d6f-90bc7d2aad8f)
![8](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/b66dee5a-3b13-4dcc-95c9-bd90a4ffd47e)
![9](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/6c082c3f-59a8-485f-b46c-d5402a7bb22c)
![10](https://github.com/Priyapugaz/Ex07_Web-Design/assets/127816320/02daa50e-d160-4ae4-be90-3bb955e5e06e)

## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
