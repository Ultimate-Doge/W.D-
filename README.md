<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DARKER YET DARKER</title>
    <style>
        /* Violent screen-wide earthquake shake */
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #000;
            overflow: hidden;
            animation: screenQuake 0.04s infinite linear;
        }

        @keyframes screenQuake {
            0% { transform: translate(6px, -4px) rotate(1deg); }
            20% { transform: translate(-8px, 6px) rotate(-1.5deg); }
            40% { transform: translate(-4px, -6px) rotate(0.5deg); }
            60% { transform: translate(8px, 4px) rotate(-1deg); }
            80% { transform: translate(-6px, 8px) rotate(1.5deg); }
            100% { transform: translate(4px, -8px) rotate(0deg); }
        }

        /* Container for the centered text wrapping */
        .shake-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            max-width: 90vw;
            /* Uses Wingdings. Falls back to Webdings or general symbols if missing */
            font-family: 'Wingdings', 'Webdings', sans-serif;
            font-size: 3.5rem;
            color: #ff0000; /* Aggressive glitch red */
            text-shadow: 0 0 15px rgba(255, 0, 0, 0.8);
            user-select: none;
        }

        /* Violent random character tearing */
        .char {
            display: inline-block;
            white-space: pre; /* Prevents spacing glitches while moving */
            animation: charRip 0.05s infinite linear;
        }

        @keyframes charRip {
            0% { transform: translate(0px, 0px) rotate(0deg) scale(1); filter: hue-rotate(0deg); }
            20% { transform: translate(-15px, 12px) rotate(-12deg) scale(1.1); }
            40% { transform: translate(12px, -15px) rotate(15deg) scale(0.9); }
            60% { transform: translate(-10px, -10px) rotate(-8deg) scale(1.2); }
            80% { transform: translate(15px, 10px) rotate(10deg) scale(0.95); }
            100% { transform: translate(-12px, 15px) rotate(-15deg) scale(1.1); }
        }

        /* Extreme desynchronisation for raw chaos */
        .char:nth-child(2n) { animation-delay: 0.01s; animation-duration: 0.04s; color: #fff; }
        .char:nth-child(3n) { animation-delay: 0.02s; animation-duration: 0.06s; }
        .char:nth-child(4n) { animation-delay: 0.03s; animation-duration: 0.03s; color: #555; }
        .char:nth-child(5n) { animation-delay: 0.015s; animation-duration: 0.05s; }
    </style>
</head>
<body>

    <div class="shake-container">
        <!-- Text converted character by character to maintain independent violent motion -->
        <span class="char">👎︎</span><span class="char">✌︎</span><span class="char">☼︎</span><span class="char">😐︎</span><span class="char">☜︎</span><span class="char">☼︎</span><span class="char"> </span><span class="char">✡︎</span><span class="char">☜︎</span><span class="char">❄︎</span><span class="char"> </span><span class="char">👎︎</span><span class="char">✌︎</span><span class="char">☼︎</span><span class="char">😐︎</span><span class="char">☜︎</span><span class="char">☼︎</span><span class="char"> </span><span class="char">❄︎</span><span class="char">☟︎</span><span class="char">☜︎</span><span class="char"> </span><span class="char">✞︎</span><span class="char">✋︎</span><span class="char">💧︎</span><span class="char">💡︎</span><span class="char">⚐︎</span><span class="char">☠︎</span><span class="char">💧︎</span><span class="char"> </span><span class="char">☝︎</span><span class="char">☜︎</span><span class="char">❄︎</span><span class="char"> </span><span class="char">💧︎</span><span class="char">❄︎</span><span class="char">☼︎</span><span class="char">⚐︎</span><span class="char">☠︎</span><span class="char">☝︎</span><span class="char">☜︎</span><span class="char">☼︎</span><span class="char">📪︎</span><span class="char"> </span><span class="char">☜︎</span><span class="char">✞︎</span><span class="char">☜︎</span><span class="char">☼︎</span><span class="char">✡︎</span><span class="char"> </span><span class="char">❄︎</span><span class="char">✋︎</span><span class="char">💣︎</span><span class="char">☜︎</span><span class="char"> </span><span class="char">❄︎</span><span class="char">☟︎</span><span class="char">☜︎</span><span class="char"> </span><span class="char">👎︎</span><span class="char">✌︎</span><span class="char">☼︎</span><span class="char">😐︎</span><span class="char">☠︎</span><span class="char">☜︎</span><span class="char">💧︎</span><span class="char">💧︎</span><span class="char"> </span><span class="char">👍︎</span><span class="char">🕆︎</span><span class="char">❄︎</span><span class="char">💧︎</span><span class="char"> </span><span class="char">👎︎</span><span class="char">☜︎</span><span class="char">☜︎</span><span class="char">🏱︎</span><span class="char">☜︎</span><span class="char">☼︎</span><span class="char">📬︎</span><span class="char">📬︎</span><span class="char">📬︎</span>
    </div>

</body>
</html>
