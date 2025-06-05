<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Watch Video - MyVideoUK</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      height: 100vh;
    }
    #video-container {
      flex: 1 1 50%;
      background: black;
      display: flex;
      justify-content: center;
      align-items: center;
    }
    video {
      max-width: 100%;
      max-height: 100%;
    }
    #ads-container {
      flex: 1 1 50%;
      background: #f5f5f5;
      padding: 10px;
      box-sizing: border-box;
    }
  </style>

</head>
<body>
  <div id="video-container">
    <video controls autoplay>
      <source src="https://pixeldrain.com/api/file/36WuMFct/contents" type="video/mp4" />
      Your browser does not support the video tag.
    </video>
  </div>

  <div id="ads-container">
    <!-- Monetag ads iframe embed -->
    <iframe src="https://otieu.com/4/9404116" style="width: 100%; height: 100%; border: none;" title="Monetag Ads"></iframe>
  </div>
</body>
</html>
