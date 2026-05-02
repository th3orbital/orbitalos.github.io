<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal</title>
    <style>
        /* Removes all margins and scrollbars */
        body, html {
            margin: 0;
            padding: 0;
            width: 100%;
            height: 100%;
            overflow: hidden;
            background-color: black;
        }

        /* Makes the video cover the entire screen */
        #bg-video {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%;
            min-height: 100%;
            width: auto;
            height: auto;
            z-index: -100;
            background-size: cover;
        }
    </style>
</head>
<body>

    <video autoplay muted loop playsinline id="bg-video">
        <source src=".mp4" type="video/mp4">
        Your browser does not support HTML5 video.
    </video>

</body>
</html>
