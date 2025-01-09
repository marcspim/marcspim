# Hello there!  
![Obi-Wan Kenobi GIF](https://media.giphy.com/media/d2lcHJTG5Tscg/giphy.gif)

## About me:

<svg width="100%" height="100" viewBox="0 0 1000 100">
  <text x="20" y="40" font-family="monospace" font-size="30" fill="black">
    <tspan id="typeText"></tspan>
  </text>
</svg>

<script>
  const text = "My name is Marcel, I'm a geologist with a master's degree in Soil Science. Currently, I'm studying programming and data science, for I've always been a tech enthusiast and now am looking for new paths in my life and career. Feel free to reach out! 😉🫡";
  let index = 0;
  
  function typeText() {
    if (index < text.length) {
      document.getElementById('typeText').textContent += text.charAt(index);
      index++;
      setTimeout(typeText, 100); // Adjust typing speed here
    }
  }

  typeText();
</script>

## Skills:

- ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- ![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
- ![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
- ![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
- ![Office](https://img.shields.io/badge/Office-D83B01?style=for-the-badge&logo=microsoft-office&logoColor=white)
