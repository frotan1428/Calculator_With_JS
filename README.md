<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
 <meta charset="utf-8"a>
<!--  <title> Simple Calculator using HTML, CSS and JavaScript </title> -->
 <link rel="stylesheet" href="styles.css">
</head>
<body>
    <span><h1>My lovely Calculator</h1></span>
    <table class = "calculator" >
    <tr>
    <td colspan = "3"> <input class = "display-box" type = "text" id = "result" disabled /> </td>
    <!-- clearScreen() function clear all the values --&gt; -->
    <td> <input class = "button" type = "button" value = "C" onclick = "clearScreen()" style = "background-color: #580426; width: 60px;" /> </td>
    </tr>
    <tr>
    <!-- display() function display the value of clicked button --&gt; -->
    <td> <input class = "button" type = "button" value = "1" onclick = "display('1')" /> </td>
    <td> <input class = "button" type = "button" value = "2" onclick = "display('2')" /> </td>
    <td> <input class = "button" type = "button" value = "3" onclick = "display('3')" /> </td>
    <td> <input class = "button" type = "button" value = "/" onclick = "display('/')" /> </td>
    </tr>
    <tr>
    <td> <input class = "button" type = "button" value = "4" onclick = "display('4')" /> </td>
    <td> <input class = "button" type = "button" value = "5" onclick = "display('5')" /> </td>
    <td> <input class = "button" type = "button" value = "6" onclick = "display('6')" /> </td>
    <td> <input class = "button" type = "button" value = "-" onclick = "display('-')" /> </td>
    </tr>
    <tr>
    <td> <input class = "button" type = "button" value = "7" onclick = "display('7')" /> </td>
    <td> <input class = "button" type = "button" value = "8" onclick = "display('8')" /> </td>
    <td> <input class = "button" type = "button" value = "9" onclick = "display('9')" /> </td>
    <td> <input class = "button" type = "button" value = "+" onclick = "display('+')" /> </td>
    </tr>
    <tr>
    <td> <input class = "button" type = "button" value = "." onclick = "display('.')" /> </td>
    <td> <input class = "button" type = "button" value = "0" onclick = "display('0')" /> </td>
    <!-- calculate() function evaluate the mathematical expression --&gt; -->
    <td> <input class = "button" type = "button" value = "=" onclick = "calculate()" </td>
    <td> <input class = "button" type = "button" value = "*" onclick = "display('*')" /> </td>
    </tr>
    </table>
<!-- <script type="text/javascript" src="index.js"></script> -->
</body>
</html>
