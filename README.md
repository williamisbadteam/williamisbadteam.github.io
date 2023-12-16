
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Password-Protected Page</title>
</head>
<body>

<script>
    // Prompt the user for a password
    var enteredPassword = prompt("Enter your name:");

    // Check if the entered password is '1234'
    if (enteredPassword === 'William') {
        // If the password is correct, display the personalized message
        document.write("<h1>William you are so dumb like, tell me what 3 x 100 is. Whatevs, lets get some food cuz I'm a bit tired.</h1>");
    } else {
        // If the password is incorrect, display an error message
        document.write("<h1>Incorrect password</h1>");
    }
</script>

</body>
</html>











