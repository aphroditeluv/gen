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
