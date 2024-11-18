<html>
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>A simple example</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/pannellum@2.5.6/build/pannellum.css"/>
    <script type="text/javascript" src="https://github.com/joshvanpraag/artlab/blob/main/pannellum.js"></script>
    <style>
    #panorama {
        width: 600px;
        height: 400px;
    }
    </style>
</head>
<body>

<div id="panorama"></div>
<script>
pannellum.viewer('panorama', {
    "type": "equirectangular",
    "panorama": "https://github.com/joshvanpraag/artlab/blob/0f9a1dc57df2e8292f8de36c199a6d23b8b6f5d2/artlab_pano.jpg"
});
</script>

</body>
</html>