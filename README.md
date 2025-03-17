<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Embed Audio and Video</title>
</head>
<body>
    <h1>Embedding Audio and Video in HTML</h1>

    <h2>Audio Example</h2>
    <audio controls>
        <source src="audio_sample.mp3" type="audio/mpeg">
        <source src="audio_sample.ogg" type="audio/ogg">
        Your browser does not support the audio element.
    </audio>

    <h2>Video Example</h2>
    <video width="400" height="300" controls>
        <source src="video_sample.mp4" type="video/mp4">
        <source src="video_sample.ogg" type="video/ogg">
        Your browser does not support the video element.
    </video>
</body>
</html>
