# hello-world
Just another repository

<!DOCTYPE html>
<html>
<body>

<p>Click the button to join three arrays.</p>

<button onclick="myFunction()">Try it</button>

<p id="demo"></p>

<script>
function myFunction() {
    var arr1 = ["Cecilie", "Lone"];
    var arr2 = ["Emil", "Tobias", "Linus"];
    var arr3 = ["Robin", "Morgan"];
    document.getElementById("demo").innerHTML =
    arr1.concat(arr2, arr3);
}
</script>

</body>
</html>
