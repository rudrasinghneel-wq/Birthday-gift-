# Birthday-gift-
Happy birthday 🎂
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday My Love</title>
    <style>
        /* Import romantic fonts */
        @import url('https://fonts.googleapis.com/css2?family=Great+Vibes&family=Montserrat:wght@300;500&display=swap');

        * {
            box-sizing: border-box;
        }

        body, html {
            height: 100%;
            margin: 0;
            padding: 0;
        }

        body {
            /* Soft floral background with a pink overlay */
            background-image: 
                linear-gradient(to bottom, rgba(255, 240, 245, 0.8), rgba(255, 192, 203, 0.6)),
                url('https://images.unsplash.com/photo-1490750967868-58cb75063ed4?q=80&w=2070&auto=format&fit=crop');
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: 'Montserrat', sans-serif;
            color: #4a4a4a;
        }

        /* The main card container */
        .container {
            background: rgba(255, 255, 255, 0.85);
            padding: 3rem 4rem;
            border-radius: 30px;
            text-align: center;
            max-width: 700px;
            width: 90%;
            box-shadow: 0 15px 35px rgba(255, 105, 180, 0.2);
            border: 1px solid rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(10px);
            animation: float 6s ease-in-out infinite;
        }

        /* The main greeting */
        h1 {
            font-family: 'Great Vibes', cursive;
            font-size: 4rem;
            color: #d63384;
            margin: 0 0 1rem 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.1);
            line-height: 1;
        }

        /* The message text */
        p {
            font-size: 1.1rem;
            line-height: 1.8;
            color: #555;
            margin-bottom: 0;
        }

        /* Small decorative hearts */
        .heart-icon {
            color: #ff4d6d;
            font-size: 1.5rem;
            margin: 0 5px;
            animation: heartbeat 1.5s infinite;
        }

        /* Animations */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        @keyframes heartbeat {
            0% { transform: scale(1); }
            15% { transform: scale(1.2); }
            30% { transform: scale(1); }
            45% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }

        /* Mobile responsiveness */
        @media (max-width: 600px) {
            .container {
                padding: 2rem;
                width: 90%;
            }
            h1 {
                font-size: 3rem;
            }
            p {
                font-size: 1rem;
            }
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Happy Birthday, my love! 🌟</h1>
        <p>
            Today, the world got even brighter because you're in it. 
            You're my favorite person, my heartbeat, and the reason my days feel like dreams. 
            <br><br>
            I made this website for you. 
            I love you more than words can say—today and every day! 💕🥳
        </p>
    </div>

</body>
</html>
