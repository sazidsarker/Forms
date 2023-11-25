# Forms
making form by using HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
   <pre style="background-color: aquamarine;">
      <form action="/action.php">
        <input type="text" placeholder="Username or Email">
        <br>
        <input type="password" placeholder="password">
        <br>
        <hr>
        <h3>Select your class</h3>
        <pre style="background-color: bisque;">
         <label for="100"><input type="radio" value="class X" NAME="class" id="100">class X</label>
         <label for="200"><input type="radio" value="class XI" NAME="class" id="200">class XI</label>
        </pre>
      </form>
   </pre> 
   <br>
   <hr>
   <h3>Select fav subject</h3>
   <pre style="background-color: brown;">
    <label for="101">
        <input type="checkbox" value="math" name="subject" id="101">math
    </label>
    <label for="102">
        <input type="checkbox" value="math" name="subject" id="102">chemistry
    </label>
    <label for="103">
        <input type="checkbox" value="math" name="subject" id="103">physics
    </label>
    <label for="104">
        <input type="checkbox" value="math" name="subject" id="104">biology
    </label>
   </pre>
</body>
</html>
