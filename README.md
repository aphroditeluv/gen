<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password Generator</title>
    <link rel="stylesheet" href="style.css">

</head>
<body>
    <div class="container">
        <h1>Password Generator</h1>
        <div class="password">
            <input type="text" id="password" readonly>
            <button type="button" id="generate">Generate password</button>
            <div class="options">
                <label for="length">Password Length</label>
                <input type="number" id="length" value="8" min="8" max="64">
                <label for="lowercase">Include Lowercase:</label>
                <input type="checkbox" id="lowercase" checked>
                <label for="uppercase">Include Uppercase:</label>
                <input type="checkbox" id="uppercase" checked>
                <label for="numbers">Include numbers:</label>
                <input type="checkbox" id="numbers" checked>
                <label for="symbols">Include symbols:</label>
                <input type="checkbox" id="symbols" checked>
            </div>
        </div>
    </div>
<script src="app.js"></script>    
</body>
</html>

body{
    background-color: blanchedalmond;
    font-family: 'Segoe UI', Tahoma, sans-serif;
    background-image: url('desk.jpeg');

}
.container{
    max-width: 600px;
    margin: 0 auto;
    padding: 25px;
    border-radius: 5px;
    box-shadow: 0px 0px 20px, rgba(0, 0,0, 0.2);
    background-color: bisque;

}
h1{
    text-align: center;
    margin-top: 0px;

}

label{
    display: flex;
    align-items: center;
    margin: 10px 0px;
}

#password{
    margin-top: 20px;
    font-size: 24px;
    text-align: center;
    padding:10px;
    border: none;
    border-radius: 5px;
    background-color: rgb(218, 194, 134);
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.2);
}

#generate{
    margin-top: 20px;
    background-color: rgb(192, 130, 130);
    border: none;
    border-radius: 5px;
    padding: 10px;
    font-size: 16px;
    cursor: pointer;
    color: antiquewhite;
}

#generate:hover{
    background-color:  rgb(194, 156, 156);
}
