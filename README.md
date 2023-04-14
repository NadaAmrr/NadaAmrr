### Hi there 👋

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>
      Circular Progress Bar using HTML, CSS & JS | SemicolonSpace.com
    </title>
    <link rel="stylesheet" href="./circular-progress-bar-styles.css">
  </head>
  <body>
    <div class="wrapper">
      <div class="container">
        <div class="background-circle"></div>
        <div class="foreground-circle">
          <!-- svg's width (180px) = 
              foreground-circle's width (180px).
            cx, cy, and r values should be half of the svg's width. -->
          <svg
            xmlns="http://www.w3.org/2000/svg"
            version="1.1"
            width="180px"
            height="180px"
          >
            <circle
              cx="90"
              cy="90"
              r="90"
              stroke="#50c878"
              stroke-width="24"
              fill="transparent"
              stroke-linecap="round"
            />
          </svg>
        </div>
        <div class="text-inside-circle">
          <p id="number-inside-circle">65 GB</p>
          <p class="remaining-text">Remaining</p>
        </div>
      </div>
      <button class="button-click" onclick="animateButtonClick()">
        Animate with Random Value
      </button>
    </div>
    <script src="./circular-progress-bar.js"></script>
  </body>
</html>
[techstack logo](https://readme-components.vercel.app/api?component=logo&logo=react)
[Dart progressbar](https://readme-components.vercel.app/api?component=linearprogress&skill=dart&value=100)
[JavaScript progressbar](https://readme-components.vercel.app/api?component=linearprogress&skill=JavaScript&value=70)
[css progressbar](https://readme-components.vercel.app/api?component=linearprogress&skill=css&value=60)

<!--
**NadaAmrr/NadaAmrr** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
