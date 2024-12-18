<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Protected Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 100px;
        }
    </style>
</head>
<body>
    <h1>Enter the Password</h1>
    <input type="password" id="password" placeholder="Password">
    <button onclick="checkPassword()">Submit</button>

    <script>
        function checkPassword() {
            const password = document.getElementById('password').value;
            const correctPassword = "mysecret"; // Change to your desired password
            const redirectURL = "https://www.jjjjjjjjjjjjjjjjjjjjjjj.com"; // Change to your desired URL
            if (password === correctPassword) {
                window.location.href = redirectURL;
            } else {
                alert('Incorrect password');
            }
        }
    </script>
</body>
</html>

