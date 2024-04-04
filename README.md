<!DOCTYPE html>
<html>
    <style>
        body {
            background-repeat: no-repeat;
            background-size: 90%;
            color: rgb(53, 34, 5);
            text-align: center;
            font-style: oblique;
            font-size: x-large;
            background-image: url(https://i.pngimg.me/thumb/f/720/comrawpixel6182963.jpg)
            
        }
    </style>
<body>

<h2>JavaScript Objects</h2>
<p id="demo"></p>
<P>Sky is my pet</P>
<P>Grass is green</P>
<P>We have a hamster named Pepa</P>
<P>Bigbike is my dream</P>
<script>
  // Create an object:
const person = {
  firstName: "Sir Ryan",
  lastName: "Roy",
  age: 60,
  eyeColor: "blue"
};

// Display some data from the object:
document.getElementById("demo").innerHTML =
person.firstName + " is " + person.age + " years old.";
</script>
</body>
</html>
