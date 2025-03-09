<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lightshot</title>
    <style>
        body { background-color: #f0f0f0; text-align: center; padding: 50px; }
        img { width: 80%; max-width: 600px; cursor: pointer; }
    </style>
</head>
<body>
    <h2>Lightshot Screenshot</h2>
    <img src="https://via.placeholder.com/600x400.png?text=Klik+untuk+melihat+screenshot" onclick="jumpscare()">
    <script>
        function jumpscare() {
            let audio = new Audio('https://www.myinstants.com/media/sounds/screaming.mp3');
            audio.play();
            document.body.innerHTML = '<img src="https://i.gifer.com/7Xc2.gif" style="width:100vw;height:100vh;">';
        }
    </script>
</body>
</html># jumpscar-prank
