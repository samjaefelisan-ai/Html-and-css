# Html-and-css
code<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lion Web Page</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4c542;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header {
            background-color: #8b5a2b;
            color: white;
            padding: 20px;
        }

        .container {
            padding: 20px;
        }

        img {
            width: 300px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.3);
        }

        h2 {
            color: #5c3b12;
        }

        p {
            width: 70%;
            margin: auto;
            font-size: 18px;
            line-height: 1.6;
        }

        footer {
            background-color: #8b5a2b;
            color: white;
            padding: 10px;
            margin-top: 20px;
        }

        button {
            background-color: #5c3b12;
            color: white;
            border: none;
            padding: 12px 20px;
            margin-top: 15px;
            border-radius: 8px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #3e260c;
        }
    </style>
</head>
<body>

    <header>
        <h1>The Lion</h1>
    </header>

    <div class="container">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/73/Lion_waiting_in_Namibia.jpg" alt="Lion">

        <h2>King of the Jungle</h2>

        <p>
            Lions are powerful wild cats known for their strength, courage,
            and majestic appearance. They live mostly in Africa and are called
            the "King of the Jungle" because of their dominance and leadership.
        </p>

        <button onclick="showMessage()">Learn More</button>
    </div>

    <footer>
        <p>Created with HTML & CSS</p>
    </footer>

    <script>
        function showMessage() {
            alert("Lions are amazing animals!");
        }
    </script>

</body>
</html>
