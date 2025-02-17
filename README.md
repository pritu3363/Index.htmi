# Index.htmi
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Do You Love Me?</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin-top: 20%; }
        button { font-size: 20px; margin: 10px; padding: 10px; }
    </style>
</head>
<body>
    <h1>Do you love me?</h1>
    <button onclick="location.href='yes.html'">Yes</button>
    <button onclick="location.href='no.html'">No</button>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yes - Love</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin-top: 20%; }
        .love { font-size: 24px; color: red; }
    </style>
</head>
<body>
    <h1 class="love">Dil ki baat tumse ❤️</h1>
    <p>You are my happiness, my love, my everything! 💖</p>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>No - Sad</title>
    <style>
        body { text-align: center; font-family: Arial, sans-serif; margin-top: 20%; }
        .message { font-size: 24px; }
        button { font-size: 20px; margin-top: 20px; }
    </style>
    <script>
        let messages = [
            "Tum mujhse pyar nahi karte 😢",
            "Fir nahin bolungi... 😞",
            "Last bol rahi hoon! 💔"
        ];
        let index = 0;
        
        function changeMessage() {
            if (index < messages.length) {
                document.getElementById("msg").innerText = messages[index];
                index++;
            }
        }
    </script>
</head>
<body>
    <h1 class="message" id="msg">Tum mujhse pyar nahi karte 😢</h1>
    <button onclick="changeMessage()">No</button>
</body>
</html>
