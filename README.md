<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
    <style>
        body {
            font-family: 'Comic Sans MS', cursive, sans-serif;
            background-color: #f0f8ff;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        h1 {
            font-size: 2.5em;
            color: #ff6347;
            margin: 20px 0;
            animation: bounce 2s infinite;
        }

        h2 {
            font-size: 2em;
            color: #4682b4;
            margin: 20px 0;
        }

        p {
            font-size: 1.2em;
            margin: 10px 0;
            line-height: 1.5;
        }

        .tech-stack img {
            height: 40px;
            margin: 5px;
            transition: transform 0.3s ease;
        }

        .tech-stack img:hover {
            transform: scale(1.2);
        }

        .social-media a {
            margin: 10px;
            text-decoration: none;
            color: #4682b4;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }

        .social-media a:hover {
            color: #ff6347;
        }

        .github-stats img {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }

        .animated-background {
            background: linear-gradient(45deg, #ff6347, #4682b4);
            background-size: 400% 400%;
            animation: gradient 15s ease infinite;
            color: #fff;
            padding: 20px;
            border-radius: 10px;
            display: inline-block;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }

        @keyframes bounce {
            0%, 20%, 50%, 80%, 100% {
                transform: translateY(0);
            }
            40% {
                transform: translateY(-20px);
            }
            60% {
                transform: translateY(-10px);
            }
        }

        @keyframes gradient {
            0% {
                background-position: 0% 0%;
            }
            50% {
                background-position: 100% 100%;
            }
            100% {
                background-position: 0% 0%;
            }
        }

        footer {
            margin: 20px 0;
            font-size: 1em;
            color: #4682b4;
        }
    </style>
</head>
<body>
    <h1>💫 About Me</h1>
    <div class="animated-background">
        <p>🔭 I’m currently working on a Lua based game</p>
        <p>🤝 I’m looking for help with my Lua game</p>
        <p>🌱 I’m currently learning Lua</p>
        <p>⚡ Fun fact: Full-time student</p>
    </div>

    <h2>💻 Tech Stack:</h2>
    <div class="tech-stack">
        <img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
        <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" alt="JavaScript">
        <img src="https://img.shields.io/badge/lua-%232C2D72.svg?style=for-the-badge&logo=lua&logoColor=white" alt="Lua">
        <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python">
    </div>

    <h2>📊 GitHub Stats:</h2>
    <div class="github-stats">
        <img src="https://github-readme-stats.vercel.app/api?username=fadedsushi&theme=dark&hide_border=false&include_all_commits=false&count_private=false" alt="GitHub Stats">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=fadedsushi&theme=dark&hide_border=false" alt="GitHub Streak Stats">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=fadedsushi&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages">
    </div>

    <h2>🏆 GitHub Trophies:</h2>
    <img src="https://github-profile-trophy.vercel.app/?username=fadedsushi&theme=radical&no-frame=false&no-bg=true&margin-w=4" alt="GitHub Trophies">

    <h2>📱 Social Media:</h2>
    <div class="social-media">
        <a href="https://twitter.com/yourusername" target="_blank">🐦 Twitter</a>
        <a href="https://linkedin.com/in/yourusername" target="_blank">🔗 LinkedIn</a>
        <a href="https://github.com/yourusername" target="_blank">🐙 GitHub</a>
    </div>

    <hr>
    <p>🌐 <a href="https://visitcount.itsvg.in/api?id=fadedsushi&icon=0&color=11" target="_blank">Page Views</a></p>

    <footer>
        <p>Created with ❤️ by [Your Name]</p>
    </footer>
</body>
</html>
