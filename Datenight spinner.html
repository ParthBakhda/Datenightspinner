<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Date Night Wheel</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #222;
      color: #fff;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
      margin: 0;
      padding: 20px;
    }
    #container {
      display: flex;
      flex-direction: row;
      align-items: center;
      gap: 40px;
    }
    #wheelContainer {
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    #wheel {
      width: 300px;
      height: 300px;
      border-radius: 50%;
      border: 8px solid #ff4444;
      position: relative;
      overflow: hidden;
      background: linear-gradient(45deg, #444, #222);
      transition: transform 3s cubic-bezier(0.25, 1, 0.5, 1);
    }
    .segment {
      width: 100%;
      height: 100%;
      position: absolute;
      clip-path: polygon(50% 50%, 100% 0, 100% 100%);
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: bold;
      color: white;
      font-size: 14px;
      padding: 10px;
      box-sizing: border-box;
      text-align: center;
    }
    #optionsList {
      max-width: 300px;
      background-color: #333;
      border: 2px solid #ff4444;
      border-radius: 8px;
      padding: 15px;
    }
    #optionsList ul {
      list-style-type: none;
      padding: 0;
      margin: 0;
      color: #ff6666;
    }
    #spinButton {
      padding: 12px 24px;
      background-color: #ff4444;
      color: white;
      border: none;
      font-size: 18px;
      cursor: pointer;
      border-radius: 8px;
      margin-top: 20px;
    }
    #result {
      margin-top: 20px;
      font-size: 20px;
      color: #ff6666;
    }
  </style>
</head>
<body>
  <h1>Date Night Wheel</h1>
  <div id="container">
    <!-- Wheel Section -->
    <div id="wheelContainer">
      <div id="wheel"></div>
      <button id="spinButton">Spin the Wheel</button>
      <div id="result"></div>
    </div>
    <!-- Options List Section -->
    <div id="optionsList">
      <h3>Options:</h3>
      <ul id="optionsListContent"></ul>
    </div>
  </div>

  <script>
    const wheel = document.getElementById("wheel");
    const result = document.getElementById("result");
    const optionsListContent = document.getElementById("optionsListContent");

    // Expanded date night restaurant and movie pairings
    const options = [
      { restaurant: "Italian Bistro", movie: "Roman Holiday" },
      { restaurant: "Sushi Spot", movie: "Lost in Translation" },
      { restaurant: "Mexican Grill", movie: "The Book of Life" },
      { restaurant: "French Café", movie: "Midnight in Paris" },
      { restaurant: "Steakhouse", movie: "Dinner Rush" },
      { restaurant: "Indian Cuisine", movie: "The Hundred-Foot Journey" },
      { restaurant: "Pizza Place", movie: "Mystic Pizza" },
      { restaurant: "Chinese Eatery", movie: "In the Mood for Love" },
      { restaurant: "Mediterranean Delight", movie: "My Big Fat Greek Wedding" },
      { restaurant: "BBQ Joint", movie: "Chef" },
      { restaurant: "Thai Restaurant", movie: "The King and I" },
      { restaurant: "Burger Shack", movie: "The Founder" },
      { restaurant: "Vegan Café", movie: "Okja" },
      { restaurant: "Seafood Spot", movie: "Finding Dory" },
      { restaurant: "Diner", movie: "Pulp Fiction" },
      { restaurant: "Tapas Bar", movie: "Vicky Cristina Barcelona" }
    ];

    // Display the options in the list
    options.forEach(option => {
      const listItem = document.createElement("li");
      listItem.textContent = `${option.restaurant} - Movie: ${option.movie}`;
      optionsListContent.appendChild(listItem);
    });

    // Generate the wheel segments
    options.forEach((option, index) => {
      const segment = document.createElement("div");
      const angle = index * (360 / options.length);
      segment.classList.add("segment");
      segment.style.transform = `rotate(${angle}deg) skewY(-${90 - 360 / options.length}deg)`;
      segment.style.background = index % 2 === 0 ? "#ff6666" : "#444";
      segment.innerHTML = `<p>${option.restaurant}</p>`;
      wheel.appendChild(segment);
    });

    let isSpinning = false;
    document.getElementById("spinButton").addEventListener("click", () => {
      if (isSpinning) return;
      isSpinning = true;

      // Spin animation
      let degrees = Math.floor(3600 + Math.random() * 3600);
      wheel.style.transform = `rotate(${degrees}deg)`;

      // Calculate result when spin ends
      setTimeout(() => {
        const selectedIndex = Math.floor((degrees % 360) / (360 / options.length));
        const chosen = options[selectedIndex];
        result.innerHTML = `Restaurant: <b>${chosen.restaurant}</b><br>Movie: <b>${chosen.movie}</b>`;
        isSpinning = false;
      }, 3000);
    });
  </script>
</body>
</html>
