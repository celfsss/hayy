# hayy
This is the sudoku game which doesn't WORKS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link rel="stylesheet" href="style3.css">

    <title>TP3 JAVASCRIPT</title>
</head>
<body>
  <style>
  .parent{
    grid-template-columns: repeat(9, auto);
    display: inline-grid;
    width: 320px;
    padding: 1%;
    border: 1px solid black;
    background-color: yellow;
}
.parent:hover{
    BACKGROUND-color: orange;
}
.parent input{
    width: 30px;
    height: 30px;
    background-color: lightgreen;
    border: solid 1px black;
    border-radius: 6px;
    margin:1px;
    
}
</style>
    <h1>SUDOKU</h1>
    <div class="parent">
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
        <div><input type="text" ></div>
    </div>
    <script>
    var num=[0, 9, 5, 3, 0, 8, 7, 0, 1, 8, 2, 1, 0, 7, 0, 0, 6, 0, 6, 7, 0, 4, 0, 0, 8, 0, 0, 2, 4, 0, 0, 0, 9, 0, 5, 0, 0, 0, 9, 0, 0, 0, 2, 0, 0, 0, 1, 0, 2, 0, 0, 0, 4, 8, 0, 0, 4, 0, 0, 2, 0, 8, 9, 0, 6, 0, 0, 3, 0, 1, 7, 2, 1, 0, 2, 8, 0, 7, 6, 3, 0];
    var sudoku = document.querySelector(".parent");
    for (i=0; i<sudoku.children.length; i++) {
        if(num[1] !=0){
            var input = sudoku.children[i].children[0];
            input.value = num[1];
            input.disabled = true;
        }
    }
    </script>
</body>
</html>
