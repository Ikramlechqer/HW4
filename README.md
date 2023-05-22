# HW4



<!-- Form using GET method -->

<form action="https://www.example.com/form-handler" method="get" target="_blank">

  <label for="name">Name:</label><br>

  <input type="text" id="name" name="name"><br>

  <input type="submit" value="Submit">

</form>



<!-- Form using POST method -->

<form action="https://www.example.com/form-handler" method="post" target="_self">

  <label for="email">Email:</label><br>

  <input type="email" id="email" name="email" required><br>

  <input type="submit" value="Submit">

</form>



<!--Implementing a simple canvas application in HTML5-->



<!DOCTYPE html>

<html>

<body>



<canvas id=”myCanvas” width=”500” height=”500” style=”border:1px solid #d3d3d3;”>

Your browser does not support the HTML5 canvas tag.

</canvas>



<script>

Var c = document.getElementById(“myCanvas”);

Var ctx = c.getContext(“2d”);

Ctx.fillStyle = “#FF0000”;

Ctx.fillRect(20, 20, 150, 100);

</script> 



</body>

</html>




