<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baldhart</title>
    <style>
        /* Genel stil */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #1a1a2e;
            color: #fff;
            text-align: center;
        }
        
        .social-card {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        
        .Btn {
            position: relative;
            width: 80px;
            height: 80px;
            background-color: #333;
            border: none;
            border-radius: 50%;
            overflow: hidden;
            cursor: pointer;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: transform 0.3s;
        }
        
        .Btn:hover {
            transform: scale(1.1);
        }
        
        .svgContainer {
            position: relative;
            z-index: 2;
        }
        
        .BG {
            position: absolute;
            width: 100%;
            height: 100%;
            background-color: #e94560;
            top: 100%;
            left: 0;
            z-index: 1;
            transition: top 0.3s ease-in-out;
        }
        
        .Btn:hover .BG {
            top: 0;
        }
        
        .Btn.github .BG { background-color: #333; }
        .Btn.whatsapp .BG { background-color: #25d366; }
        .Btn.linkdin .BG { background-color: #0077b5; }
        .Btn.discord .BG { background-color: #5865f2; }
    </style>
</head>
<body>
    <h1>Hi 👋, I'm Baldhart</h1>
    <p>[![Discord Presence](https://lanyard.cnrad.dev/api/786588903141670942)](https://discord.com/users/786588903141670942)</p>
    <h3 align="left">📊 Github Status</h3>
    <p>
        <img src="https://komarev.com/ghpvc/?username=baldhartdev&label=Profile%20views&color=0e75b6&style=flat" alt="baldhart" />
    </p>

    <div class="social-card">
        <button class="Btn github">
            <span class="svgContainer">
                <svg height="1.6em" viewBox="0 0 496 512" fill="white">
                    <path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8z"></path>
                </svg>
            </span>
            <span class="BG"></span>
        </button>
        <!-- Diğer butonlar -->
    </div>
</body>
</html>
