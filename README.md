<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Video Portal</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden; /* Prevents scrollbars */
            background-color: black;
        }

        .video-background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }

        iframe {
            width: 100vw;
            height: 100vh;
            border: none;
        }
    </style>
</head>
<body>

    <div class="video-background">
        <iframe 
            src="https://www.youtube.com/embed/?autoplay=1&mute=1&loop=1&playlist=[VIDEO_ID_HERE](https://youtu.be/Q1FSCSyFJ7U)&controls=0&showinfo=0&rel=0" 
            allow="autoplay; encrypted-media" 
            allowfullscreen>
        </iframe>
    </div>

</body>
</html>
