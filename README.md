<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Project Hub</title>
    <style>
        body {
            background-color: #1a1a1a;
            color: white;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 900px;
            margin: auto;
        }
        .video-wrapper {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            overflow: hidden;
            margin-bottom: 30px;
            border-radius: 12px;
            box-shadow: 0px 4px 15px rgba(0,0,0,0.5);
        }
        .video-wrapper iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
        .game-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }
        .game-card {
            background: #333;
            padding: 20px;
            border-radius: 8px;
            width: 200px;
            text-decoration: none;
            color: cyan;
            font-weight: bold;
            transition: 0.3s;
        }
        .game-card:hover {
            background: #444;
            transform: scale(1.05);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Welcome to the Hub</h1>
        
        <div class="video-wrapper">
            <iframe 
                src="https://www.youtube.com/embed/(https://youtu.be/Q1FSCSyFJ7U)?autoplay=1&mute=1&loop=1&playlist=VIDEO_ID_HERE" 
                frameborder="0" 
                allow="autoplay; encrypted-media" 
                allowfullscreen>
            </iframe>
        </div>

        <hr>

        <h2>My Games</h2>
        <div class="game-list">
            <a href="#" class="game-card">Coming Soon...</a>
            <a href="#" class="game-card">Coming Soon...</a>
        </div>
    </div>

</body>
</html>
