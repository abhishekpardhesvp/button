<html>

<head>

<title>Three buttom action</title>

<script>

function b1()

{

alert("Hello! friends how r you today?");

}

function b2()

{

alert("User name is = Abhishek Pardhe")

} 

function b3()

{

 var x=parseInt(document.getElementById("t1").value);

var x=parseInt(document.getElementById("t2").value);

var z=x+y;

document.write("Addition is = "+z);

}

</script>

</head>

<body>

<form>

<input type="button" value="Button 1" onClick="b1()">

</br>

<input type="button" value="Button 2" onClick="b2()">

</br>

Enter : <input type="text" id="t1"/>

</br>

Enter : <input type="text" id="t2"/>

</br>

<input type="button" value="Add" onClick="b3()">

</form>

</body>

</html>3" onClick="b3()">

</form>

</body>

</html>

